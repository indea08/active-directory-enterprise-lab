# Enterprise Active Directory Home Lab

## Overview

This project documents the design, deployment, configuration, and
administration of a simulated enterprise Microsoft Active Directory
environment.

The lab represents a fictional organization named Rosalie Technologies
and was created to gain hands-on experience with common Windows Systems
Administrator responsibilities.

## Technologies Used

- Windows Server 2022
- Windows 11
- Active Directory Domain Services
- DNS
- DHCP
- Group Policy
- PowerShell
- NTFS Permissions
- Windows File Sharing
- TCP/IP
- Virtualization

## Lab Objectives

- Deploy a Windows Server domain controller
- Configure Active Directory Domain Services
- Configure DNS and DHCP
- Create organizational units for multiple departments
- Create and manage users and security groups
- Join Windows clients to the domain
- Implement Group Policy
- Configure role-based file permissions
- Automate administrative tasks with PowerShell
- Troubleshoot common Active Directory and networking issues

## Environment

| System | Role | Operating System | IP Address |
|---|---|---|---|
| DC01 | Domain Controller / DNS / DHCP | Windows Server 2022 | 192.168.10.10 |
| FS01 | File Server | Windows Server 2022 | 192.168.10.20 |
| CLIENT01 | Domain Workstation | Windows 11 Pro | DHCP |

## Domain

corp.rosalietech.local
