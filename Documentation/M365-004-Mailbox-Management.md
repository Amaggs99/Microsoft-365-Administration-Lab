\# M365-004 — Mailbox Delegation and Permission Management



\## Objective



Configure mailbox delegation permissions in the Microsoft Exchange Admin Center to allow an authorized user to access and send email from another user's mailbox.



This task demonstrates how Microsoft 365 administrators can manage mailbox delegation by assigning \*\*Read and Manage (Full Access)\*\* and \*\*Send As\*\* permissions.



\---



\## Ticket Information



\*\*Ticket ID:\*\* M365-004



\*\*Priority:\*\* Medium



\*\*Category:\*\* Exchange Online / Mailbox Administration



\*\*Status:\*\* Completed



\---



\## Scenario



A user requires delegated access to another employee's mailbox to assist with mailbox management and email communication.



The administrator must configure the appropriate permissions in the Exchange Admin Center.



The following permissions are required:



\- \*\*Read and Manage (Full Access)\*\* — Allows the delegate to open and manage the mailbox.

\- \*\*Send As\*\* — Allows the delegate to send email that appears to originate directly from the mailbox owner.



For this task, \*\*Austin Maggs\*\* was configured as a delegate for \*\*Sarah Brown's\*\* mailbox.



After configuring the permissions, the mailbox delegation settings were reviewed to verify that both permissions were successfully assigned.



\---



\## Environment



| Item | Value |

|---|---|

| Platform | Microsoft 365 |

| Administration Portal | Exchange Admin Center |

| Service | Exchange Online |

| Target Mailbox | Sarah Brown |

| Delegate User | Austin Maggs |

| Permissions | Read and Manage (Full Access), Send As |



\---



\## Resolution Steps



\### 1. Access the Exchange Admin Center



Opened the \*\*Exchange Admin Center\*\* and navigated to:



\*\*Recipients → Mailboxes\*\*



Selected \*\*Sarah Brown's\*\* user mailbox and opened the \*\*Delegation\*\* settings.



\---



\### 2. Configure Read and Manage (Full Access)



Under \*\*Read and manage (Full Access)\*\*, selected \*\*Edit\*\* and added \*\*Austin Maggs\*\* as a delegate.



Full Access permission allows the delegate to open the mailbox and manage its contents.



!\[Full Access Delegate Configured](../Screenshots/M365-004/01-Full-Access-Delegate-Configured.png)



\---



\### 3. Save Full Access Permission



Saved the configuration to apply the new mailbox delegation permission.



The Exchange Admin Center confirmed that the mailbox permission was successfully added.



!\[Mailbox Permissions Successfully Added](../Screenshots/M365-004/02-Mailbox-Permissions-Successfully-Added.png)



\---



\### 4. Configure Send As Permission



Returned to the mailbox delegation settings and selected \*\*Edit\*\* under \*\*Send as\*\*.



Added \*\*Austin Maggs\*\* as an authorized delegate.



The \*\*Send As\*\* permission allows the delegate to send email that appears to originate directly from the mailbox owner.



!\[Send As Delegate Configured](../Screenshots/M365-004/03-Send-As-Delegate-Configured.png)



\---



\### 5. Save Send As Permission



Saved the configuration to apply the \*\*Send As\*\* permission.



The Exchange Admin Center confirmed that the mailbox permission was successfully added.



!\[Send As Permission Successfully Added](../Screenshots/M365-004/04-Send-As-Permission-Successfully-Added.png)



\---



\### 6. Verify Mailbox Delegation



Returned to the mailbox delegation configuration and verified that \*\*Austin Maggs\*\* appeared as an authorized delegate for both configured permissions:



\- Read and Manage (Full Access)

\- Send As



This confirmed that the required mailbox delegation permissions were successfully configured.



!\[Mailbox Delegation Permissions Verified](../Screenshots/M365-004/05-Mailbox-Delegation-Permissions-Verified.png)



\---



\## Verification



The mailbox delegation configuration was reviewed in the Exchange Admin Center.



The following permissions were verified:



| Permission | Delegate | Status |

|---|---|---|

| Read and Manage (Full Access) | Austin Maggs | Configured |

| Send As | Austin Maggs | Configured |



The successful configuration confirms that the delegate has been granted the required mailbox access permissions.



\---



\## Result



Mailbox delegation was successfully configured for \*\*Sarah Brown's\*\* mailbox.



\*\*Austin Maggs\*\* was granted:



\- \*\*Read and Manage (Full Access)\*\* permission to access and manage the mailbox.

\- \*\*Send As\*\* permission to send messages that appear to originate from Sarah Brown's mailbox.



The final mailbox delegation settings were reviewed to verify that both permissions were correctly assigned.



\---



\## Skills Demonstrated



\- Microsoft 365 Administration

\- Exchange Online Administration

\- Exchange Admin Center

\- Mailbox Administration

\- Mailbox Delegation

\- Full Access Permission Management

\- Send As Permission Management

\- Identity and Access Management

\- User Permission Administration

\- Access Control

\- Administrative Verification

\- Technical Documentation



\---



\## Key Takeaways



\- Mailbox delegation allows administrators to provide controlled access to another user's mailbox without sharing account credentials.

\- \*\*Read and Manage (Full Access)\*\* allows a delegate to open and manage mailbox contents.

\- \*\*Send As\*\* allows a delegate to send messages that appear to come directly from the mailbox owner.

\- Full Access and Send As are separate permissions and must be configured independently when both capabilities are required.

\- Mailbox permissions should be verified after configuration to ensure the correct delegate has been assigned the required level of access.



\---



\## Conclusion



This task demonstrated the process of configuring mailbox delegation permissions using the Microsoft Exchange Admin Center.



By assigning \*\*Read and Manage (Full Access)\*\* and \*\*Send As\*\* permissions, the delegate was provided with the necessary access to manage the user's mailbox and send email on behalf of the mailbox identity.



The completed configuration demonstrates practical experience with Exchange Online mailbox administration, delegated access, permission management, and administrative verification within a Microsoft 365 environment.

