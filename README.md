<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial outlines the post-configuration setup of the osTicket system, guiding you through the necessary steps to ensure your helpdesk is fully operational. .<br />

<p>

</p>
</p>
<p>
Great job on successfully configuring osTicket from scratch! Now, let’s move on to some system administration and post-installation setup.

### Configuring New Roles in osTicket

1. **Access the Admin Panel**: Log in to the osTicket Admin Panel.
2. Navigate to **Agents** > **Roles**.

#### Creating a Supreme Admin Role

3. Click on **Add New Role**.
4. Enter the name for the new role, in this case, **Supreme Admin**.
5. Modify the permissions as needed. For the Supreme Admin role, ensure that all permissions are granted.

### Important Note
Roles are essential for determining an agent's permissions within the helpdesk. Not all agents will have unlimited access, so be thoughtful about how you assign roles.

If you’ve followed these steps correctly, your screen should now display the newly created **Supreme Admin** role, indicating successful configuration. You’re well on your way to customizing your helpdesk to suit your team’s needs!
</p>
<img src="https://i.imgur.com/XHteqdt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
Next, let’s create a new department in osTicket to organize your agents effectively.

### Creating a New Department

1. In the **Admin Panel**, navigate to the **Agents** tab.
2. Click on the **Departments** button.

#### Adding the System Administrators Department

3. Click on **Add New Department**.
4. Enter the name for the new department, in this case, **System Administrators**. This department will be designated for the Supreme Admins.
5. You can also configure additional settings for the department, such as:
   - **Service Level Agreements (SLAs)**
   - **Department Managers**
   - **Email settings** for handling communication specific to the department.

By organizing agents into departments, you enhance workflow management and ensure that each agent is assigned tasks relevant to their role. Once you’ve set up the **System Administrators** department, you’ll be ready to assign agents accordingly.
</p>
<br />
<p>
<img src="https://i.imgur.com/dGK0RVM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring the new department, let’s move on to setting up a new team in osTicket. Teams are beneficial for pulling agents from various departments to address specific issues or topics effectively.

### Setting Up a New Team

1. In the **Admin Panel**, go to **Agents** > **Teams**.

#### Creating the Level II Support Team

2. You’ll notice a default **Level I Support Team** has already been created. To create a new team:
   - Click on **Add New Team**.
3. Enter the name for the new team, which will be **Level II Support Team**.

### Assigning Team Members

4. Once the team is created, you can assign agents from different departments to this team. This allows you to have a group of top technicians who specialize in specific areas.

Using teams effectively enables you to tackle more complex issues by leveraging the expertise of agents across various departments, ensuring a well-rounded support system. Once you’ve set up the **Level II Support Team**, you can customize it further based on your operational needs! 
</p>
<br />
<p>
<img src="https://i.imgur.com/cYzWBD2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that you’ve set up the new team, let’s configure a setting that allows anyone to create tickets in osTicket.

### Enabling Ticket Creation for All Users

1. In the **Admin Panel**, navigate to **Settings** > **User Settings**.

#### Adjusting User Settings

2. Look for the option that allows you to enable ticket creation by users.
3. Ensure that the setting is configured to allow **anyone** to create tickets.

By enabling this option, you make it easier for customers and users to submit tickets without requiring an account. This can improve your helpdesk's responsiveness and accessibility. Once this setting is configured, you’ll be ready to start receiving tickets from a broader audience!

</p>
<br />
<img src="https://i.imgur.com/H1q2Fdh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, let’s move on to creating **Agents** in osTicket. Agents are the employees who will actively work on resolving tickets, and each agent is assigned to a specific department with corresponding roles.

### Creating Agents

1. In the **Admin Panel**, navigate to the **Agents** tab.

#### Adding New Agents

2. Click on **Add New Agent**.
3. Fill in the required details for the new agent, including:
   - **Name**
   - **Email Address**
   - **Username**
   - **Password**

4. Assign the agent to a **primary department** and select their **primary role** based on the tickets they will be handling.

### Additional Permissions and Access

- Agents can be granted access to other departments beyond their primary assignment if needed.
- You can also assign different roles depending on the departments they access, allowing flexibility in their responsibilities.

### Permissions, Access, & Teams

5. Configure any necessary permissions and access levels for the agent. This is where you can determine what each agent can see and do within the system.
6. If applicable, assign the agent to specific teams for collaborative ticket resolution.

Once you’ve set up your agents, they’ll be ready to start managing and resolving tickets efficiently! 
</p>
<br />
<img src="https://i.imgur.com/8WTOSre.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you’ve created your agents, the next step is to set up **Users**. Users are the customers who will create tickets when they encounter issues, and they are identified by their email addresses.

### Creating Users

1. In the **Admin Panel**, navigate to **Users** > **User Directory**.
2. Click on **Add New** to create a new user.

#### Entering User Details

3. Fill in the required information for the user, including:
   - **Name**
   - **Email Address** (This will be their identifier in the system)
   - **Any additional details** you wish to include (like phone number or company).

### Finalizing User Creation

4. Once you’ve entered the user details, save the information.

Repeat this process to add multiple users as needed. With users in place, your helpdesk will be ready to receive and manage tickets effectively, allowing for a streamlined support experience!
</p>
<br />
<img src="https://i.imgur.com/xOprA9f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, let’s set up **Service Level Agreements (SLAs)** for your helpdesk. SLA Plans define the expected time frames for resolving specific tickets, ensuring timely support for users.

### Creating SLA Plans

1. In the **Admin Panel**, navigate to **Manage** > **SLA Plans**.
2. Click on **Add New SLA Plan** to create a new SLA.

#### Configuring SLA Details

3. When creating the SLA Plan, you will need to define:
   - **Name**: For example, **SEV-A**.
   - **Schedule**: Determine the working hours (for example, 24/7 support).
   - **Grace Period**: Set a grace period for ticket resolution; in this case, you can specify a one-hour grace period.

### Finalizing the SLA Plan

4. Save the SLA Plan once you have configured the necessary settings.

By setting up SLA Plans, you help ensure that your helpdesk meets user expectations for ticket resolution times, contributing to a more efficient support process. Repeat this process for additional SLA Plans as needed based on your operational requirements! 
</p>
<br />
<img src="https://i.imgur.com/LpjCaLd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, let’s create **Help Topics** to help users categorize their tickets effectively. Help Topics allow users to specify the nature of their issues, making it easier for agents to prioritize and address tickets based on their urgency and type.

### Creating Help Topics

1. In the **Admin Panel**, navigate to **Manage** > **Help Topics**.
2. Click on **Add New Help Topic** to create a new topic.

#### Defining the Help Topic

3. For example, create a help topic titled **Business Critical Outage**. This topic could be used for scenarios where customers are unable to access essential services, such as mobile banking.

4. Fill in any additional details or descriptions as needed to clarify the purpose of the help topic.

### Finalizing the Help Topic

5. Save the new help topic once you have configured the settings.

By establishing help topics, you enable users to better articulate their issues, which helps agents quickly assess and prioritize tickets, ensuring a more efficient resolution process. You can create additional help topics as necessary to cover various issues your users may encounter!
</p>
<br />
<img src="https://i.imgur.com/kB7rts2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
