# Microsoft 365 Administration Lab

![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![Progress](https://img.shields.io/badge/Progress-4%2F10%20Completed-brightgreen)
![Microsoft 365](https://img.shields.io/badge/Microsoft%20365-Business%20Premium-blue)
![Microsoft Entra ID](https://img.shields.io/badge/Microsoft-Entra%20ID-0078D4)
![Platform](https://img.shields.io/badge/Platform-Cloud%20Administration-success)
![GitHub last commit](https://img.shields.io/github/last-commit/Amaggs99/Microsoft-365-Administration-Lab)

---

# Overview

This repository documents realistic Microsoft 365 administration scenarios performed within a Microsoft 365 Business Premium tenant.

The project simulates day-to-day responsibilities commonly performed by IT Support Specialists, Help Desk Technicians, Desktop Support Technicians, and Microsoft 365 Administrators.

Each ticket follows a structured enterprise documentation format including objectives, scenarios, resolution steps, verification, business impact, best practices, screenshots, and skills demonstrated.

---

# Lab Environment

| Component | Details |
|-----------|---------|
| Company | Maggs Technology Services |
| Tenant | Maggs777.onmicrosoft.com |
| Platform | Microsoft 365 Business Premium |
| Identity Platform | Microsoft Entra ID |
| Administration Portal | Microsoft 365 Admin Center |
| Location | Canada |
| Environment Type | Cloud Administration Lab |

---

# Technologies Used

- Microsoft 365 Business Premium
- Microsoft Entra ID
- Microsoft 365 Admin Center
- Exchange Online
- Microsoft Teams
- SharePoint Online
- OneDrive for Business
- Microsoft Defender
- Microsoft Intune
- Microsoft Graph
- PowerShell
- Git
- GitHub

---

# Skills Demonstrated

- Microsoft 365 Administration
- Microsoft Entra ID Administration
- User Provisioning
- User Lifecycle Management
- Identity and Access Management (IAM)
- License Management
- Password Management
- Account Management
- Security Group Administration
- Group Membership Management
- Role-Based Access Control Concepts
- Principle of Least Privilege
- Multi-Factor Authentication (MFA)
- Conditional Access
- Exchange Online Administration
- Mailbox Administration
- Mailbox Delegation
- Full Access Permission Management
- Send As Permission Management
- Shared Mailbox Administration
- Distribution Group Administration
- Microsoft 365 Security
- Cloud Identity Management
- Enterprise Documentation
- PowerShell Administration

---

# Lab Objectives

- Provision Microsoft 365 users
- Assign and manage Microsoft 365 licenses
- Reset passwords and manage user accounts
- Create and manage security groups
- Manage security group membership
- Configure mailbox delegation permissions
- Manage Full Access and Send As mailbox permissions
- Configure shared mailboxes
- Configure distribution groups
- Deploy Multi-Factor Authentication
- Configure Conditional Access policies
- Troubleshoot Exchange Online mail flow
- Perform user offboarding procedures

---

# Ticket Tracker

| Ticket | Title | Status |
|---------|-------|--------|
| M365-001 | [User Creation and License Assignment](Documentation/M365-001-User-Creation.md) | ✅ Completed |
| M365-002 | [Password Reset and Account Management](Documentation/M365-002-Password-Reset-and-Account-Management.md) | ✅ Completed |
| M365-003 | [Security Group Creation and Membership Management](Documentation/M365-003-Security-Groups.md) | ✅ Completed |
| M365-004 | [Mailbox Management](Documentation/M365-004-Mailbox-Management.md) | ✅ Completed |
| M365-005 | Distribution Groups | ⏳ Planned |
| M365-006 | Shared Mailboxes | ⏳ Planned |
| M365-007 | Multi-Factor Authentication Deployment | ⏳ Planned |
| M365-008 | Exchange Online Mail Flow Troubleshooting | ⏳ Planned |
| M365-009 | Conditional Access | ⏳ Planned |
| M365-010 | User Offboarding | ⏳ Planned |

---

# Repository Structure

```text
Microsoft-365-Administration-Lab/
│
├── README.md
│
├── Assets/
│   ├── Repo-Banner.png
│   ├── Architecture-Diagram.png
│   └── Icons/
│
├── Documentation/
│   ├── Commands-Used.md
│   ├── M365-Ticket-Tracker.md
│   ├── M365-001-User-Creation.md
│   ├── M365-002-Password-Reset-and-Account-Management.md
│   ├── M365-003-Security-Groups.md
│   ├── M365-004-Mailbox-Management.md
│   ├── M365-005-Distribution-Groups.md
│   ├── M365-006-Shared-Mailboxes.md
│   ├── M365-007-MFA-Deployment.md
│   ├── M365-008-Mail-Flow-Troubleshooting.md
│   ├── M365-009-Conditional-Access.md
│   └── M365-010-User-Offboarding.md
│
└── Screenshots/
    ├── M365-001-User-Creation/
    ├── M365-002-Password-Reset/
    ├── M365-003-Security-Groups/
    ├── M365-004-Mailbox-Management/
    ├── M365-005-Distribution-Groups/
    ├── M365-006-Shared-Mailboxes/
    ├── M365-007-MFA-Deployment/
    ├── M365-008-Mail-Flow-Troubleshooting/
    ├── M365-009-Conditional-Access/
    └── M365-010-User-Offboarding/
```

---

# Completed Labs

## M365-001 — User Creation and License Assignment

Created and configured a Microsoft 365 user account within the Microsoft 365 Admin Center and assigned the appropriate Microsoft 365 license.

**Key Skills:**

- Microsoft 365 user provisioning
- User account configuration
- License assignment
- Microsoft 365 Admin Center
- Cloud identity administration

[View M365-001 Documentation](Documentation/M365-001-User-Creation.md)

---

## M365-002 — Password Reset and Account Management

Performed an administrator-initiated password reset for a Microsoft 365 user, required the user to change the temporary password at the next sign-in, and verified successful account access.

**Key Skills:**

- Password administration
- User account management
- Identity and access management
- Microsoft 365 Admin Center
- End-user sign-in verification

[View M365-002 Documentation](Documentation/M365-002-Password-Reset-and-Account-Management.md)

---

## M365-003 — Security Group Creation and Membership Management

Created a Microsoft 365 security group for the Sales department and configured group membership by adding a user to the group.

The configuration was verified through the Microsoft 365 Admin Center to confirm successful group creation and membership assignment.

**Key Skills:**

- Security group administration
- Group membership management
- Identity and access management
- Role-based access control concepts
- Principle of least privilege
- Microsoft 365 Admin Center

[View M365-003 Documentation](Documentation/M365-003-Security-Groups.md)

---

## M365-004 — Mailbox Management

Configured mailbox delegation permissions for a Microsoft 365 user through the Exchange Admin Center.

Granted **Read and Manage (Full Access)** and **Send As** permissions to an authorized delegate and verified that both permissions were successfully assigned.

**Key Skills:**

- Exchange Online administration
- Exchange Admin Center
- Mailbox administration
- Mailbox delegation
- Full Access permission management
- Send As permission management
- Access control
- Administrative verification

[View M365-004 Documentation](Documentation/M365-004-Mailbox-Management.md)

---

# Learning Outcomes

This repository demonstrates practical experience with Microsoft 365 cloud administration by documenting realistic enterprise support and administration scenarios using Microsoft's administrative tools and industry best practices.

The objective is to build hands-on experience equivalent to common operational tasks performed in modern Microsoft 365 environments while maintaining professional documentation standards suitable for an IT portfolio.

Through the completed labs, this project currently demonstrates practical experience with:

- Microsoft 365 user provisioning
- Microsoft 365 license assignment
- Password reset procedures
- User account management
- Security group creation
- Security group membership management
- Identity and access management
- Exchange Online administration
- Mailbox administration
- Mailbox delegation
- Full Access permission management
- Send As permission management
- Cloud-based administration
- Administrative verification and troubleshooting
- Enterprise technical documentation

Additional Microsoft 365 administration scenarios will be added as the lab progresses.

---

# References

- Microsoft Learn
- Microsoft 365 Admin Center
- Microsoft Entra Admin Center
- Exchange Admin Center
- Microsoft Graph Documentation