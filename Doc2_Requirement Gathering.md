# Active Directory and Azure AD Integration
# Requirement Gathering

DEPI Azure Architect

Team2

Global Knowledge Training Company

Sheraton

February 23, 2025

##

**Stakeholder Analysis**

| **Stakeholder** | **Role** | **Needs** | **Azure Benefit** | **Business Value** |
| --- | --- | --- | --- | --- |
| **Azure Architect** | Technical setup & management | Deploy AD DS on-premises/Azure, manage objects, sync with Azure AD | Azure VMs, Azure AD Connect | Streamlined hybrid management |
| --- | --- | --- | --- | --- |
| **End Users** | Daily system users | Single login for local/cloud resources (e.g., file servers, Office 365) | Azure AD SSO, Azure AD Join | Increased productivity, ease of access |
| --- | --- | --- | --- | --- |
| **IT Manager** | Strategic oversight | Scalability, cost-effective cloud integration, minimal downtime | Azure scalability, pay-as-you-go pricing | Cost savings, future-ready IT |
| --- | --- | --- | --- | --- |
| **Security Team** | Data & identity protection | Encryption (TLS, IPsec), MFA, compliance (e.g., GDPR) | Azure AD MFA, Azure Security Center | Reduced risk, regulatory alignment |
| --- | --- | --- | --- | --- |

**User Stories & Use Cases**

| **ID** | **Type** | **Description** | **Azure Components** | **Business Outcome** |
| --- | --- | --- | --- | --- |
| **US#1** | User Story | "As an admin/architect, I want to deploy AD DS on-premises and Azure to manage users across hybrid locations." | Azure VMs, AD DS | Flexible, redundant infrastructure |
| --- | --- | --- | --- | --- |
| **US#2** | User Story | "As a user, I want single credentials for local apps and Office 365 without multiple logins." | Azure AD, SSO | Enhanced user experience |
| --- | --- | --- | --- | --- |
| **UC#1** | Use Case | Admin configures DC-1 on-premises, deploys DC-2 in Azure, migrates AD data via VPN replication. | Azure VNet, VPN Gateway | Seamless DC migration, high availability |
| --- | --- | --- | --- | --- |
| **UC#2** | Use Case | User logs into Client-1, authenticates via DC or Azure AD, accesses Office 365 with SSO. | Azure AD, Azure AD Join | Simplified access, reduced IT support |
| --- | --- | --- | --- | --- |

**Functional Requirements**

| **Requirement** | **Description** | **Azure Solution** | **Technical Details** | **Business Impact** |
| --- | --- | --- | --- | --- |
| **AD DS Deployment** | Install AD DS on-premises (DC-1) and Azure (DC-2) for hybrid forest | Azure VMs, AD DS | Windows Server 2022, AD forest (CraftTheCloud.Local) | Unified identity management |
| --- | --- | --- | --- | --- |
| **DC Migration** | Migrate on-premises DC to Azure with minimal disruption | Azure VNet, VPN Gateway | Replication over secure VPN/ExpressRoute | High availability, disaster recovery |
| --- | --- | --- | --- | --- |
| **Object Management** | Create/manage users, groups, OUs via GUI and bulk scripts | ADUC, PowerShell | Bulk CSV imports, PowerShell automation | Efficient admin workflows |
| --- | --- | --- | --- | --- |
| **Synchronization** | Sync AD objects to Azure AD for hybrid identity | Azure AD Connect | Sync every 30 min, secure hash sync | Consistent identity across platforms |
| --- | --- | --- | --- | --- |
| **Azure AD Join** | Join client devices to Azure AD for cloud authentication | Azure AD Join | Windows 10/11, no on-premises DC reliance | Modern device management |
| --- | --- | --- | --- | --- |
| **Legacy App Support** | Provide LDAP/Kerberos for legacy apps via Azure AD DS | Azure AD DS | Managed LDAP endpoints, Kerberos auth | Backward compatibility |
| --- | --- | --- | --- | --- |

**Non-functional Requirements**

| **Category** | **Requirement** | **Azure Feature** | **Specification** | **Business Benefit** |
| --- | --- | --- | --- | --- |
| **Performance** | Sync latency < 5 min, auth response < 1 sec | Azure AD Connect, Azure AD | Optimized sync intervals, fast auth | Responsive system, user satisfaction |
| --- | --- | --- | --- | --- |
| **Security** | TLS/IPsec encryption, MFA, complex passwords, LDAPS | Azure AD MFA, Security Center | TLS for sync, IPsec for VPN, 12+ char passwords | Enhanced protection, compliance |
| --- | --- | --- | --- | --- |
| **Usability** | Intuitive admin interface (ADUC, Azure Portal), simple user login | Azure Portal, ADUC | Clear UI, sync status, minimal user steps | Reduced training, support costs |
| --- | --- | --- | --- | --- |
| **Reliability** | 99.9% uptime, redundant DCs, failover | Azure SLA, VM redundancy | Multi-DC replication, Azure Backup | Business continuity, trust |
| --- | --- | --- | --- | --- |
