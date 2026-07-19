Overview
Enterprise Active Directory Lab

A Windows Server 2025 enterprise lab demonstrating Active Directory Domain Services, Group Policy, SMB file sharing, NTFS permissions, and Role-Based Access Control (RBAC).

Project Overview

This project simulates a small enterprise Windows environment using Windows Server 2022 and a Windows 11 domain-joined client. The lab demonstrates centralized identity management, organizational unit design, Group Policy implementation, SMB file sharing, and NTFS permissions using Microsoft's Active Directory Domain Services.

Objectives
Deploy an Active Directory domain
Create an enterprise Organizational Unit structure
Create domain users
Configure departmental security groups
Implement Role-Based Access Control (RBAC)
Create SMB departmental file shares
Configure NTFS permissions
Deploy Group Policy Objects (GPOs)
Join a Windows client to the domain
Validate authentication and resource access
Lab Environment
Component	Technology
Hypervisor	VMware Workstation
Domain Controller	Windows Server 2022
Client	Windows 11 Enterprise
Directory Service	Active Directory Domain Services
DNS	Windows DNS
Group Policy	GPMC
File Sharing	SMB
Permissions	NTFS ACLs
Authentication	Active Directory
Network Diagram
                     Internet
                         │
                VMware Virtual Network
                         │
        ┌────────────────┴────────────────┐
        │                                 │
┌──────────────────┐          ┌────────────────────┐
│ Windows Server   │          │ Windows 11 Client  │
│ DC01             │──────────│ CLIENT01           │
│ corp.local       │          │ Domain Joined      │
│ AD DS            │          │ Emily Davis        │
│ DNS              │          │ Jessica Brown      │
│ SMB Shares       │          └────────────────────┘
└──────────────────┘
Organizational Unit Structure
corp.local

├── Finance
├── HR
├── IT
├── Management
├── Sales
├── Servers
└── Workstations
Features Implemented
Active Directory
Organizational Units
Domain Users
Security Groups
Administrative Organization
File Services

Created departmental SMB shares:

Finance
HR
IT
Management
Sales

Configured:

Share Permissions
NTFS Permissions
RBAC
Group Policy

Implemented Enterprise Workstation Policy

Configured:

Login Banner
Enterprise Security Options
Workstation Policy Deployment
Policy linked to Workstations OU
Security

Implemented:

Role-Based Access Control (RBAC)
NTFS ACLs
Departmental Isolation
Authorized Share Access
Enterprise Login Warning Banner
Validation

The following tests were successfully completed:

Active Directory deployment
User account creation
SMB share creation
NTFS permissions
GPO deployment
Windows client domain join
Domain authentication
Group Policy application
Network share access
Screenshots


Active Directory
Screenshot	Description
AD OU Structure	Organizational Unit hierarchy
Domain Users	Created enterprise users
File Shares
Screenshot	Description
SMB Shares	Department shares
NTFS Permissions	HR folder permissions
Group Policy
Screenshot	Description
GPO Linked	Enterprise Workstation Policy
Security Options	Login banner configuration
Client Validation
Screenshot	Description
Login Banner	Legal notice displayed
Successful Domain Login	Emily Davis logged into the domain
Successful Share Access	HR share opened successfully
Domain Membership	Client joined to corp.local
gpresult /r	Policy successfully applied
Skills Demonstrated
Active Directory Administration
Windows Server Administration
Active Directory Users and Computers
Group Policy Management
DNS
SMB File Services
NTFS Permissions
RBAC
Windows Client Management
Enterprise Authentication
Windows Security
What I Learned

Through this project I gained hands-on experience deploying and managing a Windows enterprise environment. I configured centralized identity management with Active Directory, implemented Group Policy Objects, secured departmental file shares using NTFS permissions and RBAC, and validated authentication from a domain-joined Windows client. This lab reinforced core enterprise administration concepts that are commonly used in corporate Windows infrastructures.
