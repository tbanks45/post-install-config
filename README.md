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

- Configure roles, departments, and teams
- Configure agents (workers), and configure users (customers)
- Configure SLA and configure help topics

<h2>Configuration Steps</h2>

<p>
![image](https://github.com/tbanks45/post-install-config/assets/142834800/b05535ce-5a91-4b8d-aac0-d13f244fc0d0)

</p>
<p>
After installing osTicket I was able to begin creating roles, departments, and teams to which agents or workers will be assigned to. In this example I created a supreme admin role. Any agent who is assigned to this role will have access and permission to perform all tasks.
</p>
<br />

<p>
![image](https://github.com/tbanks45/post-install-config/assets/142834800/ed66419b-b66c-4e23-b5ba-e953e71923fd)

</p>
<p>
In this example I created an agent(worker) named Donald Williams. Donald will be given a role and can be assigned to a department. He also can be assigned to a team for group troubleshooting purposes.
</p>
<br />

<p>
![image](https://github.com/tbanks45/post-install-config/assets/142834800/cc750256-912d-4424-8166-791c108d8f07)

</p>
<p>
Here I created an SLA plan with severity A. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed. This SLA has a grace period of 1 which is a short amount of time.
</p>
<br />
