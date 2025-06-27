<p align="center">
<img src="https://i.imgur.com/crwTViG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h1>VPN - VPN Setup and Usage (Proton VPN)</h1>
In this lab we're going to make a free account on Proton VPN on our personal computers, then test VPN connection through a virtual machine. We're also going to observe different websites and see if there's anything different with the sites based on our VPN server.
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Proton VPN Steps</h2>

- Create Proton account
- Create VM in Azure
- Download Proton on VM


<h2>Proton VPN Lab</h2>

<p>
<img src="https://i.imgur.com/CyVYy7z.png"/>
</p>
<p>
- First log into Azure and create a new virtual machine
</p> - Create new Resource Group called vpn-test 
</p> - VM Name: vpn-test-win10 > Region: East US2
</p> - Image: Windows 10 Pro
</p> - Size: Standard_D2s_v3 - 2vcpus
</p> - Then create username and password that's easy to remember > Make sure you check the licensing box > Review + Create
</p>
<br />

<p>
<img src="https://i.imgur.com/zIP2rL4.png"/> <img src="https://i.imgur.com/EmOjKvT.png"/>
</p>
<p>
- Log into the virtual machine with your vm's public IP address we just created 
</p> - Then browse to: https://whatismyipaddress.com/ > Make note of your current IP address information
</p>
<br />

<p>
<img src="https://i.imgur.com/o74AnUX.png"/> <img src="https://i.imgur.com/HBxYX4I.png"/>
</p>
<p>
- On your personal computer (not VM) sign up for a free version of Proton VPN
</p> - Then back inside your VM browse to Proton VPN + log in > Download Proton for windows
</p>
<br />

<p>
<img src="https://i.imgur.com/CniEXwp.png"/> <img src="https://i.imgur.com/JtHaVdH.png"/>
- Once Proton VPN is installed open the app + log in 
</p> - Then select "Connect" and you should receive a VPN from another country
</p>
<br />

<p>
<img src="https://i.imgur.com/TKl5I7T.png"/> <img src="https://i.imgur.com/3GoUnxd.jpeg"/>
</p>
<p>
- Browse back to: https://whatismyipaddress.com/ > Observe and make note of new IP address information 
</p> - Experiment a little by searching websites like Google, Disney, Amazon, or Netflix and make note of the different layout of the webistes
</p>
<br />
