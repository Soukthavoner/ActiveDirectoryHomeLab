<h1>Active Directory Home Lab</h1>

 

<h2>Description</h2>
In this lab, I walked through how to create an Active Directory home lab environment using Orcale Virtual Box. Configuring and running this lab to help develop my understanding of how active directory and windows networking works.<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Server 2019</b>

<h2>Set Up:</h2>
<h3>Required Downloads:</h3>
- <a href="https://www.virtualbox.org/wiki/Downloads"><b>The lastest version of the Virtual Box platform and extension pack</b></a></br>
- <a href="https://www.microsoft.com/en-us/software-download/windows10"><b>Windows 10 ISO</b></a></br>
- <a href="https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019"><b>Windows Server 2019 ISO</b></a>

<h3>Setting Up the Virtual Box:</h3>
<p align="center">
 Open Oracle Virtual Box and then being with making the server computer by clicking on "New".<br/>
 <img src="https://i.imgur.com/loRZrpo.png" height="80%" width="80%" alt="Setting Up the Virtual Box"/>
 <br/>
 <br/>
 Naming the server "DC" and setting the OS version to "Other Windows (64-bit)<br/>
 <img src="https://i.imgur.com/voT3zly.png" height="80%" width="80%" alt="Setting Up the Virtual Box"/>
 <br/>
 <br/>
 Going to the DC's computer settings and in the General Features I give the server 2GB of RAM and 2 CPU processors<br/>
 <img src="https://i.imgur.com/7iz3hL3.png" height="80%" width="80%" alt="Setting Up the Virtual Box"/>
 <br/>
 <br/>
 Changing the computer settings by clicking on settings and in the General Features tab, changed the "Shared Clipboard" and "Drag-and-Drop" to "Bidirectional"<br/>
 <img src="https://i.imgur.com/Ub3ZryF.png" height="80%" width="80%" alt="Setting Up the Virtual Box"/>
 <br/>
 <br/>
 Going into the Newtork settings, make sure the first adapter is attached to "NAT" so it uses my local Wifi and enable the second adapter to be attached to the "Internal Network"<br/>
 <img src="https://i.imgur.com/tsYkQNg.png" height="40%" width="40%" alt="Setting Up the Virtual Box"/>
 <img src="https://i.imgur.com/nKyHzuJ.png" height="40%" width="40%" alt="Setting Up the Virtual Box"/>
 <br/>
 <br/>
</p>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
