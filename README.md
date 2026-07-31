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
Headed over to Active Directory Administravive Center, opened the local user and enabled recycle bin. This took a few minutes, it created a Deleted Objects folder. Also, this feature is useful if something is deleted by accident. <br/>
 <br />
<img src="https://i.imgur.com/fp1kEfI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <img src="https://i.imgur.com/lQ0VBR2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br />
<img src="https://i.imgur.com/NsGgdZe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
To add a new user, I headed over to AD Users and Computers → right clicked on a user → copy → filled in first, full, and user logon name → created a password. This is called Automation; creating a user by doing it this way saves time and effort, the which is very effective. In this case, since I copied the Admin, that account is going appear in several groups. <br/>
 <br />
<img src="https://i.imgur.com/MGarC7D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/oVe8Lze.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/lMqj7ib.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
