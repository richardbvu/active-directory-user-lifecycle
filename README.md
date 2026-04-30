# Active Directory User Lifecycle Lab

## Overview
This project demonstrates the build, validation, and troubleshooting of an on-prem Active Directory environment, including domain controller configuration, workstation domain join, and user lifecycle management.

It focuses on core IT support tasks such as user provisioning, group-based access control, authentication validation, and Group Policy behavior, with emphasis on diagnosing and resolving common issues in a domain environment.

The lab reflects real-world support scenarios, including user login issues, domain connectivity problems, Group Policy application failures, and Remote Desktop access troubleshooting. It demonstrates the ability to manage user accounts, validate system configuration, and identify the root cause of issues affecting users and workstations.

All configurations and findings were validated through Active Directory tools, system-level checks, and controlled testing using a domain-joined workstation (W11VM). The project follows an evidence-first approach, with documented build validation, troubleshooting scenarios, tickets, runbooks, and PowerShell-based verification aligned to real IT support workflows.

## Work Performed
- Created and managed domain user accounts, including provisioning, password resets, and account state changes  
- Assigned access using security groups and validated permission behavior across user sessions  
- Joined a Windows workstation (W11VM) to the domain and verified domain connectivity and authentication  
- Validated Group Policy application and distinguished between user and computer configuration behavior  
- Performed troubleshooting for login issues, domain trust problems, and authentication failures  
- Investigated DNS and network-related issues affecting domain communication  
- Verified Remote Desktop access and resolved connectivity and permission issues  

## Start Here
Recommended files and folders to review first:

- [04-Ticket-Pack](./04-Ticket-Pack/)
- [03-Runbook](./03-Runbook/)
- [06-Resume-and-Interview](./06-Resume-and-Interview/)

## Skills Demonstrated
- Active Directory administration and user lifecycle management  
- Workstation domain join and authentication validation  
- Group Policy verification and troubleshooting  
- DNS troubleshooting in a domain environment  
- Remote Desktop access troubleshooting  
- Domain user authentication and login issue resolution  
- Security group-based access control  
- Structured troubleshooting methodology and documentation  

## Project Structure
- [00-Project-Summary](./00-Project-Summary/) — overview and navigation  
- [01-Build-Evidence](./01-Build-Evidence/) — healthy-state build validation  
- [02-Troubleshooting-Evidence](./02-Troubleshooting-Evidence/) — raw notes, screenshots, and observations  
- [03-Runbook](./03-Runbook/) — reusable troubleshooting procedures (only where applicable)  
- [04-Ticket-Pack](./04-Ticket-Pack/) — polished ticket write-ups
- [05-PowerShell](./05-PowerShell/) — PowerShell command-based validation used for administration, verification, and troubleshooting
- [06-Resume-and-Interview](./06-Resume-and-Interview/) — project packaging for job search  