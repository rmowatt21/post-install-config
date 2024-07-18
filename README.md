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
<img width="756" alt="os-ticket-agents" src="https://github.com/user-attachments/assets/05ffe15a-cf9d-445f-a3aa-506d002de038">

When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.
<p>

<img width="714" alt="os-ticket-user1" src="https://github.com/user-attachments/assets/e24f31e1-28d8-4958-b00a-11ec24e6551f">

</p>
<p>
Users are the ticket owners of the tickets in the help desk. When a ticket is created in the help desk, the user is associated with their email address in the User Directory of the help desk. Users can be added or deleted from the User Directory of the help desk at any time. You can add users to the User Directory of the Agent Panel of the help desk either individually or by importing them by uploading a CSV file.
</p>
<br />

<img width="726" alt="os-ticket-SLA" src="https://github.com/user-attachments/assets/fa013a36-8e0f-45f4-a82b-16ed6dfac304">

SLA Plans or Service Level Agreements, are unlimited in osTicket. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed. SLA Plans can be created by going to the Admin Panel > Manage > SLA Plans. Click on the top right of the table to “Add New SLA Plan.”
