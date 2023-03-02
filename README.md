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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Depending on their assigned role within the helpdesk, agents will be assigned to specific departments. For our Supreme Admin, we will need to create a "System Administrators" department, where we will place the Supreme Admin. Service Level Agreements, managers, and email settings can be added and edited in the departments tab
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring our new department, we need to think about our team structures. Teams allow you to pull and group agents from different departments. This would be useful in instances where you have a variety of products that different agents handle within the same department. Teams would allow  you to group the specific agents in their respective departments and create a team that specializes in that particular product. 
</p>
<p>
To set up our team through the Admin Panel, we will go to Agents --> Teams. We see that a Level 1 support has already been created, so we will create a Level 2 support team for escalated issues. 
<br />
</p>
<p>
Now that we have swet up a new team we will create a new setting that will allow anyone to create tickets. This can be done through Admin Panel -->Settings -->User Settings.
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
