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
In this lab, you will be setting up a virtual machine in Azure, installing the osTicket helpdesk software and its requirements, configuring osTicket, and exploring its functionalities as a Help Desk Professional. The process consists of five main stages: creating the virtual environment in Azure, preparing the virtual machine for osTicket installation, installing the required components, configuring osTicket, and cleaning up the virtual environment.
</p>
<br />

<p>
<img src="https://i.imgur.com/v6aXEEW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, you will create a resource group and a virtual machine in Azure, configuring the necessary settings such as region, image, size, and administrator account credentials. You will also set up the virtual network within the same resource group.
</p>
<br />

<p>
<img src="https://i.imgur.com/4NF4LuV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, you will prepare the virtual machine for osTicket installation by enabling Internet Information Services (IIS), installing PHP Manager for IIS, Rewrite Module, PHP, and MySQL. You will also configure IIS and PHP settings to ensure they work correctly.
</p>
<br />

<p>
<img src="https://i.imgur.com/HfYWErA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After installing the necessary components, you will download and install osTicket by copying the "upload" folder to the web server directory, renaming it to "osTicket," and then launching the osTicket Installer. You will enable the required PHP extensions and configure the osTicket installation settings such as Helpdesk Name, Default Email, and Admin User.
</p>
<br />

<p>
<img src="https://i.imgur.com/UGVgvoP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once osTicket is installed, you will use HeidiSQL to create the MySQL database needed for osTicket. You will then finalize the osTicket installation by providing the MySQL database information in the osTicket Installer and clicking "Install Now."
</p>
<p>
Finally, you will clean up the virtual environment by deleting the setup folder and setting the correct permissions for the ost-config.php file to ensure the security of your osTicket installation.
</p>
<br />
