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
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- PHP manager for IIS
- Rewrite Module
- PHP 7.3.8
- VC redist.x86.exe.
- MySQL 5.5.62

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/WouLNa9.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
At this stage of the osTicket installation all the prerequisits have been downloaded and tested to make sure they are running correctly. The image is showing that inital download of osTicket. There were extentions that needed to be enabled such as php_imap, php_intl, php_opcache. 
</p>
<br />

<p>
<img src="https://i.imgur.com/lYGHIFI.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This image now shows the necessary extentions have been enabled 
</p>
<br />

<p>
<img src="https://i.imgur.com/KZf49ut.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
osTicket is now ready for confirguration and clean up. This will include installing Hedi SQL while simultaneously configuring osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/UOA9310.jpg)" height="80%" width="80%" alt="Disk Sanitation Stepd"/>
</p>
<p>
 The configuration consisted of a named database in osTicket under MySQL and started a new session in Heidi SQL.   Aterwards, the cleanup was done by the set permissions to "Read" only of C:\inetpub\wwwroot\osTicket\ost-config.php and deletion of C:\inetpub\wwwrkoot\osTicket\setup.  
</p>
<br />

<p>
<img src="https://i.imgur.com/TC0tK3n.png) height="80%" width="80%" alt="Disk Sanitation Steps"/>
</p>
<p>
This point in time all installations, downloads, configurations, have been accomplished and osTicket is now ready for post installation setup.
