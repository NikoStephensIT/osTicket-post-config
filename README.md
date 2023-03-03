<p>
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

<h2>Configuration Steps</h2>

<p>

</p>
<p>
With osTicket installed, it's time for us to get to begin configuring roles. Let's start with a supreme admin. Click on "add new role" and then enter the name of the new role. After the role is created we can then modify any specific permissions we want to give it. Since this is going to be a supreme admin role, it will be granted all permissions. The "tier" of a role also has an effect on what permissions are given to agents, so not all roles have unlimited access. 
</p>
<br />

<p>
<img src="https://i.imgur.com/O66QGZd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Depending on their assigned role within the helpdesk, agents will be assigned to specific departments. For our Supreme Admin, we will need to create a "System Administrators" department, where we will place the Supreme Admin. Service Level Agreements, managers, and email settings can be added and edited in the departments tab.
</p>
<br />

<p>
<img src="https://i.imgur.com/aUEI9Vo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring our new department, we need to think about our team structures. Teams allow you to pull and group agents from different departments. This would be useful in instances where you have a variety of products that different agents handle within the same department. Teams would allow  you to group the specific agents in their respective departments and create a team that specializes in that particular product. 
</p>
<p>
To set up our team through the Admin Panel, we will go to Agents --> Teams. We see that a Level 1 support has already been created, so we will create a Level 2 support team for escalated issues. 
<br />
</p>
<p>
  <img src="https://i.imgur.com/B6N5P2X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Now that we have swet up a new team we will create a new setting that will allow anyone to create tickets. This can be done through Admin Panel -->Settings -->User Settings.
</p>
<p>
<img src="https://i.imgur.com/oy7Qb6T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will need a group of agents to respond to these tickets! Go ahead and add Jane and Josh through Agents -->Add New.
</p>
<br />

<p>
  <img src="https://i.imgur.com/aUEI9Vo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we will configure our users. Users are our typically employees of our client, calling into our call center with an issue they expect us to help solve. For this we will need to go to the Agent Panel -->Users -->Add New. Here we will add Karen and Ken as users.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As we getting all of our agents and users squared away, it is now time for up to configure our SLA. SLA, or Service Level Agreements, provide a length of time in which the help desk Administrator expects the tickets to be closed. SLA Plans can be created by going to the Admin Panel > Manage > SLA Plans. Click on the top right of the table to “Add New SLA Plan.”
</p>
<br />
<img src="https://i.imgur.com/BxmLFXA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>

</p>
