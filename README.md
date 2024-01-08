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
Setup Windows Server 2019 after downloading appropriate ISO images. I was having issues getting the VM to boot up initially. That led me to the BIOS menu on my computer where I then enabled settings to allow for virtualization:  <br/>
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
Create new organization unit :  <br/>
<img src="https://i.imgur.com/Ifz61BR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>
