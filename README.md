<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Virtual Machine Deployed in the Cloud (Azure)</h1>
This tutorial outlines the steps to creating a virtual machine and connecting to Remote Desktop in Microsoft Azure.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level steps to set up a virtual machine and connect to Remote Desktop in Microsoft Azure:</h2>

1. Log in to your Azure account and go to the Azure Portal.
2. Click on "Create a resource" and search for "Windows Server" in the marketplace.
3. Choose the version of Windows Server you want to use and configure the virtual machine settings, such as the name, region, and size.
4. Set up the login credentials and choose the authentication type.
5. Configure the networking settings, such as the virtual network and subnet.
6. Review and create the virtual machine.
7. Once the virtual machine is created, go to the "Overview" section of the virtual machine and click on "Connect" to download the Remote Desktop Protocol (RDP) file.
8. Open the RDP file and enter the login credentials for the virtual machine.
9. Click "Connect" to connect to the virtual machine and start using Remote Desktop.


<h2>Creating and Connecting Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Log in to your Azure account and go to the Azure Portal.
  - Go to the Azure Portal (https://portal.azure.com/) and sign in to your Azure account. In the left-hand menu, click on "Create a resource".
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Choose the version of Windows Server you want to use and click on "Create".
On the "Basics" tab, configure the virtual machine settings, such as the name, region, and size. You can also select the disk type and configure availability options.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Set up the login credentials and choose the authentication type.
  -On the "Administrator account" tab, set up the login credentials and choose the authentication type (password or SSH public key).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Configure the networking settings, such as the virtual network and subnet.
  -On the "Networking" tab, configure the networking settings, such as the virtual network and subnet. You can also configure public IP and DNS settings.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Review and create the virtual machine.
  -Review your settings and click on "Create" to create the virtual machine.
 Once the virtual machine is created, go to the "Overview" section of the virtual machine and click on "Connect" to download the Remote Desktop Protocol (RDP) file.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Open the RDP file and enter the login credentials for the virtual machine.
  
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Click "Connect" to connect to the virtual machine and start using Remote Desktop.
</p>
<br />
That's it! You should now be able to access your virtual machine through Remote Desktop.
