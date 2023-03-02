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

- Item 1: Installed CGI and enabled Internet Information Services (IIS)
- Item 2: Installed PHP Manager
- Item 3: Installed MYSQL
- Item 4: Installed C++ redistributable
- Item 5: Configured permissons and Installed os-ticket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DewPx12.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Intsalled CGI with IIS to enable the use of PHP manager to use os-ticket
</p>
<br />

<p>
<img src="https://i.imgur.com/DIdUabi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installation of PHP manager to utilize os-ticket application
</p>
<br />


<p>
<img src="https://i.imgur.com/aE6ej9s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You then have to enable PHP by using the PHP manager we installed on the VM earlier
</p>
<br />


<p>
<img src="https://i.imgur.com/Oh3HgM6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
PHP should now be enabled on your VM
</p>
<br />



<p>
<img src="https://i.imgur.com/uch7gAW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installation of MYSQL
</p>
<br />

<p>
<img src="https://i.imgur.com/jKa11LJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installation of c++
</p>
<br />

<p>
<img src="https://i.imgur.com/sf8phQV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installation of os-Ticket due to some extensions not working properly we must enable them using IIS
</p>
<br />

<p>
<img src="https://i.imgur.com/yHaNcEn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once enabling the extensions you should get the following screen
</p>
<br />




<p>
<img src="https://i.imgur.com/3hzzl5r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Success !!! os Ticket is officialy installed and usable in your VM 
</p>
<br />
