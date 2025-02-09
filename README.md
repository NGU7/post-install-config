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

- Creating Departments, Roles, and teams to simulate a work environment for agents
- Creating Agents/Workers + End-Users for the Helpdesk in osTicket
- Establishing SLAs (Service License Agreements) and their priority For tickets
- Create Help Topics for End-Users to allow them to more accurately specify their Issues

<h2>Configuration Steps</h2>

<p>
<img width="1440" alt="Screen Shot 2025-01-23 at 3 02 57 PM" src="https://github.com/user-attachments/assets/6d5cd593-8717-479c-bf6c-c3870af0be7b" />
</p>
<p>
After setting up departments "Sys Admins", "Online Banking", and "Tech Support", we then created help topics to help specify reported problems brought to the help desk, allowing agents to work and sort tickets properly.
</p>
<br />

<p>
<img width="1440" alt="users" src="https://github.com/user-attachments/assets/01b0acb8-2cb2-4236-b8cc-00594922d9d8" />
</p>
<p>
These are the three agents created for this ticket system simulation. I later gave them roles in a differing hierarchy allowing one to have a supervising position over the other, this allowed one to delegate tickets to different departments. This process helped me check to see whether different departments had access to tickets that weren't meant for them, troubleshooting any issues in the process.
</p>
<br />

<p>
<img width="1440" alt="SLA's" src="https://github.com/user-attachments/assets/d8bc47ca-cee4-4977-b254-b55f3177aa1a" />
</p>
<p>
  These are Service Level Agreements (SLA), which allow my agents to properly categorize problems based on the scope before sending them to the next department.  
</p>
<br />
