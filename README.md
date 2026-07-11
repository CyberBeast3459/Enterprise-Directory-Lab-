Overview

This project demonstrates the deployment of an enterprise Windows Server 2022 Active Directory environment. The lab includes Organizational Units (OUs), security groups, Group Policy Objects (GPOs), SMB file shares, and NTFS permissions to simulate a real-world corporate infrastructure.

Technologies Used
Windows Server 2022
Active Directory Domain Services (AD DS)
Group Policy Management
DNS
SMB File Sharing
NTFS Permissions
RBAC (Role-Based Access Control)
VMware Workstation
Windows 11 Client
Lab Architecture
DC01 (Windows Server 2022)
│
├── Active Directory
│   ├── HR OU
│   ├── Finance OU
│   ├── IT OU
│   ├── Management OU
│   ├── Sales OU
│   └── Workstations OU
│
├── Security Groups
│   ├── HR_Users
│   ├── Finance_Users
│   ├── IT_Admins
│   └── Sales_Users
│
└── Department File Shares
    ├── HR
    ├── Finance
    ├── IT
    ├── Management
    └── Sales

Client01 (Windows 11)
Features
Domain Controller deployment
Active Directory Organizational Units
Departmental user accounts
Security Groups
Role-Based Access Control
Department SMB shares
NTFS permissions
Group Policy Objects
Custom enterprise login banner
Client joined to the domain
Access control validation
Screenshots

Then make a table like this:

Screenshot	Description
OU Structure	Active Directory organizational structure
HR Users	HR department user accounts
Security Groups	Department security groups
NTFS Permissions	Folder permissions
Department Shares	SMB shared folders
GPO Creation	Enterprise Workstation Policy
Login Banner	Custom legal notice
Access Denied	Unauthorized access blocked
Successful Access	Authorized department access
Learning Outcomes
Designed an enterprise Active Directory environment
Implemented RBAC using security groups
Configured SMB file sharing
Applied NTFS permissions
Created and linked Group Policy Objects
Managed Organizational Units
Validated access control from a domain-joined workstatio
