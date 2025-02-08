# Operating System : Linux
![image](https://github.com/user-attachments/assets/22dfef4d-6546-44bb-a669-491806b60d2a)

Hello Folks, Welcome to this Learn-Linux repository! This repo will contain the Linux and Networking commands used in the projects and indusrey. We'll go step by step, and all the realed stuff would be here in this repo. And we'll conduct the learning sessions at [GrowIn Community](https://discord.com/invite/SXqTuNBm4Z) discord server.

## Introduction

The Linux Operating System is a type of operating system that is similar to Unix, and it is built upon the Linux Kernel. The Linux Kernel is like the brain of the operating system because it manages how the computer interacts with its hardware and resources. It makes sure everything works smoothly and efficiently. But the Linux Kernel alone is not enough to make a complete operating system. 
To create a full and functional system, the Linux Kernel is combined with a collection of software packages and utilities, which are together called Linux distributions. These distributions make the Linux Operating System ready for users to run their applications and perform tasks on their computers securely and effectively. Linux distributions come in different flavors, each tailored to suit the specific needs and preferences of users.

-------------------------------
### Day-1
* Why Linux
* What is the scope of Linux in the Industry.
* What are the roles you can work after having knowledge of Linux.
### Day-2
1. Linux Flavours and Distributors
   * Some distributions, such as Fedora and Red Hat Enterprise Linux from Red Hat, openSUSE from SUSE, Ubuntu from Canonical, and Oracle Linux from Oracle, are commercial, while others, such as Debian and Slackware, are community-developed.
3. VMware
4. Installation
---------------
### Day-3: 
## Learn 4 Ways to create a file:

1. Using the touch Command
* Syntax: touch filename
* Example: touch myfile.txt
* Description: This creates an empty file if it does not exist. If the file already exists, it updates the file's timestamp.
  
2. Using Redirection (> or >>)
* Syntax: > filename or echo "text" > filename
* Example:
* > myfile.txt (creates an empty file)
* echo "Hello, world!" > myfile.txt (creates the file with the specified content)
* Description: The redirection operator (>) creates or overwrites a file, while (>>) appends content to the file.
  
3. Using the cat Command
* Syntax: ```cat > filename
          ```
* Example
  ```cat > myfile.txt
     Hello, Linux!
     [Ctrl+D]
  ```
* Description: Allows you to create a file and directly input text into it. Use Ctrl+D to save and exit.

4. 4. Using a Text Editor
* Examples: ```nano filename``` (Nano editor)
* ```vi filename``` or ```vim filename``` (Vim editor)
* gedit filename (GUI-based editor for desktop environments)
* Description: Opens the specified file in a text editor. If the file does not exist, it is created.

---------------
### Resources:
[Learn Linux Fater: Blog](https://www.linkedin.com/pulse/learn-linux-faster-50-actionable-tasks-pros-devops-dipu-singh--igvlf/?trackingId=CA4kA5WPSCqq0jpIyZd6SA%3D%3D)

-------------
## Other industry used commands:
### 1. SCP Command
   * The scp (Secure Copy Protocol) command in Linux is used to securely transfer files between a local machine and a remote server (or between two remote servers) over SSH (Secure Shell). It ensures encrypted file transfer, making it safer than traditional cp or ftp.

#### Common Use Cases
1. Copy a file from local to remote
   ```
   scp file.txt user@remote_host:/path/to/destination/
   ```
2. Copy a file from remote to local
   ```
   scp user@remote_host:/path/to/file.txt /local/destination/
   ```
3. Copy a directory recursively
   ```
   scp -r local_folder user@remote_host:/remote/destination/
   ```
4. Copy between two remote servers (without downloading locally)
   ```
   scp user1@remote1:/path/to/file user2@remote2:/path/to/destination
   ```
