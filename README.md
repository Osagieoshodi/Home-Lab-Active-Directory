# Home-Lab-Active-Directory-Structure

In this project

I set up a basic home lab running Active Directory while using Oracle VirtualBox:

Installed Oracle VirtualBox: 
Downloaded and installed Oracle VirtualBox, this virtualization software allows me to create and manage virtual machines (VMs) on my computer.

Downloaded Windows Server ISO: 
Downloaded Windows Server ISO image from the Microsoft website to install the operating system on the virtual machine.

Created a Virtual Machine:
Created a new virtual machine from the VirtualBox and configured the settings, including assigning sufficient resources (CPU, RAM, storage) for the VM.

Installed Windows Server: 
Attached the Windows Server ISO to the virtual machine's virtual optical drive and powered the VM, the Windows Server installation on the VM was successful.

Set Up Network: 
Configured network settings for the VM.

Configure Static IP: 
Assigned a static IP address to the virtual machine within the home network's IP range.

Installed Active Directory Domain Services (AD DS): 
Using the Server Manager, installed Active Directory Domain Services role on the Windows Server VM. 

Created a Domain: 
Defined a new Active Directory domain.

Created Organizational Units (OUs): 
Organize the Active Directory structure by creating organizational units to represent different departments, teams, or functions.

Created User Accounts and Groups: 
Added user accounts and groups to the Active Directory domain, which allowed me to manage access and permissions within the lab environment.

Tested the Active Directory: 
Join a separate Windows client virtual machine to the just created domain, which validates the Active Directory is functioning correctly, and that domain authentication is working.

Added Group Policy: 
Created and applied Group Policy objects (GPOs) to manage and enforce settings on domain-joined computers. This helps you understand how Group Policy works in a controlled environment.

![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/3d2e6ca5-db01-4ced-be4c-8b1c0320ed6d)

# CREATED VIRTUALBOX-VM
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/62dda123-6523-4ac4-bad0-6e5122691ff3)

# WINDOWS SERVER SETUP:
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/71687750-4f2a-4c34-a9a4-d67e38699ceb)

# VirtualBox_CLIENT_Windows-10-Server-ISO
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/55e74e85-a64d-4fa9-929f-f0f263937c2b)

# INSTALLING WINDOWS 10-ISO-VIRTUALBOX
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/421249fb-1c0c-4e32-af29-61b37cc1b37a)

# FULLY INSTALLED WINDOWS 10
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/1db1d9ff-ee98-49b8-9f2c-ffb3088154e8)

# ADMINISTRATOR LOGIN
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/d19611ef-b060-4e1a-8b7a-52e605ab9555)

# ADDED ACTIVE DIRECTORY USER TO GROUP
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/5273e608-83d2-4187-860f-d6e421261cef)

# CREATED USER GROUP-ACTIVE DIRECTORY
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/4e3ef5b9-bd4e-46dd-a1bf-9381b8f008bf)

# ADMINISTRATOR-LOGIN-CLIENT-VM
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/28658411-c10b-4209-bfd6-d3a1d6e18615)

# DELETING USER
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/cde430aa-f036-4e3f-9102-d3baee000ec2)

# LOG IN THE NEW USER
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/35872d03-669f-424e-bfaf-11aff384273f)

# RESET USER PASSWORD - ACTIVE DIRECTORY
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/24bf6eaa-147f-40ad-8107-a40f9fede255)

# SHARE FOLDER
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/4372f5e4-53f1-43e7-a6e3-afca6bf1b83a)

# RESET USER PASSWORD-ACTIVE DIRECTORY
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/7cf2e39e-7794-441d-8b79-bd50811c4752)

# ADDED ROUTER-VIRTUALBOX_DC
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/9618d3f5-8bbc-4ce6-bc5c-bfa7c4da8555)

# PING GOOGLE-TEST FOR INTERNET
![image](https://github.com/Osagieoshodi/Home-Lab-Active-Directory/assets/141954663/e844dcaf-75cb-405d-881a-78ee572d1e9e)
