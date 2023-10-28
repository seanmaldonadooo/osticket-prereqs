<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- IIS in Windows WITH CGI and Common HTTP Features and IIS Management Console
- PHP Manager for IIS
- Rewrite Module
- PHP 7.3.8
- VC_redist
- MySQL 5.5.62

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/seanmaldonadooo/osticket-prereqs/assets/149026184/8a2c4e8e-acc5-4c91-9f7c-f0678a9987ae" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Install / Enable IIS in Windows WITH CGI and Common HTTP Features. Install all prerequisites. (after installing Rewrite Module create a directory named C:\PHP)
</p>
<br />

<p>
<img src="https://github.com/seanmaldonadooo/osticket-prereqs/assets/149026184/6fdf0757-b750-4c0b-9de3-32b472bdd72b" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open IIS as Administrator. Register PHP inside of IIS. Restart server after registry. Install osTicket v1.15.8 . Extract and copy “upload” folder to c:\inetpub\wwwroot . Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”. Restart the server.
</p>
<br />

<p>
<img src="https://github.com/seanmaldonadooo/osticket-prereqs/assets/149026184/c8269d6e-9653-4bcb-86fc-0ae657f80a7d" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go back to IIS, sites -> Default -> osTicket
Double-click PHP Manager
Click “Enable or disable an extension”
Enable: php_imap.dll
Enable: php_intl.dll
Enable: php_opcache.dll

</p>
<br />

<p>
<img src="https://github.com/seanmaldonadooo/osticket-prereqs/assets/149026184/dcd6c19f-d62f-453a-9cdf-2dd0aef21752" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Rename: ost-config.php
From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php
To: C:\inetpub\wwwroot\osTicket\include\ost-config.php
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

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
