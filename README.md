<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
This tutorial demonstrates the post configuration setup of the osTicket system .
<br />

Okay wonderful! We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post installation setup. first we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should like something like this. As you can see we have successfully created the "Supreme Admin" role.

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
<img width="495" height="387" alt="image" src="https://github.com/user-attachments/assets/ad52be8f-377c-49d5-af68-f176b0cb5790" />
</p>
Once you have installed Web Installer Platform open it. From inside the application you are going to install MySQL 5.5 Afterwards install x86 version of PHP up until 7.3. There are some failed files such as C++ redistributable package as well as PHP 7.3.8 and PHP Manager for IIS those files can be found with the install link.
<p>

<p>
<img width="890" height="608" alt="image" src="https://github.com/user-attachments/assets/6a38edf5-2ef7-4313-82dc-b5f8098e1742" />
</p>
<p>
Next download osTicket. Then extract and copy the "upload" folder into c:\inetpub\wwwroot. Afterwards rename the folder to osTicket
</p>
<br />

<p>
<img width="1150" height="660" alt="image" src="https://github.com/user-attachments/assets/609cdeb5-8ebf-490a-9918-8d287791b52f" />
</p>
<p>
Open IIS Manager and restart the server. Once inside IIS manager go to Sites->Default->osTicket on the right, click "Browse*.80" from there your default browser should open osTicket webserver.
</p>
<br />

<p>
<img width="1425" height="752" alt="image" src="https://github.com/user-attachments/assets/b8bb4327-bd14-4520-b76d-3055ced398f3" />
</p>
<p>
Go back into IIS manager and enable some extensions. To do this you have to go to Sites->Default->osTicket Then double click on PHP manager. Click on "Disable or enable an extension" Enable "php_intl.dll" & "php_opcache.dll" then refresh the osTicket webserver and obsereve the changes "Intl Extension" should now be enabled.
</p>
<br />

<p>
<img width="1424" height="753" alt="image" src="https://github.com/user-attachments/assets/494afc29-ad65-42d4-b3d7-cd308a7a9591" />
</p>
<p>
Go back into c:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php rename the file to c:\inetpub\wwwroot\osTicket\include\ost-config.php Assign permissions to ost-config.php Disable inheritance->Removeall New Permissions->Everyone->all
</p>
<br />

<p>
<img width="1470" height="697" alt="image" src="https://github.com/user-attachments/assets/e65d0099-294b-47c3-9095-0d00b72b314d" />
</p>
<p>
Afterwards continue setting up osTicket in the browser (click continue) then you will name the Helpdesk to your liking. Select a default email that will receive emails from customers who submit tickets.
</p>
<br />

<p>
<img width="889" height="950" alt="image" src="https://github.com/user-attachments/assets/f59bec5d-7b9c-4df9-8032-dd4f3f00981f" />
</p>
<p>
Continue Setting up osticket in the browser MySQL Database: osTicket MySQL Username: root MySQL Password: Password1 Click “Install Now!” Congratulations, hopefully it is installed with no errors! Clean up Delete: C:\inetpub\wwwroot\osTicket\setup Set Permissions to “Read” only: C:\inetpub\wwwroot\osTicket\include\ost-config.php Login to the osTicket Admin Panel (http://localhost/osTicket/scp/login.php)
</p>
<br />
