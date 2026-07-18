\# M365-003 — Security Group Creation and Membership Management



\## Objective



Create and configure a Microsoft 365 security group using the Microsoft 365 Admin Center and add a user as a member of the group.



This task demonstrates how security groups can be used to organize users and provide controlled access to organizational resources.



\---



\## Ticket Information



\*\*Ticket ID:\*\* M365-003



\*\*Priority:\*\* Medium



\*\*Category:\*\* Identity and Access Management



\*\*Status:\*\* Completed



\---



\## Scenario



The Sales department requires a dedicated security group to simplify access management for department resources.



A new security group named \*\*Sales Team\*\* must be created in the Microsoft 365 tenant.



After creating the group, the user \*\*Sarah Brown\*\* must be added as a member.



The completed configuration should be verified through the Microsoft 365 Admin Center.



\---



\## Environment



| Item | Value |

|------|-------|

| Organization | Maggs Technology Services |

| Tenant | Maggs777.onmicrosoft.com |

| Platform | Microsoft 365 Business Premium |

| Administration Portal | Microsoft 365 Admin Center |

| Group Type | Security Group |

| Group Name | Sales Team |

| Test User | Sarah Brown |

| User Principal Name | sbrown@Maggs777.onmicrosoft.com |



\---



\## Resolution Steps



\### Step 1 — Navigate to Security Group Creation



Opened the \*\*Microsoft 365 Admin Center\*\* and navigated to:



\*\*Teams \& groups → Active teams \& groups\*\*



Selected the option to create a new \*\*Security group\*\*.



!\[Security Group Creation](../Screenshots/M365-003-Security-Groups/M365-003-01-Security-Group-Creation.png)



\---



\### Step 2 — Configure Security Group Details



Configured the new security group with the following information:



\*\*Group Name:\*\* Sales Team



\*\*Description:\*\* Security group for members of the Sales department.



The group was created as a standard security group for managing membership and access to organizational resources.



!\[Configure Security Group](../Screenshots/M365-003-Security-Groups/M365-003-02-Configure-Security-Group.png)



\---



\### Step 3 — Configure Group Settings



Reviewed the security group's role assignment settings.



The option to allow Microsoft Entra ID roles to be assigned to the group was left disabled because the group is intended for standard resource access management rather than administrative role assignment.



!\[Security Group Settings](../Screenshots/M365-003-Security-Groups/M365-003-03-Security-Group-Settings.png)



\---



\### Step 4 — Review and Create the Security Group



Reviewed the security group configuration before deployment.



The following settings were confirmed:



| Setting | Configuration |

|---------|---------------|

| Group Type | Security |

| Name | Sales Team |

| Description | Security group for members of the Sales department |

| Role Assignment | Disabled |



The group was then created.



!\[Review Security Group](../Screenshots/M365-003-Security-Groups/M365-003-04-Review-and-Create-Security-Group.png)



\---



\### Step 5 — Verify Security Group Creation



The Microsoft 365 Admin Center confirmed that the \*\*Sales Team\*\* security group was successfully created.



The group was then opened from the Active teams and groups interface to configure its membership.



!\[Security Group Created](../Screenshots/M365-003-Security-Groups/M365-003-05-Security-Group-Created.png)



\---



\### Step 6 — Add User to Security Group



Opened the \*\*Members\*\* configuration for the Sales Team security group.



Selected \*\*Sarah Brown\*\* and added the account to the group.



The Microsoft 365 Admin Center confirmed that the membership configuration was successfully saved.



!\[Verify Security Group Membership](../Screenshots/M365-003-Security-Groups/M365-003-06-Verify-Security-Group-Membership.png)



\---



\## Verification



The following checks were performed to verify successful completion of the task:



\- Confirmed the \*\*Sales Team\*\* security group was successfully created.

\- Confirmed the group type was configured as \*\*Security\*\*.

\- Confirmed administrative role assignment was disabled.

\- Confirmed the group appeared in the Microsoft 365 Admin Center.

\- Confirmed \*\*Sarah Brown\*\* was successfully added as a member.

\- Confirmed the group displayed \*\*1 member\*\*.

\- Confirmed the Microsoft 365 Admin Center displayed a \*\*Saved\*\* confirmation after the membership change.



\---



\## Result



The \*\*Sales Team\*\* security group was successfully created and configured.



The user \*\*Sarah Brown\*\* was successfully added as a member of the group.



The security group can now be used as part of role-based access and resource management within the Microsoft 365 environment.



\---



\## Business Impact



Security groups allow administrators to manage access to organizational resources based on group membership rather than assigning permissions individually to each user.



This provides several operational benefits:



\- Simplifies access management

\- Supports role-based access control principles

\- Reduces repetitive administrative tasks

\- Improves consistency when assigning resource permissions

\- Simplifies onboarding and offboarding workflows

\- Supports the principle of least privilege when properly configured



For example, access to resources used by the Sales department can be assigned to the \*\*Sales Team\*\* security group. Administrators can then manage access by adding or removing users from the group.



\---



\## Best Practices



\- Use descriptive and standardized group names.

\- Document the business purpose of each security group.

\- Assign access through groups instead of directly to individual users whenever possible.

\- Regularly review group membership.

\- Remove users who no longer require access.

\- Avoid enabling role-assignable groups unless administrative role assignment is specifically required.

\- Follow the principle of least privilege when assigning resource permissions.

\- Maintain documentation for security-sensitive group changes.



\---



\## Skills Demonstrated



\- Microsoft 365 Administration

\- Microsoft 365 Admin Center

\- Microsoft Entra ID

\- Security Group Administration

\- Group Membership Management

\- Identity and Access Management (IAM)

\- Role-Based Access Control Concepts

\- Principle of Least Privilege

\- User Access Management

\- Cloud Administration

\- Enterprise Documentation



\---



\## Conclusion



This ticket demonstrated the creation and management of a Microsoft 365 security group.



The \*\*Sales Team\*\* security group was created through the Microsoft 365 Admin Center, configured without administrative role assignment, and updated to include \*\*Sarah Brown\*\* as a member.



The completed task demonstrates practical experience with security group administration and group-based access management in a Microsoft 365 environment.

