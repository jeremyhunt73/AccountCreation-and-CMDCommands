<h1>Account creation and CMD Commands</h1>

<h2>Description</h2>
This project consists on creating an account on Server 2016 by copying an existing one. Also, a few CMD commands for viewing very important information like IP address and info related to a user. Knowing these concepts is fundamental on day-to-day IT support tasks, it lets us identify computers and finding users.
<br />


<h2>Software Used</h2>

- <b>Latest version of VirtualBox</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2016</b>

<h2>Walk-through:</h2>

<p align="center">
I headed over to Active Directory Users and Computers to enable advanced features. <br/>
<img src="https://i.imgur.com/uiRwLGC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br />
Right clicked on computers, selected find, and typed in Guest. Note: searching for a user must be done via the entire directory, not only computers. This will make finding a user way more effective. <br/>
 <br />
<img src="https://i.imgur.com/bCwhFu8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/qGWVUZI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
