<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/@MarkwheelReach)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics (For when users create a ticket)

<h2>Configuration Steps</h2>

<p>
This is the Log.in Page for admin users
http://localhost/osTicket/scp/login.php
</p>
<p>
<img src="https://i.imgur.com/st8MZud.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
This is the landing page for End Users
http://localhost/osTicket
</p>
<p>
<img src="https://i.imgur.com/FjzYEor.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
So this is our 1st Objective to make a new role, and we already make a new one here, we add a new role name Supreme Admin.
To do that we log.in as admin user then go to Admin Panel in the upper right of the page then we select the Agent tab and then
Role and made a new Role.
</p>
<p>
<img src="https://i.imgur.com/mnPCZvC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
2nd Objective is to make a new Department.
to do that 1st we need to be at the admin panel, then select the Agent tab then Department.
then click on make a new department.
we named our new department as sysAdmins
</p>
<p>
<img src="https://i.imgur.com/ShM8C9k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
3rd Objective is to make a new Teams
to do that we need to be at the admin panel page then agents tab then Teams
click on the Create new Teams
We Named our Teams as Online Banking
</p>
<p>
<img src="https://i.imgur.com/TSaCBSP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
