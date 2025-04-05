---
layout: archive
title: "Getting Started"
permalink: /getting-started/
author_profile: true
redirect from:
  - /start
---

{% include base_path %}

Getting Started With the CLI
======

Necessary Materials & Resources
------
* Google Slides Presentation: [How to Use the Command Line](https://docs.google.com/presentation/d/17vu6vvsbNUQ65irCu921e1luyEiU92aWmMy_3Yjzrxc/edit?usp=sharing).
* Online emulated Linux environment: [JSLinux](https://bellard.org/jslinux/).
* Online step-by-step demo: [BanditLabs](https://overthewire.org/wargames/bandit/).


Step-by-Step Set Up Guide for JSLinux
------
1. Open the link for JSLinux in a new tab.
2. For the option "Alpine Linux 3.12.0 - Console", hit the "Click here" button. This will open the emulated environment that oyu can work within. The window is expandable, so make sure to adjust it to a comfortable width for working!
*You can now run most Unix CLI command in this window! In order to continue with the demo, follow these next set of steps. However, if you wanted to play with it yourself, stop here.*
3. Create a new directory, name it something line "CLI Demo".
4. Move into that new directory.
5. Run the following script:
	wget https://t3-ciders.gitlab.io/files/unix-demo-hs.tar.gz
*This downloaded the preset demonstration that has been created for the workshop. It is mostly a collection of files and directories to be played with later.*
6. Run the following script:
	tar xvf unix-demo-hs.tar.gz
*This unzipped that file so you can access those files and directories for the remainder of the time!

**Do not close the JSLinux window during the duration of the workshop or intended use. It will not save your progress, and you will have to restart.**


Necessary Unix CLI Commands
======

Basic Navigation
------
pwd – Print working directory (shows current location).  
ls – List files in the directory.  
ls -a – Show hidden files.  
ls -l – Show detailed file info.  
cd [directory] – Change directory.  
cd .. – Move up one level.  
cd ~ – Go to home directory.  


File & Directory Manipulation
------
mkdir [dir] – Create a new directory.  
cp [source] [destination] – Copy a file or directory.  
cp -r [dir] [new_dir] – Copy an entire directory.  
mv [source] [destination] – Move or rename a file/directory.  
rm [file] – Delete a file.  
rm -r [dir] – Remove a directory and its contents.  


File Interaction
------
cat [file] – Display file contents.  
head [file] – Show the first 10 lines of a file.  
tail [file] – Show the last 10 lines of a file.  
echo "text" – Print text to the terminal.  
touch [file] – Create a new empty file.  


Searching & Processing Files
------
grep "text" [file] – Search for text in a file.  
find [path] -name "filename" – Search for a file by name.  
sort [file] – Sort lines in a file.  
uniq [file] – Remove duplicate lines.  
diff [file1] [file2] – Compare two files.  
	* -q - Outputs only when the files differ.
	* -s - Outputs when the files are the same.


Remote Access / Secure Shell (SSH) Connection
------
ssh [user]@[server] -p [port] – Securely connect to a remote server.  


Quick Tips
------
Use Tab to auto-complete file/directory names.  
Use clear to clear the screen.
Use exit to end an SSH connection.
Use the up/down arrows to navigate the terminal.

