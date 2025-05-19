# Virtualization
## AIM :
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.
## 3.a) Installation and Configuration of Oracle VirtualBox:
## AIM
To install and configure Oracle VM VirtualBox.
##Pre-requisites:
 1.Machine with Internet access
 2.Minimum 4 GB RAM
 3.Sufficient storage space
 ## SREPS :
 ### 1.Download Oracle VM VirtualBox:

 1.Visit Oracle VirtualBox Official Site
 2.  Download installer for your OS (Windows/macOS/Linux).
### 2.Install Oracle VM VirtualBox (Example: Windows):

1.Launch Installer → Allow Changes → Click Next.
2.Choose Installation Options → Click Next.
3.Accept Network Interface Warning → Click Yes.
4.Click Install.
5.Finish Installation and Launch VirtualBox.
### 3.Configure VirtualBox:

1.Open VirtualBox.
2.Click New → Name VM → Select Type (Linux/Windows) and Version.
3.Allocate:
*Minimum 2 GB RAM
*Create Virtual Hard Disk (20 GB recommended).
4.Start Virtual Machine and provide ISO to install OS.
###  RESULT:
Thus, Oracle VM VirtualBox was installed successfully.
### 3.b) Installation and Configuration of Kali Linux
### AIM:
To install and configure Kali Linux in Oracle VirtualBox.
### PRE REQUISITES:
1.Oracle VM VirtualBox Installed
2.4 GB RAM and 20 GB Storage Minimum
3.Kali Linux ISO image
### STEPS:
1.Download Kali Linux ISO:

*Visit Kali Linux Official Site
*Download 64-bit ISO (Installer version).
2.Create a New Virtual Machine:

*Open VirtualBox → Click New.
*Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
3.Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).
4.Create Virtual Hard Disk:

*Select VDI (VirtualBox Disk Image).
*Choose Dynamically allocated.
*Set Disk size to 20 GB or more.
5.Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
6.Start Installation:

*Boot Virtual Machine → Choose Graphical Install.
*Set Language, Region, Keyboard.
*Configure Network → Set Hostname (e.g., kali).
*Set root password.
*Disk Partitioning: Use entire disk → All files in one partition.
*Install System → Install GRUB Bootloader → Finish Installation.
7.Login to Kali Linux:

Use root credentials.
8.(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
### SNAPSHOTS :
![440120436-737dafde-fd5d-4266-849a-a12013ce9c5b](https://github.com/user-attachments/assets/be41995e-7ab5-4464-aaf5-bfcd54a583fd)
![440120616-6b08c65e-e2c0-4f8e-a782-0914a3470759](https://github.com/user-attachments/assets/fd36559f-f633-4a76-9098-4bbe8ad23e78)
### RESULT:
Thus, Kali Linux guest OS was installed and configured successfully
### 3.c) Execution of Linux Commands in Kali:
### About Linux:
1.Open-source operating system.
2.Kernel manages communication between hardware and software.
3.Commands are case-sensitive.
### Linux Commands:
ls Command

The ls command is used to display a list of content of a directory.

Syntax:
ls


![440122167-65cbb685-53e1-4d50-b109-2d3a73e366dc](https://github.com/user-attachments/assets/c479a012-95bc-4685-86ff-8271f71ebb6c)


2.pwd Command

The pwd command is used to display the location of the current working directory.

Syntax:
pwd


![440120811-06a87e8c-9f1f-4f33-9c75-d9a5f75c8d60](https://github.com/user-attachments/assets/e4671627-d177-4ae5-b6cf-cec2cde6b97d)


3.mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax:
mkdir <directory_name>


![440120918-1b1790eb-a58c-4bbb-a2b7-ee9ab6051a93](https://github.com/user-attachments/assets/7388075c-edce-4e5b-9ca1-7a14d438159c)


4.rmdir Command

The rmdir command is used to delete a directory.

Syntax:
rmdir <directory_name>


![440120963-5002fe8b-4414-42d0-8519-3d1f452fbafb](https://github.com/user-attachments/assets/5b495804-78a0-455d-b5aa-f340883d2bb3)


5.cd Command The cd command is used to change the current directory
Syntax:
cd <directory_name>


![440121083-84cead37-3512-4e54-8884-427cb99b15fc](https://github.com/user-attachments/assets/94497d69-6f00-4f1d-9d77-24d6544c6283)


6.cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

Syntax:
cat [options] [file_name]


![440121465-2361932b-99fc-4118-9097-bd9bdce384f0](https://github.com/user-attachments/assets/093cd3d6-95fe-416f-9db4-e75b92fc562e)


![440121476-4c6d451f-4bfc-48f1-b4cd-0217fef9e06c](https://github.com/user-attachments/assets/7e217ccd-a672-4c48-b34b-8db82cbcd1c5)


7.cp Command

The cp command is used to copy a file or directory.

Syntax:
cp [source] [destination]


![440121533-4e377a91-23d4-4169-a66b-f88af203a60b](https://github.com/user-attachments/assets/7ed3a3bc-00fc-4c50-bbaa-2b3b029095d3)


![440121580-1edbd41c-31c2-4a94-8e7f-be35155e35e5](https://github.com/user-attachments/assets/443fc685-952e-4299-8ccc-7cb7f353abea)



8.mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax:
mv
[source] [destination]



![440121624-fd4832ba-1dad-45a7-a213-a5f28ca508db](https://github.com/user-attachments/assets/c127cf26-b491-403c-908c-ba65cb732642)



![440121653-16138df9-da4a-4070-a936-29f251178773](https://github.com/user-attachments/assets/8d4caca2-b43e-4f01-b691-3704608d33bb)



9.touch Command

Create empty file.

Syntax:
touch [filename]


![440121709-0ee05807-fe42-4579-a1bf-6562904fd7b1](https://github.com/user-attachments/assets/2ff97b5e-a62a-4caf-871c-b59089515385)


10.vi Command

Edit file contents using editor.

Syntax:
vi [filename]


![440121931-77ca13f3-45d7-4da6-88af-cdd2e280f41b](https://github.com/user-attachments/assets/5429fdfc-c4e0-4c21-88ae-a60129217ef3)


### Result::
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.










