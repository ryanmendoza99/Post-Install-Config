# Post-Install-Config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation][https://www.youtube.com](https://www.youtube.com/watch?v=J08-kJ3-3Ag)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure a Supreme Admin role
- Configure a System Administrators Department
- Configure Two Teams (Level II Support)
- Configure Agents and Users
- Cofigure SLA and Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure our SA role, we must first ensure we are on the admin login. Next we can continue by heading over to admin panel, clicking on the agents tab following roles. We will then add System Administrators and ensure that we give the role permission to do everything.  
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure our System Administrator Department, we follow the same path but click on departments. Leave everything as default and create department.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure teams, we follow the same pathway and however, click on teams. Add team and create a Level II Support team. Before continuing, go to settings-> user settings-> ensure the "Registration Required:Require registration and login to create tickets" box is not checked off
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure Agents, hover over admin panel-> agents-> add two new agents of your liking. Make sure you add them to a department/team. Next configure users, hit agent panel-> users -> add new users
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA, click on admin panel ->manage-SLA; create the following 
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
</p>
<br />
