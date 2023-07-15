# VM-s-Traffic-Prerequisites
This list is a brief description of how to setup your two Virtual Machines (Windows and Linux), so that Network Traffic may be observed between them both.

<img src="https://i.imgur.com/5Xcad7u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Wireshark

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (22H2)
- [Linux] Ubuntu Server</b> (20.04 LTS)

<h2>List of Prerequisites</h2>

- Microsoft Azure

<h2>Installation Steps</h2>

<p>

  
1.) The first step will be to create a Resource Group, within Azure (https://portal.azure.com/). Create your Windows 10 Pro, version 22H2 Virtual Machine within the created Resource Group. 
NOTE: Ensure the VM has at least 2vcpus and 16 GiB memory.

<img src="https://i.imgur.com/Y1DgfIA.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>


When creating the VM, allow a new Virtual Network and Subnet to be created.

<img src="https://i.imgur.com/QDcrOuu.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>


2.) In the same resource group from step 1, create your Linux (Ubuntu) Server 20.04 LTS. The Ubuntu VM is okay to run on minimal vcups and Gib memory.

<img src="https://i.imgur.com/cs789uO.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

NOTE: When creating the Linux VM, choose the previously selected Resource Group and V-Network as the Windows 10 VM.

<img src="https://i.imgur.com/euaBqEw.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/v0exv6S.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

- Double check that both of your Virtual Machines have the same Virtual Network/Subnet in Microsoft Azure

<img src="https://i.imgur.com/td9fAQG.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/dfFMgxa.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

3.) Connect to your Windows 10 VM via Remote Desktop, using the public IP address and created login information. Once connected, download and install Wireshark on the VM. (https://www.wireshark.org)

- Obtain your Windows 10 Public IP address from within Microsoft Azure
  
<img src="https://i.imgur.com/J0cI8b9.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

- Remote desktop into the Windows 10 VM, using the retrieved Public IP address

<img src="https://i.imgur.com/lIHeUOa.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

- Using the Windows 10 Virtual Machine, use the browers to download and install Wireshark. (https://www.wireshark.org)

<img src="https://i.imgur.com/3XYQ6Ya.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/U6Dd4XI.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>


- Once installed, open Wireshark and you may begin filtering for your various traffics


<img src="https://i.imgur.com/M5gDNmi.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
