<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Microsoft Azure Free Account
- Understanding of Windows Ost
- Understanding of SLAs
- [Installation Files](https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6)

Now we can login in using our credentials and begin configuring roles, departments, and even setup SLA's.
![Screenshot 2023-11-03 113000](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/cf5218fa-47a3-4099-aa7b-44698382c9e1)

Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin
![Screenshot 2023-11-03 114445](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/04cc3e4a-00ac-4929-86a3-fb1065eed41b)
![Screenshot 2023-11-03 114520](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/8e68697d-6962-4f76-a687-da64690d3715)
Configure Departments
Admin Panel -> Agents -> Departments
System Administrators
![Screenshot 2023-11-03 114724](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/d7118393-dc40-45c1-a925-703e57e7654d)
Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support
![Screenshot 2023-11-03 114940](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/eeb06d79-2e03-468c-b71b-a1fda66f2234)
![Screenshot 2023-11-03 114946](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/e6c822de-21aa-4406-964e-33b7d1d0e9a5)
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets 
![Screenshot 2023-11-03 115114](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/fe410562-4a95-4323-8448-63cb076b7c04)
Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John
![Screenshot 2023-11-03 115405](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/b816bca1-2069-4181-a1a8-402d64f1c255)
![Screenshot 2023-11-03 115350](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/fdddb7c3-89e7-4a4c-899a-70411756d566)
Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
![Screenshot 2023-11-03 115655](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/324e13b1-3fa6-431a-9658-36f356fbd340)
![Screenshot 2023-11-03 115807](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/e19b61c7-ee11-4fb2-a6a1-3680be9a4b7b)
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour,24/7) 
![Screenshot 2023-11-03 120134](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/a138cd11-3c7c-4a0a-878b-90974a072570)
Sev-B (4 hours, 24/7)
![Screenshot 2023-11-03 120256](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/c20039f6-6a83-4a29-b21f-a731ba66aa61)
Sev-C (8 hours, business hours)
![Screenshot 2023-11-03 120345](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/1a2a290e-5fe0-4e9f-8ab3-1fef9f09f829)
Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
![Screenshot 2023-11-03 120630](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/b6f8fbcb-dc82-4e00-8441-fa9bf73cb5ff)
Personal Computer Issues
![Screenshot 2023-11-03 120706](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/03e17108-533e-4761-bbf2-2fd8070fa52d)
Equipment Request
![Screenshot 2023-11-03 120832](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/1777dc8d-9ee8-47e3-aeba-d52b334d8e95)
Password Reset
![Screenshot 2023-11-03 120857](https://github.com/jachinrupe/post-install-config-osticket/assets/149485790/4b5f8b34-b701-4261-a794-5051854ec05e)

There you have it for Post-installation for osTicket. Next lab we'll work on Ticket lifecycles with examples.
