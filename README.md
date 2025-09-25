<h2>How-to-use-Remote-Desktop-Connection<h2>
<p align="center">
<img width="360" height="270" alt="rdp-icon" src="https://github.com/user-attachments/assets/6889c7e9-e23a-4398-b2a2-1923e8a4ff81" />

</p>

<h1>Azure - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and tutorial of opening Remote Desktop Connection.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Remote Desktop Connection

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

1) An active Azure subscription and access to the Azure Portal
2) A running Virtual Machine with a public IP address assigned.
3) Remote Desktop Protocol (RDP) port 3389 opened in the VM’s Networking settings.
4) The username and password created during the VM setup.
5) A Windows computer (Remote Desktop Connection is built-in) or Remote Desktop client installed on macOS/Linux.
6) A stable internet connection.

<h2>Installation Steps</h2>

<p>

<h2>How to Use Remote Desktop to Access an Azure Virtual Machine</h2>

<img width="1100" height="213" alt="sc1" src="https://github.com/user-attachments/assets/020eda54-a535-4830-b69a-82ace6935679" />
<hr>
</p>
<p>
^Step 1: Log into the Azure Portal.

Go to https://portal.azure.com and sign in with your Azure account credentials.

</p>
<p>
^Step 2: Navigate to Virtual Machines.

From the Azure services section on the homepage, click Virtual machines. 
</p>
<br />
<hr>
<p>
  <img width="1903" height="505" altt="Sc2" src="https://github.com/user-attachments/assets/bc8a7db9-c339-4114-88d1-ae12ccd8fcdb" /> 
</p>
<hr>
<p>
^Step 3: Copy the Public IP Address.

On the Virtual Machines page, select the VM you want to access.
Copy the Public IP address listed for the VM (e.g., 4.227.176.15).
</p>
<br />

<hr>
<p>
<img width="430" height="273" alt="Sc3" src="https://github.com/user-attachments/assets/0cca68fa-00be-4d34-9f6a-1063d0cebd72" />
  </p>
  <hr>
  <p>
 ^Step 4: Open Remote Desktop Connection.

On your local computer, click the Windows search bar in the bottom corner.
Type Remote Desktop Connection and open the app.   
  </p>
  <br />

<hr>
  <p>
 <img width="468" height="606" alt="Sc4" src="https://github.com/user-attachments/assets/27441cca-df63-4fdb-8deb-c4d5fae62938" />
  </p>
  <hr>
  <p>
 ^Step 5: Enter IP and Credentials.

In the Remote Desktop Connection window, paste the Public IP address into the Computer field.
When prompted, enter the username and password you created when setting up the VM.
Click Connect.  
  </p>
  <br />

<hr>
  <p>
 <img width="1907" height="1121" alt="Sc5" src="https://github.com/user-attachments/assets/47bf9d73-a9b4-4e05-a1ad-da6937242a03" />
   </p>
   <hr>
<p>
^Step 6: Access the Virtual Machine.

After authentication, the Remote Desktop session will launch.
The Windows VM desktop will appear, and you may see the initial setup/privacy screen.
From here, you are fully connected to your Azure Virtual Machine. 
</p>
<br />

