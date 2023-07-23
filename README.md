<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com/watch?v=TCW03bksEYQ)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a Virtual Machine in Azure
- Log in to the Azure Virtual Machine (VM) using Remote Desktop
- Install Active Directory Domain Services
- Open PowerShell on the Azure VM

<h2>Deployment and Configuration Steps</h2>

<p>
<a href="https://imgur.com/m68Q8wy"><img src="https://i.imgur.com/m68Q8wy.png" title="source: imgur.com" /></a>
</p>
<p>
Creating a virtual machine (VM) in Microsoft Azure is indeed the first step in deploying Active Directory (AD) since Active Directory requires a Windows Server environment to run. 
</p>
<br />

<p>
<a href="https://imgur.com/sm51JPY"><img src="https://i.imgur.com/sm51JPY.png" title="source: imgur.com" /></a>
</p>
<p>
After creating the virtual machine (VM) in Microsoft Azure, the next step is to remote sign into the VM to set up Active Directory (AD). Remote signing in allows you to access and configure the VM from your local machine. 
</p>
<br />

<p>
<a href="https://imgur.com/4kY0lCz"><img src="https://i.imgur.com/4kY0lCz.png" title="source: imgur.com" /></a>
</p>
<p>
Setting up Active Directory (AD) involves installing the Active Directory Domain Services (AD DS) role on a Windows Server and configuring it to act as a domain controller. 
</p>
<br />

<a href="https://imgur.com/nyOGS9l"><img src="https://i.imgur.com/nyOGS9l.png" title="source: imgur.com" /></a>


Using PowerShell in Active Directory allows you to perform various administrative tasks, automate processes, and manage Active Directory objects more efficiently
