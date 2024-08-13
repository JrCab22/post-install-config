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
   - Go to Agents --> Departments from admin panel
   - We will be adding a system administrators department
     
  ![image](https://github.com/user-attachments/assets/a5eb3aed-c2f6-42c5-b2f6-2bebce81f562)

3) Configure teams:
   - Admin Panel -> Agents -> Teams
   - We will create these 2 teams: Level I Support and Level II Support
     
![image](https://github.com/user-attachments/assets/bccb3fbe-badb-411e-b471-4ba5cb30893b)

4) Allow anyone to create tickets
   - Admin Panel -> Settings -> Users
   - Registration Required: Require registration and login to create tickets 
     
![image](https://github.com/user-attachments/assets/600efc24-71ef-488c-91d0-978232822801)


5) Create new agents or help desk staff accounts
  - Admin Panel -> Agents -> Add New Agent
  - We will be adding 2 new agents to the team: Winston and Isabella
  - Assign them  a username and password for them to login. (Uncheck the password reset and password email boxes)
  - Set their access to limited and assign them to the Support team

![image](https://github.com/user-attachments/assets/ff43e665-9b01-4662-84c8-2de415a248ce)

![image](https://github.com/user-attachments/assets/8164c793-d614-49b6-83cb-32270c39b0e9)


6) Configure Users (customers)
   - Agent Panel -> Users -> Add New
   - Create 2 new user accounts:  Karen and Jeff


7) Configure SLA
   - Admin Panel -> Manage -> SLA
   - The following will be defined under the SLA: **Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours)**

8) Configure Help Topics
   - Admin Panel -> Manage -> Help Topics
   - The following will be defined under Help topics: **Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset**


