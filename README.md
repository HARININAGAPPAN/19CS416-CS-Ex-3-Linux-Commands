Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
NAME:HARINI N
REG NUMBER: 2122223040057
Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

3.a) Installation and Configuration of Oracle VirtualBox
# Aim:
To install and configure Oracle VM VirtualBox.

# Pre-requisites:
Machine with Internet access

Minimum 4 GB RAM

Sufficient storage space

# Steps:
# 1.Download Oracle VM VirtualBox:
Visit Oracle VirtualBox Official Site

Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):
Launch Installer → Allow Changes → Click Next.

Choose Installation Options → Click Next.

Accept Network Interface Warning → Click Yes.

Click Install.

Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:
Open VirtualBox.

Click New → Name VM → Select Type (Linux/Windows) and Version.

Allocate:

Minimum 2 GB RAM

Create Virtual Hard Disk (20 GB recommended).
```

Start Virtual Machine and provide ISO to install OS.

```

Result:
Thus, Oracle VM VirtualBox was installed successfully.

3.b) Installation and Configuration of Kali Linux

# Aim:
To install and configure Kali Linux in Oracle VirtualBox.

Pre-requisites:
Oracle VM VirtualBox Installed

4 GB RAM and 20 GB Storage Minimum

Kali Linux ISO

# Steps:
1.Download Kali Linux ISO:

Visit Kali Linux Official Site

Download 64-bit ISO (Installer version).
2.Create a New Virtual Machine:

Open VirtualBox → Click New.

Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
Allocate Memory: Minimum 2 GB RAM (recommended 4 GB). 4.Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).

Choose Dynamically allocated.

Set Disk size to 20 GB or more.
5.Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali       Linux ISO.
6.Start Installation:

Boot Virtual Machine → Choose Graphical Install.

Set Language, Region, Keyboard.

Configure Network → Set Hostname (e.g., kali).

Set root password.

Disk Partitioning: Use entire disk → All files in one partition.

Install System → Install GRUB Bootloader → Finish Installation.
7.Login to Kali Linux:

