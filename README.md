<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Azure Portal.

Sign in with your Azure account.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Azure Portal, click on the "Create a resource" button.

Under Compute, select "Virtual Machine".

</p>Subscription – Choose the appropriate subscription.

Resource Group – Either create a new one or use an existing one.

Virtual Machine Name – Enter a name for your VM.

Region – Choose the desired location for your VM.

Availability Options – Choose redundancy settings based on your needs.

Security Type – Select Standard or Trusted Launch VM.

Image – Select an OS (e.g., Windows Server, Ubuntu, etc.).

Size – Select a VM size based on your needs.

Administrator Account – Enter username and password or use SSH keys for authentication.

<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
OS Disk Type – Choose SSD or HDD.

Optionally, add a data disk.
Virtual Network – Use an existing VNet or create a new one.

Subnet – Select or create a subnet.

Public IP – Enable or disable a public IP.

Inbound Ports – Allow specific ports (e.g., RDP for Windows, SSH for Linux).
Enable or disable Boot diagnostics, Auto-shutdown, Monitoring, etc.

Enable Backup (optional).</p>
Click "Review + Create".

Verify your configurations.

Click "Create" to start the deployment.
Windows VM: Use Remote Desktop (RDP) to connect.

Linux VM: Use SSH to connect.<br />
