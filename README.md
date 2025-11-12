# Windows Server Lab – AD, DHCP, DNS

## Overview
A virtualized lab environment built to simulate enterprise IT infrastructure...

## Technologies
- Windows Server 2022  
- PowerShell  
- Hyper-V Manager
- Virtual Machine 

## Steps
1. Create a windows server 2022 on Hyper-V Manager
3. Configured AD DS  
4. Added DHCP role...  
5. Configured DNS zone...  

## Screenshots
1. Add active directory and Group Policy Management on the server
<img width="1363" height="770" alt="image" src="https://github.com/user-attachments/assets/0c747025-5b8c-4779-93f5-decfb0d9e04d" />

2. Creating the domain and making the server the active directory domain controller
<img width="1364" height="730" alt="image" src="https://github.com/user-attachments/assets/5faff48e-d5c1-4acc-85ef-42b22136efd5" />

3. Domain creation proof
<img width="1366" height="767" alt="image" src="https://github.com/user-attachments/assets/7dcaf621-4a06-40f3-aef1-82dd97984b53" />

4. Create new Zone for DNS, a new zone is crucial for easier management, backup, and troubleshooting
<img width="1362" height="772" alt="image" src="https://github.com/user-attachments/assets/a7dcf909-49a9-4641-a058-a683f6d34f86" />

5. Add the DHCP
<img width="1358" height="766" alt="image" src="https://github.com/user-attachments/assets/ed5ca100-d30c-4ee6-b5fb-72ebfd8771a0" />

6. Creating a Scope for DHCP to put up to 151 clients
<img width="1362" height="765" alt="image" src="https://github.com/user-attachments/assets/72a86d90-d7b3-4804-9a48-c53cd7e32bca" />

7. 

## Outcome
Successfully created a functional test domain with centralized authentication, DHCP IP distribution, and DNS resolution.
