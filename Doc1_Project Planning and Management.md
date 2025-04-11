# Active Directory and Azure AD Integration
# Project Planning & Management
02.23.2025

**───────**

DEPI Azure Architect

Team2

Global Knowledge Training Company

Sheraton

# Project Overview

As Azure Cloud Architects, we are excited to present an overview of the Active Directory and Azure AD Integration project. This project aims to seamlessly integrate on-premises Active Directory (AD) with Azure Active Directory (Azure AD), creating a robust hybrid identity solution that enhances security, scalability, and user experience.  
<br/>This project is a critical step towards modernizing our identity management infrastructure, aligning with best practices, and leveraging the full potential of Azure's cloud capabilities. I look forward to collaborating with the team to successfully execute this project and achieve our goals.

# Goals

1. Deploy and Configure AD DS: Establish a reliable Active Directory Domain Services (AD DS) environment both on-premises and in Azure, ensuring high availability and redundancy.
2. Migrate Domain Controller to Azure: Transition an existing on-premises domain controller to Azure, leveraging Azure's infrastructure for improved performance and disaster recovery.
3. Create and Manage AD Objects: Efficiently manage AD users, groups, and organizational units (OUs) through automated and bulk operations, ensuring streamlined administration.
4. Extend AD to Azure: Implement Azure AD Domain Services (Azure AD DS) and configure synchronization between on-premises AD and Azure AD, enabling a unified identity management system.
5. Final Review and Presentation: Conduct a comprehensive review of the integration, document the entire process, and present the outcomes to stakeholders for feedback and future improvements.

## **Benefits of the Project**

Enhanced Security: By integrating on-premises AD with Azure AD, we can leverage advanced security features such as multi-factor authentication (MFA) and conditional access policies.

Improved Scalability: Azure's scalable infrastructure ensures that our AD environment can grow with our organizational needs without compromising performance.

Seamless User Experience: Users will benefit from a consistent identity across on-premises and cloud environments, simplifying access to resources and applications.

Disaster Recovery: Hosting domain controllers in Azure provides a robust disaster recovery solution, ensuring business continuity in case of on-premises failures.

# Project Plan Timeline (Week-by-Week Breakdown)

**Week 1: Active Directory Deployment**

Tasks: Deploy AD DS on-premises and in Azure, migrate a domain controller to Azure.

Deliverables: Detailed documentation of the deployment and migration process, including network diagrams and step-by-step guides.

**Week 2: Create and Manage AD Objects**

Tasks: Create and manage AD users, groups, and OUs; perform bulk operations using PowerShell.

Deliverables: Comprehensive report on AD object management, including screenshots, configuration details, and PowerShell scripts.

**Week 3: Extend AD to Azure**

Tasks: Deploy Azure AD DS, configure synchronization with Azure AD Connect, and implement Azure AD Join for devices.

Deliverables: Documentation of Azure AD DS deployment, synchronization configuration, and troubleshooting guide for common issues.

**Week 4: Final Review and Presentation**

Tasks: Review the integration, prepare a final report, and present the project outcomes to stakeholders.

Deliverables: Final report on AD integration, presentation slides, and detailed feedback from stakeholders.

# Milestones

| Week | Task | Milestone | Assigned Architect(s) |
| --- | --- | --- | --- |
| 1   | Active Directory Deployment | AD DS deployed on-premises and in Azure | Hassan Sayed Hassan, Islam Hamdy Abdo |
| Domain controller migrated to Azure | Hassan Sayed Hassan, Islam Hamdy Abdo |
| 2   | Create and Manage AD Objects | AD users, groups, and OUs created and managed | Yasen Mahmoud Ahmed, Alaa Mohamed Gomaa |
| Bulk operations performed | Yasen Mahmoud Ahmed, Alaa Mohamed Gomaa |
| 3   | Extend AD to Azure | Azure AD DS deployed | Hassan Sayed Hassan, Islam Hamdy Abdo |
| Synchronization configured | Hassan Sayed Hassan, Islam Hamdy Abdo |
| Azure AD Join implemented | Yasen Mahmoud Ahmed, Alaa Mohamed Gomaa |
| 4   | Final Review and Presentation | Integration reviewed | All architects |
| Final report prepared | All architects |
| Project outcomes presented | All architects |

