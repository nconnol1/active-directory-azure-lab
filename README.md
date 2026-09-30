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
