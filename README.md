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

- MAC OS </b>
- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents 
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/nVRFh1E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log in to your osTicket administration panel as an administrator. Click on the "Admin Panel" tab located at the top right corner of the page. In the left sidebar, under the "Roles & Permissions" section, click on "Roles”. On the Roles page, you'll see a list of existing roles (e.g., Admin, Agent, Staff). To create a new role, click on the "Add New Role" button. Provide a name for the role and a brief description to help identify its purpose. After creating the role, you'll see a list of permissions that can be assigned to that role. Select the desired permissions for the role by checking the checkboxes next to each permission. You can assign as many or as few permissions as necessary based on the role's responsibilities. Once you have configured the permissions and access restrictions for the role, click the "Save" button to save the changes. After saving, you can assign the newly created role to users in osTicket. To do this, go to the "Agents" or "Staff" section (depending on the role type), select the user you want to assign the role to, and choose the role from the available options.
</p>
<br />

<p>
<img src="https://imgur.com/C3FwWCe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the left sidebar of the admin panel, navigate to the "Agents & Departments" section and click on "Departments”. On the Departments page, you'll see a list of existing departments if any have been set up previously. To create a new department, click the "Add New Department" button. Provide a name for the department, which should reflect the specific area or team it represents. Next, you can configure other settings for the department. Save your changes by clicking the "Save" button. Repeat the process to create additional departments as necessary.
</p>
<br />

<p>
<img src="https://imgur.com/4YgcGPs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the left sidebar of the admin panel, navigate to the "Agents & Departments" section and click on "Teams." On the Teams page, you'll see a list of existing teams if any have been set up previously. To create a new team, click the "Add New Team" button. Provide a name for the team, which should reflect the purpose or specialization of the group. For example, "Level 1 Support," "Billing Team," or "Product Development”. Next, you can assign agents to the team by selecting them from the available options. This associates the agents with the team and allows for effective collaboration and ticket assignment. Save your changes by clicking the "Save" button. Repeat the process to create additional teams as necessary.
</p>
<br />

<p>
<img src="https://imgur.com/r3J2hT9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the left sidebar of the admin panel, navigate to the "Agents & Departments" section and click on "Agents." On the Agents page, you'll see a list of existing agents if any have been set up previously. To create a new agent account, click the "Add New Agent" button. Provide the necessary information for the agent, such as their name, email address, and desired username and password for logging in to osTicket. Assign the appropriate roles to the agent based on their responsibilities. Assign the agent to the relevant departments. This determines which support tickets they can access and respond to. You can select one or multiple departments for the agent, depending on their scope of responsibility. If desired, you can further customize the agent's access privileges by selecting specific options under the "Access" section. This includes enabling or disabling features like access to the knowledgebase or ability to create new tickets. Save the agent's configuration by clicking the "Save" button. Repeat the process to create additional agent accounts as necessary.
</p>
<br />

<p>
<img src="https://imgur.com/voAEAai.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the left sidebar of the admin panel, navigate to the "Users" section and click on it. On the Users page, you can view a list of existing users if any have been registered in the system. To create a new user account, click the "Add New User" button. Provide the necessary information for the user, such as their name, email address, and any additional details you may require, such as a contact number or organization name. Save the user's account by clicking the "Save" button. Once the user account is created, the user will receive an email containing their login credentials and instructions for accessing the osTicket system.
</p>
<br />

<p>
<img src="https://imgur.com/1kdwJ8i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the left sidebar of the admin panel, navigate to the "Settings" section and click on "SLA." On the SLA page, you'll find the list of existing SLAs if any have been set up previously. To create a new SLA, click the "Add New SLA" button. Provide a name for the SLA that reflects the type of service level agreement you want to set. For example, "Standard SLA" or "VIP SLA." Define the response time target by specifying the number of hours or days within which an initial response should be provided to a ticket. Specify the resolution time target by setting the number of hours or days in which the ticket should be resolved or completed. Save the SLA configuration by clicking the "Save" button. Repeat the process to create additional SLAs as necessary.
</p>
<br />

<p>
<img src="https://imgur.com/gclgVhi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the left sidebar of the admin panel, navigate to the "Knowledgebase & FAQ" section and click on "Help Topics." On the Help Topics page, you'll see a list of existing help topics if any have been set up previously. To create a new help topic, click the "Add New Help Topic" button. Provide a name for the help topic, which should describe the category or subject of the tickets it covers. Save the help topic configuration by clicking the "Save" button. Repeat the process to create additional help topics as necessary.
</p>
<br />

