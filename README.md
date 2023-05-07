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

- Enable Internet Information Services (IIS)
- Install Web Platform Installer
- Install MySQL, Setup Username & Password
- Install C++ Redistributable
- Configure Permissions & Install OSTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/OIKJFXG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this project, I successfully deployed and configured osTicket, a widely recognized helpdesk software, on a Microsoft Azure virtual machine. This project demonstrates my ability to work with cloud infrastructure, manage virtual machines, and install and configure web-based applications.
</p>
<br />

<p>
<img src="https://i.imgur.com/v6aXEEW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To begin, I created a resource group and a virtual machine in Azure, considering essential settings such as the region, image, size, and administrator account credentials. I also set up a virtual network within the same resource group, ensuring that the virtual environment was secure and organized.
<br />

<p>
<img src="https://i.imgur.com/4NF4LuV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I prepared the virtual machine for osTicket installation by enabling Internet Information Services (IIS) and installing PHP Manager for IIS, the Rewrite Module, PHP, and MySQL. I then configured IIS and PHP settings, guaranteeing their compatibility and proper functioning.
</p>
<br />

<p>
<img src="https://i.imgur.com/HfYWErA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After preparing the virtual machine, I installed osTicket by copying the "upload" folder to the web server directory, renaming it to "osTicket," and launching the osTicket Installer. I enabled the necessary PHP extensions and configured essential osTicket installation settings, such as the Helpdesk Name, Default Email, and Admin User.
</p>
<br />

<p>
<img src="https://i.imgur.com/UGVgvoP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To complete the osTicket installation, I used HeidiSQL to create a MySQL database and provided the required database information in the osTicket Installer, clicking "Install Now" to finalize the process.
</p>
<p>
Lastly, I cleaned up the virtual environment by deleting the setup folder and setting the appropriate permissions for the ost-config.php file, ensuring the security of the osTicket installation. This project showcases my ability to deploy and manage web applications, work with cloud infrastructure, and implement secure and efficient solutions for organizations.
</p>
<br />
