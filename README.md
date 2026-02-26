<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
This tutorial demonstrates the post configuration setup of the osTicket system .
<br />

<p>
Okay wonderful! We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post installation setup. first we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should like something like this. As you can see we have successfully created the "Supreme Admin" role.
</p>

<p>
<img width="1048" height="463" alt="68747470733a2f2f692e696d6775722e636f6d2f584874657164742e706e67" src="https://github.com/user-attachments/assets/5636fe3e-c957-4acc-a23a-e7999813b817" />
<p>
</p>
<br />

Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab.

<p>
<img width="1053" height="854" alt="image" src="https://github.com/user-attachments/assets/5a1df6b6-a6f2-48d9-8da2-ab2accbd7941" />
</p>
<p>
After configuring a new department we will set up a new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create a Level II Support Team.
</p>
<br />

<p>
<img width="1051" height="745" alt="68747470733a2f2f692e696d6775722e636f6d2f63597a574244322e706e67" src="https://github.com/user-attachments/assets/7b9773b5-3197-4021-89a9-90492b6c2849" />
</p>
<p>
Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.
</p>
<br />

<p>
<img width="1014" height="706" alt="68747470733a2f2f692e696d6775722e636f6d2f483171324664682e706e67" src="https://github.com/user-attachments/assets/decf5479-373f-4fd1-856f-9633ebcd83f5" />
</p>
It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab.
<p>

<p>
<img width="981" height="939" alt="68747470733a2f2f692e696d6775722e636f6d2f3857544f5372652e706e67" src="https://github.com/user-attachments/assets/8a4bdf3e-0de6-4435-a157-ef45206d5c9b" />
</p>
<p>
After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new.
</p>
<br />

<p>
<img width="1029" height="432" alt="68747470733a2f2f692e696d6775722e636f6d2f784f70724139662e706e67" src="https://github.com/user-attachments/assets/bbbcdf37-d0fe-4e04-8c51-bd3f7f306219" />

</p>
<p>
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period.
</p>
<br />

<p>
<img width="1000" height="695" alt="68747470733a2f2f692e696d6775722e636f6d2f4c706a43614c642e706e67" src="https://github.com/user-attachments/assets/442157ee-a9ae-437a-904a-9590640facd0" />
</p>
<p>
Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking.
</p>
<br />

<p>
<img width="999" height="665" alt="68747470733a2f2f692e696d6775722e636f6d2f6b4237727473322e706e67" src="https://github.com/user-attachments/assets/a07ea5a6-f395-4b0f-9be2-69974fe3b8ce" />
</p>
