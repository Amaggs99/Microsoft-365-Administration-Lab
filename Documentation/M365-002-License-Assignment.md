# M365-002 — Password Reset and Account Management

## Objective

Reset a Microsoft 365 user's password, require a password change at the next sign-in, revoke active user sessions, and verify successful access to the Microsoft 365 portal.

---

## Ticket Information

**Ticket ID:** M365-002

**Priority:** Medium

**Category:** Identity and Access Management

**Status:** Completed

---

## Scenario

A user contacted the IT Help Desk after forgetting their Microsoft 365 password and was unable to access company resources.

The account password needed to be reset while ensuring the user changed their password at the next sign-in. As a security precaution, all active Microsoft 365 sessions were revoked before the user signed in with the new credentials.

---

## Environment

| Item | Value |
|------|-------|
| Tenant | Maggs777.onmicrosoft.com |
| Platform | Microsoft 365 Business Premium |
| Administrator | Austin Maggs |
| User | Sarah Brown |
| Username | sbrown@Maggs777.onmicrosoft.com |

---

# Resolution

## Step 1 — Open User Account

Opened the Microsoft 365 Admin Center and navigated to:

**Users → Active users → Sarah Brown**

Verified the user account before making administrative changes.

---

## Step 2 — Reset Password

Reset the user's password and enabled:

- Require this user to change their password when they first sign in.

The password reset was completed successfully.

---

## Step 3 — Sign Out of All Sessions

Signed the user out of all active Microsoft 365 sessions to invalidate existing authentication tokens before the next sign-in.

---

## Step 4 — Verify User Access

Signed in as the user using the temporary password.

Confirmed Microsoft required a password change before granting access to Microsoft 365.

After creating a new password, verified successful access to the Microsoft 365 portal.

---

## Verification

Verified:

- Password reset completed successfully.
- User was required to change their password at first sign-in.
- Existing Microsoft 365 sessions were revoked.
- User successfully authenticated after creating a new password.
- Access to Microsoft 365 services was restored.

---

## Business Impact

Restored secure access to the user's Microsoft 365 account while ensuring account security through password rotation and session invalidation.

---

## Best Practices

- Require a password change after administrative password resets.
- Revoke active sessions following password resets to invalidate existing authentication tokens.
- Verify successful user authentication before closing the ticket.
- Avoid exposing passwords in documentation or screenshots.

---

## Screenshots

| Screenshot | Description |
|------------|-------------|
| 01-User-Account-Overview.png | User account prior to password reset. |
| 02-Password-Reset-Configuration.png | Password reset configuration with password change requirement enabled. |
| 03-Password-Reset-Confirmation.png | Successful password reset confirmation. |
| 04-Sign-Out-All-Sessions.png | Confirmation that all active Microsoft 365 sessions were revoked. |
| 05-Password-Change-Required-at-First-Sign-In.png | User prompted to create a new password during first sign-in. |
| 06-Successful-Microsoft-365-Sign-In.png | Successful authentication after password change. |

---

## Skills Demonstrated

- Microsoft 365 Administration
- Microsoft Entra ID User Management
- Password Administration
- Identity and Access Management (IAM)
- User Account Administration
- Session Revocation
- Authentication Troubleshooting
- Microsoft 365 Security Administration
- Help Desk Documentation
- IT Incident Resolution

---

## References

- Microsoft 365 Admin Center
- Microsoft Entra Admin Center
- Microsoft Learn Documentation