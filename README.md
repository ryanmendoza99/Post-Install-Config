# Post-Install-Config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>
For a step-by-step demonstration, take a look at the video as it will be more useful. 

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
- Configure SLA and Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/XhmcfEu.png">
</p>
<p>
To configure our SA role, we must first ensure we are on the admin login. Next, we can continue by heading over to the admin panel, and clicking on the agent's tab following roles. We will then add Supreme Admin. and ensure that we give the role permission to do everything.  
</p>
<br />

<p>
<img src="https://imgur.com/kP8wigd.png">
</p>
<p>
To configure our System Administrator Department, we follow the same path but click on departments. Leave everything as default and create a department.
</p>
<br />

<p>
<img src="https://imgur.com/pQFmQsH.png">
</p>
<p>
To configure teams, we follow the same pathway and however, click on teams. Add a team and create a Level II Support team. Before continuing, go to settings-> user settings-> ensure the "Registration Required: Require registration and login to create tickets" box is not checked off
</p>
<br />

<p>
<img src="https://imgur.com/1cLxXNG.png">
<img src="https://imgur.com/sgrOm5R.png">
</p>
<p>
To configure Agents, hover over the admin panel-> agents-> add two new agents of your liking. Make sure you add them to a department/team. Next configure users, hit agent panel-> users -> add new users
</p>
<br />

<p>
<img src="https://imgur.com/xQss56i.png">

</p>
<p>
Configure SLA, click on admin panel ->manage-SLA; create the following 
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
</p>
<br />
