<h1>Active Directory Homelab</h1>

<h2>Description</h2>
This project uses virtual machines to simulate an Active Directory environment implemented with Powershell.   
<br />


<h2>Languages and Utilities Used</h2>

- <b>Powershell</b> 


<h2>Environments Used </h2>

- <b>Virtual Box, Windows 10, Windows Server 2019</b> 

<h2>Project walk-through:</h2>

<p align="center">
Download VirtualBox: Head to the Oracle website to download the hypervisor for your preferred operating system. This will hold our Windows 10 and Windows 2019 server machines https://www.virtualbox.org/wiki/Downloads<br/>
<img src="https://i.imgur.com/y4Z1svR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set up Windows Server 2019 after downloading appropriate ISO images. I was having issues getting the VM to boot up initially. That led me to the BIOS menu on my computer where I then enabled settings to allow for virtualization:  <br/>
<img src="https://i.imgur.com/0ZpOFOw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure IP addresses per device. Here is the addressing scheme used below:  <br/>
<img src="https://i.imgur.com/epvtVrV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
  Install Active Directory Domain Services on VM:  <br/>
<img src="https://i.imgur.com/6jl6tKz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br />
<br />
Create a new organization unit:  <br/>
<img src="https://i.imgur.com/rSTbGoe.png" height="80%" width="80%" alt="Active Directory"/>
<img src="https://i.imgur.com/Xkgh01n.png" height="80%" width="80%" alt="Active Directory"/>
<img src="https://i.imgur.com/OB6XtSG.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Configure routing and DHCP:  <br/>
<img src="https://i.imgur.com/siV48rj.png" height="80%" width="80%" alt="Active Directory"/>
<img src="https://i.imgur.com/gD1OKwW.png" height="80%" width="80%" alt="Active Directory"/>
<img src="https://i.imgur.com/82ZKHbs.png" height="80%" width="80%" alt="Active Directory"/>
<img src="https://i.imgur.com/Q81jPuC.png" height="80%" width="80%" alt="Active Directory"/>
<img src="https://i.imgur.com/fxmJfFO.png" height="80%" width="80%" alt="Active Directory"/>
<img src="https://i.imgur.com/sCLtyK3.png" height="80%" width="80%" alt="Active Directory"/>
<br />
<br />
Retrieve the Powershell script to create users and run Powershell as an administrator. Then I set the command execution policy to unrestricted and load the script. Next, I navigate to the name file directory in PowerShell and execute the script. I can then view roughly over 400 created users in the server manager window.:  <br/>
<img src="https://i.imgur.com/5Ttfdya.png" height="80%" width="80%" alt="Active Directory"/>
<img src="https://i.imgur.com/jGKTWEe.png"80%" width="80%" alt="Active Directory"/>
<img src="https://i.imgur.com/HyvZVs7.png" width="80%" alt="Active Directory"/>
<img src="https://i.imgur.com/x8AMhr7.png" width="80%" alt="Active Directory"/>
<img src="https://i.imgur.com/wTFSX0W.png" width="80%" alt="Active Directory"/>
<br />
<br />
Create Windows client:  <br/>
<img src="https://i.imgur.com/soLgJSS.png" height="80%" width="80%" alt="Active Directory"/>
<img src="https://i.imgur.com/vbdj5o4.png" height="80%" width="80%" alt="Active Directory"/> 
</p>
