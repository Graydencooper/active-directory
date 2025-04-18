## Overview
In this document, I review the steps to set up an active directory in a virtual Windows environment and setup organizational units and users.

## Tools Used

- Azure Portal
- Windows Server 2019
- Server Manager
- Active Directory Users and Computers

## Key Steps

1. Created a Windows Server VM in Azure
<img width="800" alt="Screenshot of created server VM" src="https://github.com/user-attachments/assets/3b8b941c-c02c-4754-8995-7a95cb48d1bc" />

2. Logged into server via RDP
3. Installed the AD DS role using Server Manager
<img width="800" alt="Screenshot of selecting server roles" src="https://github.com/user-attachments/assets/7dced5f6-b152-4e9c-afe3-2e6d2bcbf76d" />
<img width="800" alt="Screenshot of installing AD roles" src="https://github.com/user-attachments/assets/86eb4c70-a1a9-4bdf-8ef7-bb6d80afd43e" />

4. Promoted the server to a domain controller
<img width="800" alt="Screenshot of creating domain " src="https://github.com/user-attachments/assets/2a885745-5108-4e3e-8811-d85f237f84b4" />

<img width="800" alt="Screenshot of AD checking system requirements " src="https://github.com/user-attachments/assets/b0e53436-2784-415a-bb2a-656c0cbb6ad1" />
- Checked system prerequisites 

5. Created a organizational unit in Active Directory
<img width="800" alt="Screenshot creating OU" src="https://github.com/user-attachments/assets/f925dd3c-6882-44c4-ab08-bda81d592b9c" />
- Opened Active Directory Users and Computers
- Created Organizatinal unit "_ADMINS"
  
7. Created admin user
<img width="800" alt="Screenshot of creating user" src="https://github.com/user-attachments/assets/f48cdab9-4abf-4d02-8698-550c534c0597" />

<img width="800" alt="Screenshot of new user properties" src="https://github.com/user-attachments/assets/29b192e6-a741-419f-8903-7f7733fad966" />
<img width="800" alt="Screenshot of new user being added to domain admins group" src="https://github.com/user-attachments/assets/8c48d39e-4ab1-41f1-84d1-f6898c9bf3dd" />
- Set group memership
## What I Learned

- How to navigate and configure Windows Server
- The basics of Active Directory setup
- How to simulate a real IT support task in a virtual environment
