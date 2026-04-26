<p align="center">
<img width="598" height="244" alt="image" src="https://github.com/user-attachments/assets/5c8d616f-b45f-42d8-b3fc-8e0e158505ee" />

</p>

<h1>osTicket – Post-Setup Settings</h1>
In this lab, I outline the essential configuration steps required to make osTicket operate effectively as a ticketing system.
<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> 


<h2>Setup Steps</h2>

<p>
<img width="1786" height="881" alt="image" src="https://github.com/user-attachments/assets/efc2992b-0d52-4ad4-ae0f-2648e5e57eb5" />

<img width="1298" height="682" alt="image" src="https://github.com/user-attachments/assets/03dba62e-2026-408d-8886-a34676970f7e" />

</p>
<p>
After installing osTicket, the next step is to configure it so it can function as a ticketing system. Keep in mind that you’ll be switching between the Admin and Agent panels, since each one contains different settings. You can tell which panel you’re currently in by checking the top right corner of the screen if it says “Agent Panel,” you’re in the Admin panel, and if it says “Admin Panel,” you’re in the Agent panel.

To begin, create a new role called Supreme Admin. For this exercise, the role should be given full permissions across the system. To do this, go to the Admin panel, navigate to the Agents section, select Roles, and then create the new role there.
</p>
<br />

<p>
<img width="3470" height="1916" alt="image" src="https://github.com/user-attachments/assets/300d4bf8-ac4a-417f-bdd0-c1ebe3b9643c" />

</p>
<p>
After that, set up a new department specifically for System Administrators. Go to the Admin panel, navigate to the Agents section, and select Departments to add the new department in osTicket.</p>
<br />

<p>
<img width="1301" height="713" alt="image" src="https://github.com/user-attachments/assets/c9978a1b-d118-4625-bf77-8ec9aa56954e" />

</p>
<p>
A new Level II Support Team should be set up to complement the existing Level I Support Team in osTicket. To do this, go to the Admin panel, navigate to the Agents section, select Teams, and create any additional teams as needed.
</p>
<br />

<p>
<img width="3498" height="1866" alt="image" src="https://github.com/user-attachments/assets/ad323a9a-ebf9-4909-819a-47f3dbd2528a" />

<img width="1295" height="714" alt="image" src="https://github.com/user-attachments/assets/a59127e0-4303-4392-b217-185445c3a36b" />

</p>
<p>
New agents need to be set up so they can handle tickets from the queue. To do this, go to the Admin panel and navigate to the Agents section. Select “Add New Agent,” then enter the login details for each person. In this example, accounts are created for Jane and John Doe.
</p>
<br />

<p>
<img width="1725" height="912" alt="image" src="https://github.com/user-attachments/assets/c25394c2-69b1-4474-bd31-52d612536602" />

</p>
<p>
New users need to be set up so they can submit tickets, which agents will then receive and prioritize. To add users, go to the Agents panel, open the Users section, and select “Add User.” From there, enter the required account details for each person. In this example, accounts have been created for Karen and Ken.
</p>
<br />

<p>
<img width="1281" height="701" alt="image" src="https://github.com/user-attachments/assets/de3d9588-78b3-49fc-96dd-edeb432af9f7" />
 

</p>
<p>
Service Level Agreements (SLAs) will have to be made in order to categorize tickets according to their level of impact. To make new SLAs, enter the Admin panel and open the Manage menu. Click on SLA and create any needed SLAs. In this case, SEV-A, B, and C have been created to categorize tickets that need to be resolved within 1 hour, 4 hours, and 8 hours respectively.
</p>
<br />

<p>
<img src="https://i.imgur.com/v3zTkfy.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
Finally, Help Topics need to be created to help users select an appropriate category that describes their problem so that Agents get an idea of what problem is described in the ticket. To make a new Help Topic, enter the Admin panel and open the Manage menu. Click on Help Topics and click on Add New Help Topic. In this case, I have added the following in order to use later for when I create new tickets to resolve: Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request.
</p>
<br />

<h2>osTicket Configurations are Complete </h2>

Now that the configurations have been set in place, I can now utilize osTicket as a proper ticketing system. I can create tickets and be able to traige them as if I were in a real environment.
