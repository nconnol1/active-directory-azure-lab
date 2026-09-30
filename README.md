# Active Directory Azure Lab

## Overview

This project documents a hands-on Active Directory lab built using Microsoft Azure and Windows Server.

The purpose of this project is to gain practical experience with Windows Server administration, Active Directory Domain Services (AD DS), DNS, user and group management, PowerShell, Group Policy, domain authentication, and basic troubleshooting.

The lab is being built from scratch and documented throughout the process.

---

## Lab Architecture

The lab will consist of a Windows Server domain controller and a Windows client connected through an Azure virtual network.

```text
                    Microsoft Azure
                           |
                    Azure Virtual Network
                           |
              +------------+------------+
              |                         |
            DC01                     CLIENT01
       Windows Server              Windows Client
              |                         |
              +------------+------------+
                           |
                    Active Directory
                           |
                       adlab.test
```

---

## Objectives

The objectives of this lab are to:

- Deploy Windows infrastructure in Microsoft Azure
- Install Active Directory Domain Services
- Promote a Windows Server to a domain controller
- Configure DNS
- Create an Active Directory domain
- Create and organize Organizational Units
- Create and manage user accounts
- Create and manage security groups
- Configure group membership
- Join a Windows client to the domain
- Test domain authentication
- Use PowerShell to manage Active Directory
- Configure basic Group Policy
- Troubleshoot common Active Directory issues
- Document the completed environment using GitHub

---

## Technologies

- Microsoft Azure
- Windows Server
- Windows Client
- Active Directory Domain Services
- DNS
- PowerShell
- Group Policy
- Azure Virtual Network
- GitHub

---

## Lab Environment

| Component | Configuration |
|---|---|
| Cloud Platform | Microsoft Azure |
| Domain Controller | DC01 |
| Client Computer | CLIENT01 |
| Domain | adlab.test |
| Directory Service | Active Directory Domain Services |
| DNS | Windows DNS |
| Automation | PowerShell |
| Network | Azure Virtual Network |

---

## Active Directory Structure

The planned Active Directory structure is:

```text
adlab.test
|
+-- Users
|
+-- Groups
|
+-- Computers
|
+-- Servers
