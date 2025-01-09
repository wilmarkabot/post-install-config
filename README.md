<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: Post-Install Configuration Objectives Playlist ](https://www.youtube.com/playlist?list=PLRwChl0ROcE7yfqEbbmVsT3gcU5yXW7VP)

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
4th Objective is to make sure anyone can create tickets, 
to do that we need to go to Admin Panel then Settings then UNCHECK unregistered users can Create tickets)
</p>
<p>
<img src="https://i.imgur.com/Ad0kiXS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
This is now our fifth Objective and on this Objective we will need to Create 2 Agents.
Agents manage tickets within their departments, ensuring efficient task allocation. 
As helpdesk members, they resolve customer issues, provide support, 
and maintain seamless communication to enhance service quality.
</p>
<p>
<img src="https://i.imgur.com/kVQHPyt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
After We Successfuly Created our Agents we will now create a USER.
to do that just go to this time in the Agent Panel --> Users --> Add New.
USERS submit tickets to report issues or request support, provide detailed information, 
track ticket status, and respond to agent inquiries. 
They play a vital role in initiating communication and ensuring smooth resolution of their concerns.
</p>
<p>
<img src="https://i.imgur.com/b2jijGr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
Our 2nd to the Last Objective is to Create SLA's (Service Level Aggrement)
Its basically like how much time you have to resove or do some specific task weather its responding
to a ticket or completing a ticket. We Created 3 SLA's Sev-A, Sev B, Sev C. <br />
Sev-A SLA we need to resolve it in just 1 hour and it is the most Critical Ticket to Solve so we much take action of this SLA as soon as Posible. <br />
Sev-B SLA is Critical but not Priority task <br />
Sev-C SLA is Common Problems encounter in workplace and its a low priority task.
</p>
<p>
<img src="https://i.imgur.com/OwIYj0n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
This is our Last Objective and this time we will Create Help Topics.
to do that go to Admin Panel -> Manage -> Help Topics  <br />
Help Topics is a ticket organization by categorizing user inquiries based on predefined subjects, 
such as "Bussness Critical Outage" or "Personal Computer Issues" 
They guide users during ticket submission, ensuring proper routing to the right department or agent, 
enhancing efficiency and providing faster, more accurate issue resolution.
</p>
<p>
<img src="https://i.imgur.com/ssKyaDN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
