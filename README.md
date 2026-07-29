<h1>Account creation and CMD Commands</h1>

<h2>Description</h2>
This project consists of changing the default computer name to one that´s easier to be familiar with, and installing Active Directory, a key component. This project is very important, since it will prepare the machine for everyday tasks on IT support.
<br />


<h2>Software Used</h2>

- <b>Latest version of VirtualBox</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2016</b>

<h2>Walk-through:</h2>

<p align="center">
Opened up explorer → Properties by right clicking This PC → Change settings and named the computer Server 2016. This will prompt a restart, so I clicked OK to restart the machine.  <br/>
<img src="https://i.imgur.com/JrzCrim.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br />
 <img src="https://i.imgur.com/BdBjDCL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br />
In the System page i was beforehand, clicked Performance → Settings → maked sure all boxes are turned off. <br/>
 <br />
<img src="https://i.imgur.com/kUGdfq3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Opened Server manager, clicked manage and "Add roles and features". This will open the setup for installing Active Directory, I followed along.  <br/>
 <br />
<img src="https://i.imgur.com/IFV6tC6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <img src="https://i.imgur.com/Wuh8AoF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The Deployment configuration popped up after waiting at the previous step. I selected "Add a new forest" and typed "jerhunt.com" as the domain name.  <br/>
 <br />
<img src="https://i.imgur.com/aP7tdM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After waiting for the installation, I set a secure password. I also set the NetBIOS to JERHUNT.  <br/>
 <br />
<img src="https://i.imgur.com/uBp1PAT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
<img src="https://i.imgur.com/Ip6rIFS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Afterwards, the installation is complete and I now have Active Directory. This can be found in "Tools" at the navigation bar in Server Manager. I pinned Active Directory Users and Computers to my taskbar, because this is the bread and butter of IT support.  <br/>
 <br />
<img src="https://i.imgur.com/9gZs6Jw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br />
<img src="https://i.imgur.com/zFsKtH2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
