<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In this tutorial we will be learning how to utilize the administrator funcctions in osTicket.<br />


<h2>Video Demonstration</h2>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Learn how to open and close tickets.
- Creating an SLA as an administrator.
- Configure teams, departments, agents, and users (customers)
- Configure Help Topics such as Business Critical Outage
  

<h2>Configuration Steps</h2>

1) Configure roles in the admin panel.
   - Go to Agents --> Roles --> Add role from admin panel
   - In this exercise we will be adding a role known as "Supreme Admin" that has all permissions.
   - Check all permissions boxes
     
     ![image](https://github.com/user-attachments/assets/65b1c022-bae7-4f1c-a8b3-f81ccbea5bb4)

  ![image](https://github.com/user-attachments/assets/2166f89c-1333-497a-9bd7-48980af9266f)

2) Configure departments in admin panel.
   - Go to Agents --> Roles from admin panel
   - We will be adding a system administrators department
  
3) Configure teams:
   - Admin Panel -> Agents -> Teams
   - We will create these 2 teams: Level I Support and Level II Support

4) Allow anyone to create tickets
   - Admin Panel -> Settings -> User Settings
   - Registration Required: Require registration and login to create tickets 
   - Configure Agents (workers)

5) Create new agents or help desk staff accounts
  - Admin Panel -> Agents -> Add New
  - We will be adding 2 new agents to the team: Winston and Isabel

6) Configure Users (customers)
   - Agent Panel -> Users -> Add New
   - Create 2 new user accounts:  Karen and Jeff

7) Configure SLA
   - Admin Panel -> Manage -> SLA
   - The following will be defined under the SLA: **Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours)**

8) Configure Help Topics
   - Admin Panel -> Manage -> Help Topics
   - The following will be defined under Help topics: **Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset**


