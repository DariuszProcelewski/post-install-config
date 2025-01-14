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

It’s essential to switch between the Admin and Agent panels, as each panel offers distinct configuration options. You can determine which panel you’re using by checking the top-right corner of the osTicket screen. If it displays "Agent Panel," you are currently in the Admin panel, and the reverse is true.

The first step is to create a role named "Supreme Admin." For the purposes of this lab, this role will be granted all available permissions. To create it, open the Admin panel, go to the Agents menu, select Roles, and create the new role from there.
![Screenshot 2025-01-14 055440](https://github.com/user-attachments/assets/7eb8b66f-a36c-45b9-ac0e-e86e542a1783)
![Screenshot 2025-01-14 055732](https://github.com/user-attachments/assets/d5b439aa-2666-4c31-8835-2353eee86be6)
![Screenshot 2025-01-14 060336](https://github.com/user-attachments/assets/2d9260db-cded-416a-a7c7-899516312e59)

Then go to Permissions -> Tickets and tick all boxes.
![Screenshot 2025-01-14 060429](https://github.com/user-attachments/assets/fac332d0-af37-496e-a533-f198de6bb037)

Next Permissions -> Tasks and again tick all boxes and Press "Add Role".
![Screenshot 2025-01-14 060708](https://github.com/user-attachments/assets/43c0cd52-df90-48c7-bb01-98956394b358)