**Gantt Chart**

| Task | Week 1 | Week 2 | Week 3 | Week 4 | Milestone |
| --- | --- | --- | --- | --- | --- |
| Deploy AD DS On-Premises | X   |     |     |     | AD DS On-Premises Deployed |
| Configure AD DS in Azure | X   |     |     |     | AD DS Configured in Azure |
| Migrate Domain Controller to Azure | X   |     |     |     | Domain Controller Migrated |
| Create AD Users |     | X   |     |     | AD Users Created |
| Manage AD Groups and OUs |     | X   |     |     | Groups and OUs Managed |
| Perform Bulk Operations on AD Objects |     | X   |     |     | Bulk Operations Completed |
| Deploy Azure AD DS |     |     | X   |     | Azure AD DS Deployed |
| Configure Synchronization with On-Premises AD |     |     | X   |     | Synchronization Configured |
| Implement Azure AD Join |     |     | X   |     | Azure AD Join Implemented |
| Review Integration |     |     |     | X   | Integration Reviewed |
| Prepare Final Report |     |     |     | X   | Final Report Prepared |
| Present Findings to Stakeholders |     |     |     | X   | Presentation Delivered |

**Task Assignment & Roles**

| ![People](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAgCAMAAABXc8oyAAADAFBMVEUAAABAQEBERkZFR0ZER0ZDR0VISEhFRUVERkVER0ZDR0dDRkNESERDRkZER0VESEhESEZCR0RDR0ZER0dERkZGRkZDRkRARUVASEhERkVFSEhDR0VER0ZGRkZDR0VFSEVFRUVFR0VER0YAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACxWeV0AAAAInRSTlMAEH/fz58gMO/vn1BAoL9AgHDfcIBQoDAgz2CQr19vYGBvGxXIWQAAATxJREFUeF7lUl1Pg0AQnAWKacWCLdq0D9b//6/aJqSNWoFCY0GpC1TYW2Pii09Ocrmd3cndfgH/EaQdIKIl1kSFcpsUuKJFc6+ck+G3DQa4VqtDkNsfMqBftJfAln+/A55TGXAkAfwpsD+yYU8QVpmIWMJuaRzXRhxxuioiwSm/t5ar0lJCzr9srRw4y4gSsmreuCwuyuiPrnocApuRSx6nuZcBLZwllz4iCrYyoIWYlUFzR/7O8OvJIPdja4BVlcsm/gl0jjQnSnNcj89FYiyaISTyQkHX812vFUJavHy1psOm29++6ofT7Q1f0ck+OueMd6Nm/ji5DLJ78bGeXDRN+q54VNY/HJ4a1r04HCAq81QUUBThYcjCduSd8J6PMVxG9lZ4GL02ttzwyhekxaSzpPC7TkDt48/4tfATbQFS+X53JHAAAAAASUVORK5CYII=) Name | ![Dropdowns](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAgCAYAAABgrToAAAABhUlEQVR4AWIgDEbBKBgFo2AUODg4CAB6rYLihoEYSCUQAuEmdyuJRczAZhAzSRi4DAwhEAqhENpq+pHnGsVW4nv4dyOtd1fSFqJLYcxg+ixM36GP8PVXA72IHF4GpkW0oN84/mXGNQw0M3r9Yy208/fbg4dN4FTOuhBmCLokKSxNAo4nQZeZplp+uqxnzsqgnpOS3u5rkUOu/MzDc88tZb3rgOw7fLhbuV1PZio3y1wAXAjkkknMj9kzdKsErdaYWsj2/peYE5fBPPpovWsX64xodB9koXNrgAA6V2Y7HACO22WicfXuk5qhZCym16pqYAvEvURjBJyPIQzQB+mDCwBUWp0JDoDcBk5tZfehOyRq2Cg4C9IDFxgSGt0HUZA+OHskJvfk6XJcSlJSk/3iHwlH5oanzvo/M1/dhNE6LGgPm7j9ATUnzzIZTb2+PyXBiVuRXTYR0TlyZaxCEOnUShvWkMNkg8ivPTRlx1Mv0W0/gJgrz8XjOXotGGLV+FlrqJxrh+8Hfz5iz8X39iMAAAAASUVORK5CYII=) Role | ![Dropdowns](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAgCAYAAABgrToAAAABhUlEQVR4AWIgDEbBKBgFo2AUODg4CAB6rYLihoEYSCUQAuEmdyuJRczAZhAzSRi4DAwhEAqhENpq+pHnGsVW4nv4dyOtd1fSFqJLYcxg+ixM36GP8PVXA72IHF4GpkW0oN84/mXGNQw0M3r9Yy208/fbg4dN4FTOuhBmCLokKSxNAo4nQZeZplp+uqxnzsqgnpOS3u5rkUOu/MzDc88tZb3rgOw7fLhbuV1PZio3y1wAXAjkkknMj9kzdKsErdaYWsj2/peYE5fBPPpovWsX64xodB9koXNrgAA6V2Y7HACO22WicfXuk5qhZCym16pqYAvEvURjBJyPIQzQB+mDCwBUWp0JDoDcBk5tZfehOyRq2Cg4C9IDFxgSGt0HUZA+OHskJvfk6XJcSlJSk/3iHwlH5oanzvo/M1/dhNE6LGgPm7j9ATUnzzIZTb2+PyXBiVuRXTYR0TlyZaxCEOnUShvWkMNkg8ivPTRlx1Mv0W0/gJgrz8XjOXotGGLV+FlrqJxrh+8Hfz5iz8X39iMAAAAASUVORK5CYII=) Project Phase | ![Dropdowns](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAgCAYAAABgrToAAAABhUlEQVR4AWIgDEbBKBgFo2AUODg4CAB6rYLihoEYSCUQAuEmdyuJRczAZhAzSRi4DAwhEAqhENpq+pHnGsVW4nv4dyOtd1fSFqJLYcxg+ixM36GP8PVXA72IHF4GpkW0oN84/mXGNQw0M3r9Yy208/fbg4dN4FTOuhBmCLokKSxNAo4nQZeZplp+uqxnzsqgnpOS3u5rkUOu/MzDc88tZb3rgOw7fLhbuV1PZio3y1wAXAjkkknMj9kzdKsErdaYWsj2/peYE5fBPPpovWsX64xodB9koXNrgAA6V2Y7HACO22WicfXuk5qhZCym16pqYAvEvURjBJyPIQzQB+mDCwBUWp0JDoDcBk5tZfehOyRq2Cg4C9IDFxgSGt0HUZA+OHskJvfk6XJcSlJSk/3iHwlH5oanzvo/M1/dhNE6LGgPm7j9ATUnzzIZTb2+PyXBiVuRXTYR0TlyZaxCEOnUShvWkMNkg8ivPTRlx1Mv0W0/gJgrz8XjOXotGGLV+FlrqJxrh+8Hfz5iz8X39iMAAAAASUVORK5CYII=) Contributions |
| --- | --- | --- | --- |
| Alaa Mohamed Gomaa | Azure Architect | Week 1: Active Directory Deployment | Deploy and configure Active Directory Domain Services (AD DS) onpremises and in Azure. Migrate a domain controller to Azure. |
| Hassan Sayed Hassan | Azure Architect | Week 2: Create and Manage AD Objects | Create and manage AD users, groups, and organizational units. Perform bulk operations and configure object properties. |
| Yasen Mahmoud Ahmed | Azure Architect | Week 3: Extend AD to Azure | Deploy Azure AD DS, configure synchronization between on-premises AD and Azure AD, and implement Azure AD Join. |
| Islam Hamdy Abdo | Azure Architect | Week 4: Final Review and Presentation | Review the integration, prepare a final report, and present the project outcomes to stakeholders. |

# Contributors Architects’ Github Accounts

| ![People](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAgCAMAAABXc8oyAAADAFBMVEUAAABAQEBERkZFR0ZER0ZDR0VISEhFRUVERkVER0ZDR0dDRkNESERDRkZER0VESEhESEZCR0RDR0ZER0dERkZGRkZDRkRARUVASEhERkVFSEhDR0VER0ZGRkZDR0VFSEVFRUVFR0VER0YAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACxWeV0AAAAInRSTlMAEH/fz58gMO/vn1BAoL9AgHDfcIBQoDAgz2CQr19vYGBvGxXIWQAAATxJREFUeF7lUl1Pg0AQnAWKacWCLdq0D9b//6/aJqSNWoFCY0GpC1TYW2Pii09Ocrmd3cndfgH/EaQdIKIl1kSFcpsUuKJFc6+ck+G3DQa4VqtDkNsfMqBftJfAln+/A55TGXAkAfwpsD+yYU8QVpmIWMJuaRzXRhxxuioiwSm/t5ar0lJCzr9srRw4y4gSsmreuCwuyuiPrnocApuRSx6nuZcBLZwllz4iCrYyoIWYlUFzR/7O8OvJIPdja4BVlcsm/gl0jjQnSnNcj89FYiyaISTyQkHX812vFUJavHy1psOm29++6ofT7Q1f0ck+OueMd6Nm/ji5DLJ78bGeXDRN+q54VNY/HJ4a1r04HCAq81QUUBThYcjCduSd8J6PMVxG9lZ4GL02ttzwyhekxaSzpPC7TkDt48/4tfATbQFS+X53JHAAAAAASUVORK5CYII=) Name | Github Link |
| --- | --- |
| Hassan Sayed Hassan | <https://github.com/hassansayed99> |
| Islam Hamdy Abdo | <https://github.com/islamyassein> |
| Yasen Mahmoud Ahmed | <https://github.com/YasenMahmoudAhmed> |
| Alaa Mohamed Gomaa | <https://github.com/alaaMohamed1219> |

## **Contributors Architects’ Contacts and Emails**

| ![People](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAgCAMAAABXc8oyAAADAFBMVEUAAABAQEBERkZFR0ZER0ZDR0VISEhFRUVERkVER0ZDR0dDRkNESERDRkZER0VESEhESEZCR0RDR0ZER0dERkZGRkZDRkRARUVASEhERkVFSEhDR0VER0ZGRkZDR0VFSEVFRUVFR0VER0YAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACxWeV0AAAAInRSTlMAEH/fz58gMO/vn1BAoL9AgHDfcIBQoDAgz2CQr19vYGBvGxXIWQAAATxJREFUeF7lUl1Pg0AQnAWKacWCLdq0D9b//6/aJqSNWoFCY0GpC1TYW2Pii09Ocrmd3cndfgH/EaQdIKIl1kSFcpsUuKJFc6+ck+G3DQa4VqtDkNsfMqBftJfAln+/A55TGXAkAfwpsD+yYU8QVpmIWMJuaRzXRhxxuioiwSm/t5ar0lJCzr9srRw4y4gSsmreuCwuyuiPrnocApuRSx6nuZcBLZwllz4iCrYyoIWYlUFzR/7O8OvJIPdja4BVlcsm/gl0jjQnSnNcj89FYiyaISTyQkHX812vFUJavHy1psOm29++6ofT7Q1f0ck+OueMd6Nm/ji5DLJ78bGeXDRN+q54VNY/HJ4a1r04HCAq81QUUBThYcjCduSd8J6PMVxG9lZ4GL02ttzwyhekxaSzpPC7TkDt48/4tfATbQFS+X53JHAAAAAASUVORK5CYII=) Name | ![No type](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAgAQMAAABaY6hDAAAABlBMVEUAAABER0byc6G0AAAAAXRSTlMAQObYZgAAAB5JREFUeAFjIBXw//+PhQRRDDhI5v8fsJIMcgyUkwA7RRKRO1GB3wAAAABJRU5ErkJggg==) Email |
| --- | --- |
| Hassan Sayed Hassan | <hassansayed2131999@gmail.com> |
| Islam Hamdy Abdo | <islamyassein@outlook.com> |
| Yasen Mahmoud Ahmed | <faridayasen7@gmail.com> |
| Alaa Mohamed Gomaa | <amgg5672@gmail.com> |

**Risk Assessment & Mitigation Plan**

**1\. Data Security Risks**

Risk: There's a chance that sensitive data could be accessed by unauthorized users during the migration and synchronization process.

Mitigation: To prevent this, we'll implement multi-factor authentication (MFA), encrypt data both in transit and at rest, and regularly audit access logs to catch any suspicious activity.

**2\. Synchronization Issues**

Risk: Sometimes, synchronization between on-premises AD and Azure AD might fail or be inconsistent.

Mitigation: We'll use Azure AD Connect Health to keep an eye on synchronization, set up alerts for any failures, and ensure our synchronization rules are properly configured.

**3\. Downtime During Migration**

Risk: Migrating domain controllers to Azure could cause some downtime, which might disrupt business operations.

Mitigation: We'll plan the migration during off-peak hours, use a phased approach to minimize impact, and have a rollback plan ready just in case something goes wrong.

**4\. Configuration Errors**

Risk: Misconfigurations can lead to security vulnerabilities or operational issues.

Mitigation: We'll follow best practices and guidelines, conduct thorough testing in a staging environment, and have peer reviews to catch any mistakes.

**5\. User Provisioning and De-provisioning**

Risk: Errors in provisioning and de-provisioning users can pose security risks.

Mitigation: We'll automate these processes using tools like Azure AD Connect and regularly review and update our user access policies.

**6\. Network Connectivity Issues**

Risk: Network problems could affect connectivity between on-premises and Azure environments.

Mitigation: We'll ensure we have redundant network connections, use VPN or ExpressRoute for secure and reliable connectivity, and monitor network performance closely.

**KPIs (Key Performance Indicators)**

**Key Performance Indicators (KPIs) for Azure AD Integration Architecture**

| **KPI** | **Description** | **Target** | **Azure Metric/Tool** | **Measurement Frequency** | **Business Impact** |
| --- | --- | --- | --- | --- | --- |
| **AD Sync Latency** | Time taken to sync AD objects from on-premises to Azure AD | < 5 minutes | Azure AD Connect Health | Hourly | Ensures real-time identity updates |
| **Authentication Response Time** | Time for user authentication (local or cloud) to complete | < 1 second | Azure AD Sign-in Logs, DC Event Logs | Real-time | Improves user experience |
| **System Uptime** | Availability of AD DS (DC-1, DC-2) and Azure AD services | 99.9% | Azure Monitor, VM Availability Metrics | Daily | Guarantees business continuity |
| **Successful Sync Rate** | Percentage of AD objects successfully synced without errors | 100% | Azure AD Connect Sync Errors | Per Sync Cycle (30 min) | Maintains data consistency |
| **MFA Adoption Rate** | Percentage of users enrolled in Azure AD MFA | 90%+ | Azure AD MFA Usage Reports | Weekly | Enhances security compliance |
| **Replication Success Rate** | Percentage of successful AD replications between DC-1 and DC-2 | 99.5% | Azure Monitor, AD Replication Status | Hourly | Ensures redundancy and failover |
| **Cost Efficiency** | Monthly cost of Azure resources (VMs, VPN, Azure AD DS) vs. budget | Within 10% of budget | Azure Cost Management | Monthly | Optimizes financial performance |
| **User Login Success Rate** | Percentage of successful login attempts via AD DS or Azure AD | 98%+ | Azure AD Sign-in Logs | Daily | Reduces support tickets |
| **Legacy App Accessibility** | Percentage of legacy apps accessible via Azure AD DS | 100% | Azure AD DS Health, App Logs | Weekly | Supports business-critical apps |
| **Deployment Time** | Time to deploy and configure all components (DC-2, Azure AD, VNet, etc.) | < 4 weeks | Azure Deployment Tracker | One-time (project end) | Meets project timeline |
