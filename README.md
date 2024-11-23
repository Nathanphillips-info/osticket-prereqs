# osticket-prereqs
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

- Item 1: You will need this link to access the files to install OsTicket:
-  (https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD) 
- Item 2: In Azure, create a Windows 10 VM with at least two CPUs. Use remote desktop to log in, download the folder, and put it on the desktop.  
- Item 3: You must enable IIS in Windows with CGI. Find World Wide Web Services -> application development features -> CGI
- This can be found in Control panel -> programs -> turn windows features on or off 

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/b3f57e9d-8a0e-4172-a44f-ea8ddd9952a5"/>
</p>
<p>
- 1: Once you have moved the files to the desktop and installed IIS and CGI, you can install PHP Manager for IIS.
</p>
<p> 
- 2: Then install AMD rewrite module 
</p>
- 3: In the C: drive, create a directory for PHP and unzip the file PHP 7.3.8 into that folder in C: 
</p>
<p>
- 4: Install VC_redist.X86.exe
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/0fe7dc26-7281-47c7-bc7d-95c27833d706"/>
</p>
<p>
- 1: Next, Install my SQL 
</p>
<p> 
- 2: You will want to use the typical setup and launch the config wizard once it is complete
</p>
<p> 
- 3: In the config wizard, select the standard configuration and, for ease, make the username and password both "root." This isn't good for security, but this is just for practice. 
</p>
<p>
- 4: After completing this, you must register PHP from within IIS. Open IIS as an administrator and Register PHP. Then, you can browse to the PHP folder you created in the C: drive. You will want to select the PHP CGI file. 
</p>
<p>
- 5: Then reload IIS
</p>

</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/ac2d73f7-ed0b-4d16-902c-37e380af2ec3"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
