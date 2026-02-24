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

- Windows (Windows 11 Pro)

<h2>List of Prerequisites</h2>

- Intake
- Azure Virtual Machine
- osTicket Installation files
- Heidi SQL

<h2>Installation Steps</h2>

Welcome to my first in-depth IT tutorial! To begin we will have to create a Virtual machine using the Microsoft Azure portal(portal.azure.com). We will be using a VM(virtual machine) which is a remote computer. We are using a VM in order to protect our physical machine just in case something malfunctions, and also have a clean slate computer to continually replicate the lab on. Create a resource group and title it "osTicket". Afterwards create a VM with 2-4 CPUs. In this example I will be using 4 CPUs.

<p>
<img width="1728" height="1080" alt="Screenshot 2026-01-25 at 5 22 26 AM" src="https://github.com/user-attachments/assets/8a2c348c-4eb5-43b1-a992-46db9e5b332c" />
<img width="1728" height="1080" alt="Screenshot 2026-01-25 at 5 55 53 AM" src="https://github.com/user-attachments/assets/f7fb6ba0-0727-4c32-9652-52a55f9ad58b" />
<p>
Log into osTicket and open "Tickets" Panel. Observe ticket(s). Consider client issue, priority level, and SLA.
</p>
<br />

<p>
<img width="1728" height="1080" alt="Screenshot 2026-01-25 at 5 36 00 AM" src="https://github.com/user-attachments/assets/da4a61ea-a27d-4d99-9908-608a3cf4672a" />
</p>
<p>
Communicate to client that the issue will be addressed and they will be kept up to date concerning progress.
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
