<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>

1. Configure Roles

It’s essential to switch between the Admin and Agent panels, as each panel offers distinct configuration options. You can determine which panel you’re using by checking the top-right corner of the osTicket screen. If it displays "Agent Panel," you are currently in the Admin panel, and the reverse is true.

The first step is to create a role named "Supreme Admin." For the purposes of this lab, this role will be granted all available permissions. To create it, open the Admin panel, go to the Agents menu, select Roles, and create the new role from there.

![Screenshot 2025-01-14 055440](https://github.com/user-attachments/assets/7eb8b66f-a36c-45b9-ac0e-e86e542a1783)
![Screenshot 2025-01-14 055732](https://github.com/user-attachments/assets/d5b439aa-2666-4c31-8835-2353eee86be6)
![Screenshot 2025-01-14 060336](https://github.com/user-attachments/assets/2d9260db-cded-416a-a7c7-899516312e59)

Then go to Permissions -> Tickets and tick all boxes.

![Screenshot 2025-01-14 060429](https://github.com/user-attachments/assets/fac332d0-af37-496e-a533-f198de6bb037)

Next Permissions -> Tasks and again tick all boxes and Press "Add Role".

![Screenshot 2025-01-14 060708](https://github.com/user-attachments/assets/43c0cd52-df90-48c7-bb01-98956394b358)

2. Configuring Departments (Ticket Visibility and Team Roles: Help Desk, SysAdmins, Networking)

Navigate to the Admin Panel > Agents > Departments to configure department-specific settings and ticket visibility.

- SysAdmins: Configuration focuses on managing system-level tickets and administrative tasks.
  
- Help Desk: Primarily handles user support and general inquiries.
  
- Networking: Manages network-related tickets and infrastructure issues.
  
This structure ensures tickets are routed to the appropriate team for efficient resolution.

Click "Add New Department" and create "System Admins" Department: 

![Screenshot 2025-01-14 061804](https://github.com/user-attachments/assets/0f35dd1d-c6b8-439d-a58f-c5bfa8eb2eba)
![Screenshot 2025-01-14 062255](https://github.com/user-attachments/assets/5943c7fa-f220-4e02-b1dd-d3a9b51a7699)

3. Configuring Teams (Cross-Department Collaboration)
Navigate to the Admin Panel > Agents > Teams to set up teams by grouping agents from different departments.

Online Banking: A team created to handle tasks and tickets related to online banking services, ensuring specialized support across departments.

This setup facilitates collaboration and ensures agents with the right expertise are assigned to specific tasks.

![Screenshot 2025-01-14 062854](https://github.com/user-attachments/assets/4c421c2a-7415-4ef9-b926-fed76e9cb795)
![Screenshot 2025-01-14 063021](https://github.com/user-attachments/assets/977fb09f-4d9d-4269-a7c9-04a3a2bf5810)

4. Configuring Ticket Creation Permissions
   
To manage who can create tickets, navigate to Admin Panel > Settings > User Settings:

- Allow Anyone to Create Tickets: Uncheck the option for "Unregistered users can create tickets" to restrict ticket creation to registered users only.
  
- Registration Required: Enable this setting to require users to register and log in before submitting tickets.
  
This configuration ensures controlled access to the ticketing system and enhances security.

![Screenshot 2025-01-14 063407](https://github.com/user-attachments/assets/f1942e08-d25a-4678-a3b6-4569a666ec76)

5. Configuring Agents (Team Members)

To add and assign agents to specific departments, navigate to Admin Panel > Agents > Add New:

- Jane: Assigned to the System Admins department, focusing on system administration tasks.
  
- John: Assigned to the Support department, specializing in user support and general inquiries.
  
This setup ensures that each agent is appropriately aligned with their responsibilities.

![Screenshot 2025-01-14 063746](https://github.com/user-attachments/assets/16c95745-1203-4e84-9e31-6516442688c5)
![image](https://github.com/user-attachments/assets/e3cd131e-7e85-40cd-88b0-09341c23791d)
![Screenshot 2025-01-14 064159](https://github.com/user-attachments/assets/18913131-7e75-4ecd-9d39-a4df1e623fe9)
![Screenshot 2025-01-14 064259](https://github.com/user-attachments/assets/c94c2167-f1a9-42d0-a8a6-801fb2ab7777)



