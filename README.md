<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration</h1>

This tutorial outlines the creation of Agents, Departments and SLA's in the help desk ticketing system osTicket. 

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Windows Virtual Machine
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
<p>

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (Workers)
- Configure SLA
- Configure Help Topics

- <h2>Configuration of Roles</h2>

A) Admin Panel > Agents > Roles

B) Superior Admin > Create Role

<img src="https://i.imgur.com/eHgF4RJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Create the role Superior Admin, and give it the accessbility that a Superior Admin should have FULL CONTROL.

<img src="https://i.imgur.com/95zIXPV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- <h2>Configure Departments</h2>

A) Admin Panel > Agents > Departments

B) System Administrators > Create Department

<img src="https://i.imgur.com/vnzabEi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


- <h2>Configure Teams</h2>

A) Admin Panel > Agents > Teams

B) Level I Support

C) Level II Support > Edit to your liking > Create Teams

<img src="https://i.imgur.com/BadK5BJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


- <h2>Allow anyone to create tickets</h2>

A) Admin Panel > Settings > User Settings

B) Click Registration Required (for demonstration purposes I will unclick it) > Save Changes

<img src="https://i.imgur.com/pbyL9lP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


- <h2>Configure Agents (Workers)</h2>

A) Admin Panel > Agents > Add New Agent

- Kayden
- Benjamin

<img src="https://i.imgur.com/aZ2KGEP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


Edit Access, Permissions, and Teams as needed for the designated agent


- <h2>Configure Users (Customers)</h2>

A) Agent Panel > User > Add New User

- Sammy
- Rudy

<img src="https://i.imgur.com/Kl5YNVe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


- <h2>Configure SLA</h2>

A) Admin Panel > Manage > SLA > Add New SLA Plan

<img src="https://i.imgur.com/TmBYI6t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

B) Sev-A (1 hour, 24/7)
 
   Sev-B (4 hour, 24/7)
  
   Sev-C (1 hour, 24/7)
  
<img src="https://i.imgur.com/99kwMgq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  
Once you're finished entering your SLA Plan's, it should look like this
  
  
<img src="https://i.imgur.com/ANtmyxe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  
- <h2>Configure Help Topics</h2>

A) Admin Panel > Manage > Help Topics

B) Add New Help Topics
  
  - Business Critcal Outage
  
  - Personal Computer Issues
  
  - Equipment Request
  
  - Password Reset
  
  When complete, it should look like this

<img src="https://i.imgur.com/PUOEmuY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
On the next tutorial, we will create tickets & dislpay the <a href="https://github.com/JuryM87/osTicket-Lifestyle.git"></h1>Ticket Lifecycle
  
  
