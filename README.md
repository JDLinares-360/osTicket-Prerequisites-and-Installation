<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket-Prerequisites-and-Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10

<h2>List of Prerequisites</h2>

- Azure Virtual Machine
- osTicket Installation files
- Heidi SQL

<h2>Installation Steps</h2>

Welcome to my first in-depth IT tutorial! To begin we will have to create a Virtual machine using the Microsoft Azure portal(portal.azure.com). We will be using a VM(virtual machine) which is a remote computer. We are using a VM in order to protect our physical machine just in case something malfunctions, and also have a clean slate computer to continually replicate the lab on. Create a resource group and title it "osTicket". Afterwards create a VM with 2-4 CPUs. In this example I will be using 4 CPUs.\.

<p>
<img width="1919" height="968" alt="68747470733a2f2f692e696d6775722e636f6d2f4f506149476f4e2e706e67" src="https://github.com/user-attachments/assets/acabc84e-408e-4e99-b2f6-5a180574f955" />
<p>
Log into osTicket and open "Tickets" Panel. Observe ticket(s). Consider client issue, priority level, and SLA.
</p>
<br />

Next simply connect to your newly created VM using RDP using the public IPv4 address. If you are a Mac user you will have to download Microsoft Remote Desktop(RDP).

<p>
<img width="406" height="253" alt="image" src="https://github.com/user-attachments/assets/24277a2c-282a-409e-a0d3-1bb73fcc2469" />
</p>
<p>
Alright, now that you are connected to your VM you will have to enable IIS. Simply access the control panel then select uninstall a program. Off to the left select "Turn windows features on or off". A list will appear then you will enable Internet Information Services.
</p>
<br />

<p>
<img width="1728" height="1080" alt="Screenshot 2026-01-25 at 5 52 45 AM" src="https://github.com/user-attachments/assets/d209691f-ec66-4fdd-b4a6-7d57309f95bd" />
</p>
<p>
After troubleshooting/working the ticket with the client, post internal notes with details concerning actions taken to resolve the issue.
</p>
<br />

<p>
<img width="1728" height="1080" alt="Screenshot 2026-01-25 at 6 08 06 AM" src="https://github.com/user-attachments/assets/131d3800-eedf-4aac-a7c4-b16196fc605a" />
<img width="1728" height="1080" alt="Screenshot 2026-01-25 at 6 08 44 AM" src="https://github.com/user-attachments/assets/a0c5880f-d092-4e58-8f67-68062640efc4" />
</p>
<p>
Depending on how osTicket is configured:

Option A: Change Department
<br />
<br />
Example:
<br />
  From: IT Helpdesk / Tier 1
<br />
  To: Desktop Support / Tier 2

Option B: Assign to Tier 2 Agent or Team
<br />
<br />
Example:
<br />
Assign to:
<br />
-Tier 2 Queue
<br />
-Desktop Engineering
<br />
-Network Team
<br />
-Systems Team
  </p>
<br />
