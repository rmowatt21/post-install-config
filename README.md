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

- Configure Roles
- Configure Departments/Teams 
- Configure Agents/Users 
- Configure SLA
- Help Topics 

<h2>Configuration Steps</h2>

<p>
<img width="784" alt="image" src="https://github.com/user-attachments/assets/4917d5f7-adf8-43f2-ad3c-698bb471c622">
</p>
<p>
After we install the ticketing system, we are able to configure the Roles. Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments. Role Permissions for Tickets include:

Assign: Ability to assign tickets to agents or teams
Close: Ability to close tickets. 
Create: Ability to open tickets on behalf of users. 
Delete: Ability to delete tickets. Edit: Ability to edit tickets

</p>
<br />

<p>
<img width="783" alt="Os-ticket2" src="https://github.com/user-attachments/assets/17c2e824-ed94-4934-9bf4-5d4087cb7863">

In the department settings. This is where the admin can assign tickets to different agents or schedule an event with a a manager. We can also set up an SLA Service Level Agreement for tickets routed to this Department. This the expected amount of time (in hours) that a ticket is expected to be closed once opened. If the ticket is not closed in the allotted amount of time, it will then be Overdue.
</p>
<p>

<img width="759" alt="OS-ticket3" src="https://github.com/user-attachments/assets/1305590a-26cf-422b-97d2-b98be8e1a0a5">

Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.
Having Agents from different Departments assigned to a Team will supersede the parameters of the Agents’ Department rules.

</p>
<br />
<img width="753" alt="os-ticket-teams" src="https://github.com/user-attachments/assets/2a560cd7-abbd-415f-b224-8820f15576bb">

adding an additional team member so we can set up different task for different members
<p>

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
