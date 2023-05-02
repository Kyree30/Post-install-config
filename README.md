# Post-install-config
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

-Do the after-installation configuration of osTicket

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/e1UNFHS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/lpDnu8g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><b>
(Configure Roles)
Admin Panel -> Agents -> Roles
  Supreme Admin</b>
</p>
<br />

<p>
<img src="https://i.imgur.com/lIADqHS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/6Rc5MyG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><b>
(Configure Departments)
Admin Panel -> Agents -> Departments
System Administrators
  </b>
</p>
<br />

<p>
<img src="https://i.imgur.com/EOj7Ct5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/dcpP1EV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><b>
(Configure Teams)
Admin Panel -> Agents -> Teams
Level I Support
  Level II Support</b>
</p>
<br />

<br>
<p>
<img src="https://i.imgur.com/AU4IJFr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><b>
(Allow anyone to create tickets)
Admin Panel -> Settings -> User Settings
  Registration Required: Require registration and login to create tickets</b> 
</p>
<br />

<p>
<img src="https://i.imgur.com/QYP7Dcd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><b>
Configure Agents (workers)
  Admin Panel -> Agents -> Add New</b>
Jane
John

</p>
<br />

<p>
<img src="https://i.imgur.com/SjpmlUw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/NrBFZTD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><b>
Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
  Ken</b>
</p>
<br />

<p>
<img src="https://i.imgur.com/At9ymSy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/a4fRlbt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><b>
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
</p></b>
<br />

<p>
<img src="https://i.imgur.com/Nwd5zGz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/rIM4wvQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p><b>
Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
  Password Reset</b>
</p>
<br />