Use root credentials.
8.(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox 

<img width="776" height="60" alt="image" src="https://github.com/user-attachments/assets/0da5c14a-b027-4ebc-a964-94d5973d0844" />




Snapshot 2: Kali Running in Virtual 

<img width="783" height="487" alt="image" src="https://github.com/user-attachments/assets/c0726ef1-c8c9-437d-a24a-5197a0ee54ef" />




# Result:
Thus, Kali Linux guest OS was installed and configured successfully.

# 3.c) Execution of Linux Commands in Kali
3 About Linux:
Open-source operating system.

Kernel manages communication between hardware and software.

Commands are case-sensitive.

# Commands:
ls Command The ls command is used to display a list of content of a directory.
Syntax: ls

<img width="820" height="294" alt="image" src="https://github.com/user-attachments/assets/3745a756-f8d1-4a0a-9a19-146f3d8f419d" />

# 2) pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd 

<img width="218" height="62" alt="image" src="https://github.com/user-attachments/assets/50b2aaca-da26-4b78-92de-d245297e7d78" />


# 3) mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

<img width="776" height="85" alt="image" src="https://github.com/user-attachments/assets/952aff09-3741-4cf9-a3a7-9bacd1b32108" />

# 4) rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir

<img width="756" height="98" alt="image" src="https://github.com/user-attachments/assets/7c3ec9e8-406d-4e69-9ce2-3bb0484e0d66" />

# 5) cd Command
The cd command is used to change the current directory.

Syntax: cd



# 6) cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="333" height="210" alt="image" src="https://github.com/user-attachments/assets/1326250d-bcc3-4a66-b02d-f061f30366cd" />

# 7) cp Command
The cp command is used to copy a file or directory.

Syntax: cp

<img width="312" height="136" alt="image" src="https://github.com/user-attachments/assets/014531a3-e2f3-40aa-9c10-4181a0e0de5c" />

# 8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="377" height="46" alt="image" src="https://github.com/user-attachments/assets/fcb6eedd-eebe-467e-8d04-5c57a3052e23" />

# 9) su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su

<img width="246" height="112" alt="image" src="https://github.com/user-attachments/assets/9ed9375f-c176-43a4-9014-d8346dfbb6d7" />

# 10) mv Command
The mv command is used to move a file or a directory form one location to another location.

Syntax: mv

<img width="360" height="312" alt="image" src="https://github.com/user-attachments/assets/3615f10d-7e20-4b64-968d-f36f9dced473" />

# 11) rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="455" height="205" alt="image" src="https://github.com/user-attachments/assets/762fe1c3-8275-4e28-9271-075a0bc31e6b" />

# 12) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head

<img width="410" height="654" alt="image" src="https://github.com/user-attachments/assets/5ae6219e-f00b-417f-8485-caa80a9f6d11" />


# 13) tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

<img width="290" height="285" alt="image" src="https://github.com/user-attachments/assets/16d124e3-a0e4-4968-b2b6-77a0acc93c02" />

# 14) id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="815" height="40" alt="image" src="https://github.com/user-attachments/assets/3c9f03e7-a57d-4896-b491-2a1bc04c0bef" />

# 15) grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep

<img width="339" height="75" alt="image" src="https://github.com/user-attachments/assets/9afb4474-d47b-454c-9c65-137e32a73f63" />

# 16) tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="510" height="147" alt="image" src="https://github.com/user-attachments/assets/4b257b53-36ef-460e-a9ed-e6329ba34a15" />

# 17) chmod Command
The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<file_name>

# 18) tar Command The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved] $ tar xvzf file.tar *.c

<img width="372" height="188" alt="image" src="https://github.com/user-attachments/assets/090a169d-049b-49b4-9625-1068fb67d823" />

# 19) chown Command
The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="285" height="277" alt="image" src="https://github.com/user-attachments/assets/62d0cd86-ca72-40cd-93ee-2a42766ae4f3" />

# 20) make Command
The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="247" height="70" alt="image" src="https://github.com/user-attachments/assets/9ffc213e-4712-4e8d-a6fe-9cbaed8c88d8" />


# 21) ifconfig Command
The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="539" height="138" alt="image" src="https://github.com/user-attachments/assets/ceec16c4-b1fd-4b07-8958-ab603698212e" />

# 22) chmod 777 Command
The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name $chmod -R 777 /path/to/file/or/folder

<img width="554" height="112" alt="image" src="https://github.com/user-attachments/assets/1ae0a5c7-a604-4065-8d6e-d535d3ac4a47" />

# 23) host Command
The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host or

<img width="732" height="86" alt="image" src="https://github.com/user-attachments/assets/ed49f312-f73d-4fad-a9b7-17ffc5e580b3" />

# 24) gzip Command
The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip ..

# 25) sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort

<img width="235" height="369" alt="image" src="https://github.com/user-attachments/assets/cbba15fa-b2da-4de0-8993-be5c8be3913d" />

# 26) cal Command
The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="288" height="234" alt="image" src="https://github.com/user-attachments/assets/b225248d-60a4-4df1-af29-97f2526e96ed" />

# 27) clear Command
Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="560" height="627" alt="image" src="https://github.com/user-attachments/assets/cc362f6d-99fc-4038-9103-5b995a09772f" />

<img width="362" height="181" alt="image" src="https://github.com/user-attachments/assets/c6427aea-a8ae-4f73-9167-67b31839941a" />


# 28) mail Command
The mail command is used to send emails from the command line.

Syntax: mail -s "Subject"

<img width="548" height="53" alt="image" src="https://github.com/user-attachments/assets/bd443863-96c7-428a-90bf-48199f347496" />

# 29) df Command
The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="549" height="175" alt="image" src="https://github.com/user-attachments/assets/2387ac1d-1c21-406e-ac84-4e60b9c9b08c" />

# 30) find Command
The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="330" height="107" alt="image" src="https://github.com/user-attachments/assets/44baba23-9938-44f3-88de-3fcf221f65c2" />

<img width="368" height="69" alt="image" src="https://github.com/user-attachments/assets/23ca86b9-4b24-408a-b852-eb870b93b6e1" />


# Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.
