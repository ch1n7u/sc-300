## 1. Why use an identity.?
![Pasted image 20260617173707](Images/Pasted%20image%2020260617173707.png)

---
## 2. Identity Provider (IDP)
![Pasted image 20260617185418](Images/Pasted%20image%2020260617185418.png)

---
## 3. Entra ID
![Pasted image 20260617192640](Images/Pasted%20image%2020260617192640.png)

![Pasted image 20260618000057](Images/Pasted%20image%2020260618000057.png)

---
## 4. Managing groups in Entra ID

### Types of groups:

#### i. Security Groups: 
- Used to manage access to applications, resources, and permissions.
- Members can be users, devices, service principals, and other groups (depending on configuration).
- Commonly used for Role-Based Access Control (RBAC) and resource authorization.

#### ii. Microsoft 365 Group

- Provides collaboration features in addition to membership management.
- Automatically creates shared resources such as:
    - Outlook mailbox
    - Calendar
    - SharePoint site
    - Teams workspace (when integrated)
- Members are typically users only.

#### -> Users can't be manually added in a dynamic group. 
---
## 5. Entra ID registered devices:
![Screenshot 2026-06-18 014355](Images/Screenshot%202026-06-18%20014355.png)

![Pasted image 20260618015830](Images/Pasted%20image%2020260618015830.png)

---
## 6. Entra roles


## 7. Licenses

#### Microsoft Entra ID Free

- Included with Microsoft 365 subscriptions.
- Basic user and group management.
- Self-service password change.
- Single Sign-On (SSO) for Microsoft cloud applications.
- Basic security and reporting.

---

#### Microsoft Entra ID P1 (Premium P1)

- Includes everything in Free.
- Dynamic groups.
- Self-Service Password Reset (SSPR) with writeback.
- Conditional Access policies.
- Hybrid identity management.
- Automatic user provisioning to SaaS applications.
- Group-based license assignment.

**Commonly used by:** Organizations implementing IAM and Zero Trust fundamentals.

---

#### Microsoft Entra ID P2 (Premium P2)

- Includes everything in P1.
- Identity Protection.
- Risk-based Conditional Access.
- Privileged Identity Management (PIM).
- Access Reviews.
- Entitlement Management.
- Advanced security reporting and analytics.

**Commonly used by:** Enterprises requiring privileged access governance and advanced identity security.

---

### Microsoft 365 E3

Microsoft 365 E3 includes:

- Microsoft Entra ID P1.
- Office desktop applications.
- Exchange Online.
- SharePoint Online.
- OneDrive for Business.
- Microsoft Teams.
- Basic compliance and security features.

**Entra License Included:** P1

---

### Microsoft 365 E5

Microsoft 365 E5 includes:

- Everything in E3.
- Microsoft Entra ID P2.
- Microsoft Defender suite.
- Microsoft Defender for Endpoint.
- Microsoft Defender for Office 365.
- Microsoft Defender for Identity.
- Microsoft Purview advanced compliance features.
- Advanced auditing and analytics.

**Entra License Included:** P2
