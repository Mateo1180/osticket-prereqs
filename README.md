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

- Step 1: Create and log into Azure Vitrutal Machine using Remote Desktop Application
- Step 2: Install and Enable IIS in Windows and IIS Management Console
- Step 3: Download and Install PHP Manager for IIS
- Step 4: Download and install the Rewrite Module
- Step 5: Create a directory called C:\PHP
- Step 6: Download PHP 7.3.8 and unzip its contents into C:\PHP
- Step 7: Download and install VC redist.x86.exe
- Step 8: Then Download,install, and configure MySQL 5.5.62
- Step 9: Open IIS as an Admin
- Step 10: Register PHP from within IIS
- Step 11: Reload IIS 
- Step 12: Install and configure osTicket


<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/a/Wpqgz03"/>
</p>
<p>
First I started out by creating a virtual Machine using Microsoft Azure. Then I downloaded Microsoft Remote Desktop onto my Mac computer which, I use to run the virtual machine that I created in Azure. The reason I am performing all of these steps so far is that I have no way of installing osTicket on my Mac. So I need a way of using a Windows Operating System on my Mac. Azure and Remote Desktop allowed me to do just that. 
</p>
<br />

<p>
<img src="file:///Users/mattleslie/Desktop/ScreenShots%20for%20IT%20Portfolio/Screenshot%202024-05-28%20at%205.46.47%20PM.png"/>
</p>
<p>
 Next step is to open IIS as an Admin but before I could do that I needed to configure and install a bunch of other apps first. I had to first Install and Enable IIS in Windows and IIS Management Console, Download and Install PHP Manager for IIS, Download and install the Rewrite Module, Create a directory called C:\PHP, Download PHP 7.3.8 and unzip its contents into C:\PHP, Download and install VC redist.x86.exe, Then Download,install, and configure MySQL 5.5.62. 
</p>
<br />

<p>
<img src="file:///Users/mattleslie/Desktop/ScreenShots%20for%20IT%20Portfolio/Screenshot%202024-05-28%20at%205.55.44%20PM.png"/>
</p>
<p>
Finally as the last step I am able to download osTicket. But first had to Register PHP from within IIS and Reload IIS. After that's done OSTicket is up and ready to go.
</p>
<br />
