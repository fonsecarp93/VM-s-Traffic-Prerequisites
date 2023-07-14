# VM-s-Traffic-Prerequisites
This list is a brief description of how to setup your two Virtual Machines (Windows and Ubuntu), so that Network Traffic may be observed between them both.

# osticket-prereqs

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Wireshark
- 

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (22H2)
- Ubuntu Server</b> (20.04 LTS)

<h2>List of Prerequisites</h2>

- Microsoft Azure

<h2>Installation Steps</h2>

<p>

  
1.) The first step will be to create a Resource Group, within Azure (https://portal.azure.com/). Create your Windows 10 Pro, version 22H2 Virtual Machine within the created Resource Group. 
NOTE: Ensure the VM has at least 2vcpus and 16 GiB memory.

When creating the VM, allow a new Virtual Network and Subnet to be created.

2.) In the same resource group from step 1, create your Linux (Ubuntu) Server 20.04 LTS. The Ubunt VM is okay to run on minimal vcups and Gib memory.


3.) Connect to your Windows 10 VM via Remote Desktop, using the public IP address and created login information. Once connected, download and install Wireshark on the VM. (https://www.wireshark.org)
  
    

<img src="https://i.imgur.com/oRPg6fI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


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
