# Deploying-Active-Directory
Active Directory Domain Services Deployment


<p align="center">
<img src="https://user-images.githubusercontent.com/126700220/226635953-574a772b-a2d4-4f68-8c49-cb06d0d6b3e7.png"/>
</p>

<h1>Topology.</h1>
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Wireshark
- Powershell ISE
- Active Directory Domain Services
- Service Manager
- Active Directory Users and Computers
- Windows Server for Domain Controller

Quick Note: 
-DC=Domain Controller
-VM=Virtual Machine
-ICMP=Internet Control Message Protocol
-DS=Domain Service


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Windows 11 PC

<h2>Screenshots for my project.</h2>
In this project, I used Azure to create two virtual machines. 
On one machine, I created a Domain Controller. On the other machine, I created a client to act as a user.
Enjoy the slides.

<h2>Screenshots of Steps</h2>

<p>
<img src="https://user-images.githubusercontent.com/126700220/226637964-7f469d2f-d6b5-4f13-8ae7-c7ba588e5325.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
Created a resource group. Note the name of the Resource Group. 
<p>
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/226638313-6fe46d8a-1e41-4766-a978-31b6b8e1377e.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
Created a Domain Controller virtual machine. Used the Windows Server feature.
<p>
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/226638644-70f9ed19-c260-4887-a4bd-7c4b9170e95c.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
Created client virtual machine.
<p>
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/226639070-3f71be4d-91f6-4dd9-8746-24b505c08b18.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
Changed the Domain Controller's IP address to static.  
<p>
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/226639541-0c3b908a-500f-45bf-a6ce-aa03a1cbed55.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
I verified connectivity between the DC and the client via Network Watcher Topology. Check out my other lab tutorial on Topology. 
<p>
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/126700220/226640076-ee6b8106-f910-4c90-a474-2dade7856b34.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
Remoted into the client VM. I did this to test the ICMP (Internet Control Message Protocol) to the DC (Domain Controller).
<p>
</p>
<br />

Thank you for looking at my work.
