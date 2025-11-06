# Vitual Private Network (VPN)
<p align="center">
<img src="https://i.imgur.com/ycANIUO.jpeg" height="80%" width="80%" alt="VPN Main Image"/>
</p>

<h1>VPN - Prerequisites and Installation</h1>
This tutorial covers the prerequisites and installation process for setting up and using a VPN..<br />

<h2>Environments and Technologies Used</h2>

- A VPN (Proton VPN)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 Enterprise N</b> (22H2)

<h2>Installation Steps</h2>


<p>
Create a Resource Group in Azure, then deploy a Windows 10 Virtual Machine within it. Once the VM is set up, use Remote Desktop Protocol (RDP) to log into the VM.
</p>
<p>
<img src="https://i.imgur.com/Pd2qv7E.png" height="80%" width="80%" alt="Virtual Machine Essentials"/>
</p>
<br />


<p>
Once inside the VM, open a web browser and navigate to https://whatismyipaddress.com/. View the IP information displayed and record it in Notepad or on a piece of paper for later reference.
</p>
<p>
<img src="https://i.imgur.com/j5Gc7hS.png" height="80%" width="80%" alt="Before VPN IP"/>
</p>
<br />


<p>
On your personal computer, sign up for the free version of Proton VPN at https://account.protonvpn.com/signup?plan=free&language=en.
Inside the VM, download and install the Proton VPN client. Log in to the client using your Proton VPN credentials at 
https://account.protonvpn.com/login 
</p>
<p>
<img src="https://i.imgur.com/M9nQnKR.png" height="80%" width="80%" alt="Proton Downloads"/>
<img src="https://i.imgur.com/5MrszOi.png" height="80%" width="80%" alt="Proton Downloading"/>
</p>
<br />


<p>
Sign in to the Proton VPN client using the credentials you created during account setup. Once logged in, click "Quick Connect" to automatically connect to a VPN server. Connecting to the VPN will mask your real IP address and encrypt your internet traffic, enhancing privacy and security.
</p>
<p>
<img src="https://i.imgur.com/gK0SjHS.png" height="80%" width="80%" alt="Before Connecting"/>
</p>
<br />


<p>
Revisit https://whatismyipaddress.com/ and observe the changes in the IP information. Note how the IP now reflects the VPN server you connected to, demonstrating the VPN's effect.
</p>
<p>
<img src="https://i.imgur.com/waGXQQ1.png" height="80%" width="80%" alt="New VPN IP Address"/>
</p>
<br />
