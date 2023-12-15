# File-Share-and-Permissions

Needed tools and prerequisites to installing VMs
<p align="center">
<img width="700" height="300" src="https://i.imgur.com/1KYZw7l.png" alt="2 VMs pining"/>
</p>

<h1>File Share and Permissions - Prerequisites and Installation</h1>

<h2>Video Demonstration</h2>

- <h3><a href="https://youtu.be/n4alBjAxGkI" target="_blank_">YouTube: Connecting PCs together and sharing files over the network</a></h3>

<h2>Environments and Technologies Used</h2>

- VM Virtual Box/ Hyper-V (Virtual Machines/Compute)
- Windows 10 ISO
- If VM Virtual BOx, you will need the Guest Addition - To avoid hiccups and delays

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Prerequisites</h2>

<p>This tutorial outlines the prerequisites and installation of:</p>
<ul>
  <li>The windows 10 operating system</li>
  <li>Creating users and user groups</li>
  <li>Setting up file permissions on a NTFS formatted drive</li>
  <li>Sharing this folder on the network</li>
  <li>Installing the VM Virtual Box <a href="[​All supported platforms](https://download.virtualbox.org/virtualbox/7.0.12/Oracle_VM_VirtualBox_Extension_Pack-7.0.12.vbox-extpack)">Guest Addition</a></li>
  <li>Creating a Mapped drive of the folder shared on the network for easy access</li>
</ul>

-(Create Virtual Machines in Virtual Box and adding the Guest addition or creating it in Hyper-V)
-(Adequate memory available for running Two Virtual Machines)

File Permissions

Your going to need to download ;
VirtualBox 7.0.12 Oracle VM VirtualBox Extension Pack
Download VirtualBox


- Open VM Virtual Box (select new, create your VM resources such as memory, HDD, add your ISO image, add your network adapter for internal VMs, configure the settings before starting the VM) This will create a starter point for a smooth process.

- Start your VM (go through the windows 10 installation process)

- Run the guest addition for smooth operation of the VM
- Create a folder in the C: drive
- Go to properties on that folder, setup sharing allowing everyone access, then go on Security and setup your NTFS permissions to allow users or groups
- Implement IPv4 address 192.168.10.1 on the first pc and 192.168.10.2 on the second pc
- Ping both PCs to make sure they are connected
- Go to your network shares and you should see the folder that was shared
- Right click the folder and choose Map network drive


If done right, CONGRATULATIONS!! You setup everything and you can collaborate or share files and folders easier


