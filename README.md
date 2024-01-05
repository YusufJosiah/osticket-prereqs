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

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- Enable IIS in Windows with CGI and Common HTTP Features
- Install web platform installer
- Install mySQL and set-up username and password
- Install C++ redistributable
- Configure permissions and install osTickets

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/hH1D6bu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The process of installing osTicket from scratch involves multiple steps after deploying resources on the Azure cloud computing platform. Once inside the Virtual Machine (VM) using a Remote Desktop Connection, the installation process typically includes the following steps: Install Internet Information Services (IIS), add PHP support by installing PHP and configuring it to work with IIS; Configure PHP settings within IIS Manager to ensure proper integration between PHP and IIS; Set up MySQL database where osTicket will store its data; etc.
</p>
<br />

<p>
<img src="https://i.imgur.com/ieAmJII.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After installation of all files prior to installing osTicket, access IIS as administrator and click on PHP manger to register PHP. Then restart server.
</p>
<br />

<p>
<img src="https://i.imgur.com/GqICUP3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download osTicket and extract the folder named "upload" into c:\inetpub\wwwroot. Then rename it to “osTicket.” Now restart the server. Click on the server, then sites then Default then osTicket. On the right, click “Browse *:80” you will land on the page pictured above.
</p>
<br />
<p>
<img src="https://i.imgur.com/hYNXtv1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Access the PHP manager and enable these important extensions: php_imap.dll; php_intl.dll; php_opcache.dll. Then rename ost-sampleconfig.php to ost-config.php in C:\inetpub\wwwroot\osTicket\include. Lastly, create MySQL Database and install osTicket in the browser.
</p>
<br />
