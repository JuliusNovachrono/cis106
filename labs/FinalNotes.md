##### Arnaldo Jara

##### Professor Alberto

##### CIS-106-RE1

# Final Notes

<!-- TOC -->
* [Notes Lecture 1 What is Linux](#notes-lecture-1-what-is-linux)
    - [Why Do you need to learn linux?](#why-do-you-need-to-learn-linux)
    - [What is Linux?](#what-is-linux)
    - [Linux books I can use:](#linux-books-i-can-use)
    - [Linux distributions](#linux-distributions)
    - [Linux Architecture](#linux-architecture)
    - [Software licensing agreement](#software-licensing-agreement)
    - [The 4 freedoms](#the-4-freedoms)
    - [Learn more:​  https://www.gnu.org/philosophy/free-sw.en.html](#learn-more​--httpswwwgnuorgphilosophyfree-swenhtml)
    - [Advantages/Disadvantages of Open Source software](#advantagesdisadvantages-of-open-source-software)
    - [What is Ubuntu (Notes Lecture 1)?](#what-is-ubuntu-notes-lecture-1)
* [Notes Lecture 2: Installing Ubuntu](#notes-lecture-2-installing-ubuntu)
    - [What is Virtualization?](#what-is-virtualization)
    - [Using Virtualbox?](#using-virtualbox)
    - [Installing Ubuntu In a virtual machine:](#installing-ubuntu-in-a-virtual-machine)
* [Notes Lecture 3: Learning the Bash shell](#notes-lecture-3-learning-the-bash-shell)
    - [Exploring Desktop Environments](#exploring-desktop-environments)
    - [What is a Shell?](#what-is-a-shell)
    - [Managing Software](#managing-software)
    - [The Linux filesystem](#the-linux-filesystem)
* [Notes Lecture 4: Manipulating files and directories](#notes-lecture-4-manipulating-files-and-directories)
    - [Managing files and directories](#managing-files-and-directories)
    - [Getting help](#getting-help)
    - [Working with wildcards](#working-with-wildcards)
    - [Shell Expansion](#shell-expansion)
* [Notes Lecture 5: Command Line text editors](#notes-lecture-5-command-line-text-editors)
    - [The Basics of Nano](#the-basics-of-nano)
    - [The Basics of Vim](#the-basics-of-vim)
* [Notes Lecture 6: Managing Data and File permissions](#notes-lecture-6-managing-data-and-file-permissions)
    - [Managing data](#managing-data)
    - [File permissions](#file-permissions)<!-- /TOC -->

# Notes Lecture 1 What is Linux

## Why Do you need to learn linux?
* Linux runs in a lot of devices. Example: laptops, desktops, servers, smartphones, IoT devices, etc
* Linux powers the cloud
* Linux is used by a lot of companies even Microsoft

## What is Linux?
* Linux is a kernel. A kernel is the core of any operating system.
* An operating system that uses the Linux kernel is called a Linux Distribution. Example: Ubuntu and Android.
* Linux is multitasking, multi-user, and multipurpose OS.
* Linux is a modular operating system.

## Linux books I can use:
* Linux Administration A Beginner's Guide 8th Edition by Wale Soyinka
* CompTia Linux+ Study Guide by  Christine Bresnahan
* The Linux Command Line by William Shotts

## Linux distributions
![imglk](/imgs/FinalPics/imgLK.png)
* There are a large number of Linux distributions.
* There are two main Linux Distributions:
    ○ Debian
    ○ Redhat
* There are also other independent distributions:
    ○ Slackware
    ○ Arch
    ○ Gentoo
## Linux Architecture
![imgLA](/imgs/FinalPics/imgLA.png)
* Linux is modular which means that users can remove and add/remove whatever they need or don't need.
    ○ Kernel ​= the core of the operating system. Manages the hardware.
    ○ Daemons​ = background programs that run independent of the user.
    ○ Shells​ = the interface that accepts user input and translates it so that the kernel can use it.
    ○ Graphical Desktop Environmen​t = a collection of software that makes the graphical interface.
* In Linux everything is a file.
* Type of files:
  ○ Device files
  ○ Directory files
  ○ Binary files
  ○ Regular files
## Software licensing agreement
* A license agreement outlines the rights a user has to a given software
* Types of licensing agreement:
  
  Open source | Closed source | Free software
  ------------|---------------|--------------
  Software can be distributed for freeor a fee. The source code must be distributedwith the software. |  Software can be distributed for freeor a fee. ​The end user has limitedaccess to the software and thesource code is not available. | Software can be distributed for freeor a fee. The user has total control ofthe software and the source code.The software must comply with the 4 freedoms.
![imgOC](/imgs/FinalPics/imgOC.png)
#### The 4 freedoms
* Freedom 0: the user can run the program as you wish, for any purpose .
* Freedom 1: the user can  study how the program works, and change it.
* Freedom 2: the user can  redistribute copies.
* Freedom 3: the user can distribute copies of your modified versions.
#### Learn more:​  https://www.gnu.org/philosophy/free-sw.en.html


## Advantages/Disadvantages of Open Source software
![imgAD](/imgs/FinalPics/imgAD.png)
## What is Ubuntu (Notes Lecture 1)?
* Ubuntu is a free open source Linux distribution based on Debian.
* It is considered one of the best secure operating systems on linux, and includes superb professional support.
* Since Ubuntu is open source it can be customized to meet any users needs, Ubuntu is simply very flexible!
* Ubuntu is also not just used as a front end desktop envronment, it is also used to manage backend servers.

# Notes Lecture 2: Installing Ubuntu

## What is Virtualization?
* There are two types of virtualization:
  - server side virtualization - uses software to provide a virtual desktop to the users / clients (service is provided from a web server)
  - client side virtualization - uses software that allows a user to use virtual machines (service is provided from the clients computer)
* The best benefit of virtualization is the ability to run multiple operating systems on one computer. 
* One can run two or more operating systems simultaneously by using the host or main operating system and turning on other virtual machines at the same time.
* A benefit to having a virtual machine is also the ability to test programs or scripts on the VM before running on your main operating system. 

## Using Virtualbox?
* Virtualbox is an open source virtualization software provided by oracle.
* It can run on any major operating system.
  
## Installing Ubuntu In a virtual machine:
* To use a virtual machine ones computer must have the following:
  - AMD or Intel or M1 processor (minimum dual core)
  - 4 gb of ram
  - a decent size of storage (10gb minimum) 
* If minimum requirements are met head to https://www.virtualbox.org/wiki/Downloads

# Notes Lecture 3: Learning the Bash shell

## Exploring Desktop Environments
* A modern desktop environment has a graphical user interface, which is a visual interface that makes the operating system act more interactive. Something like windows, macOS and ubuntu are graphical desktop environments. The desktop environment allows the user to have a lower entry level of computer knowledge.(more user friendly the CLI)
* Before the desktop environment the command line interface was used to operate the computer.(CLI was used by dinosaurs) but today it is updated and can efficiently run many complex commands. 
* Unlike windows or macOS Linux has an abundance of GUI 
* Examples of Linux desktop environments are as follows:
  - GNOME
  - Cinnamon
  - KDE
  - LXDE
  - Flux box
  - and many more!
* One desktop environment isn't necessarily better than another. One should decide which one they feel most comfortable with, Unless one is restricted to use a DE due to work or school preference. 
## What is a Shell?
* The shell or the bash shell is an semi-interactive program that allows access to the OS of linux.
* Its a program that requires certain knowledge of basic commands at minimum. (the entry level is moderate) Its similar to coding html, css, or MySQL but they don't have much in common.  
* The shell is simple to use. (to move around you only need to move around using the arrow keys, but there are other commands to move around if one desires to learn) I personally like using the arrow keys since I don't run large commands on linux.
* Two useful basic commands are clear & free. Clearing the screen every once in a while wile working on the shell helps organizing the screen (my preference). The second command that is efficient is the free to quickly display free storage on computer or VM. 
* TIP!!: You can always re run or pull up used commands by using the up and down arrow key.

## Managing Software
* A great package managing software on Linux is the Debian Package Management system. (It comes preloaded on all debian distributions)
* DPMS uses an application called dpkg, which works on the back end to manage files.
* The better option in my opinion is the APT package
* The APT or Advanced Package tool is used to handle software installations, getting updates, handling dependencies, and resuming to run packages after system shut down.  
* common commands used after apt are:
  - get
  - cache
  - install
  - update
  - clean
  - remove
  - upgrade
* APT is used very frequently by Linux users due to these benefits.

## The Linux filesystem
* The Linux file system refers to the way files are archived and organized in the directories on Linux.
* The root is the main directory or core directory, containing files of the operating system. (The root directory acts as the first branch of the directory tree or structure,(Think of it as the father of all other directories))
*  This tree is called the FHS or the file system directory. FHS are a set of rules on how files are structured.
*  A directory contains sub directories and one has to open a path to enter sub directories. (If C is in B and B is in A, one would have to create a path from A to B then C ~/A/B/C/)
*  The following is a visual representation of the directory structure beggining from root:
* ![x](/imgs/FinalPics/root.png) 

# Notes Lecture 4: Manipulating files and directories

## Managing files and directories
* The most used command for creating single or many directories on a single command is "mkdir".
* To create a single directory on simply uses:
  - mkdir newDirectoryName (mkdir followed by the name of the new directory)
* To create more than one simply enter the name of another new directory separated by a space or null value.
* To create sub directories use mkdir followed the name of the directory than in brackets enter the sub directories separated by a comma.
  - mkdir newDirectory {subD1, subD2, subD3}
* To create files we use the "touch" command separated by the name of the file.
* You can also add an extension to the file, such as pdf, txt , py, cpp etc... 
* An example of creating a text file in current directory:
  - touch file.txt
* Example creating the same file but in a specific directory:
  - touch NewFiles / file.txt
* You can also use quotation marks "" to make file with a string name.
* The "rm" command followed by the -r option is used to remove files or directories. rm alone can only delete files.
* The "mv" command is used to move files from one directory to another. 
  - mv file1 DocumentsDirectory
* mv can also be used to rename files 
  - mv filename.txt newFileName.txt
* The "cp" command is used to copy files, from one place to another. Using the -r option lets us copy directories as well.
* The following command will copy directory A to directory B.
  - cp -r directoryA directoryB
* 
## Getting help
○ "man" The manual page also known as the man page. Is used to pull up the manual of a specific command. Commands such as ls or the list command. All you need to type is 5 letters (man ls). The other option is google lol.

## Working with wildcards
○ Wild cards are used to represent a single character or even multiple. The ? question mark symbol is used to represent any single character. The * ass symbol is used to represent any amount of characters before or after the symbol. 
○ If you would like to list all txt files in the home directory you would enter (ls *.txt). Wild cards are used in majority of programming languages to increase efficiency.
## Shell Expansion
○ the brace expansion is used to include many files or directories grouped together inside of the brackets {}.

# Notes Lecture 5: Command Line text editors
 
## The Basics of Nano
* Nano is a very basic and efficient text editor used to create, save, and add logs of the outputs on the terminal and create other types of files. 
* Nano is usually pre installed with most linux distributions. All one has to do is type nano into the terminal to activate text editor. Nano will activate on your current directory.
* The following are basic commands on nano:
* ![x](/imgs/FinalPics/nano.png)

## The Basics of Vim
* Vim unlike nano is not pre installed and will have to be downloaded.
  - to simply install type the following: 
  - > sudo apt install vim
* Vim unlike nano is not very basic and dull, it has many modern features integrated into the app, It can do everything nano can do and much more.
* Vim includes many features such as spell check., merging, unicode, scripting languages supported, plugins,and SYNTAX HIGHLIGHTING!!
* To start vim simply type vim into the terminal. Followed by the letter "i" to enter into insert mode. 
* To enter command line on vim enter this symbol with the two little dots that I forgot what it's called --> :
* To save enter   :w
* To quit enter   :q
* To create a file enter vim followed by the name of the new file: 
* > vim hello.txt
* To open an existing file type :e followed by name of file.
* To navigate through vim file use:
* k for up
* j for down
* h for left
* l for right
* yw to copy a word
* yy to copy a line 
* x to cut
* u to undo
* As you can see vim is clearly superior in every aspect.

# Notes Lecture 6: Managing Data and File permissions

## Managing data
* One of the best ways to manage simple data is by creating archives of directories or files.
* Tools such as Tar are used for creating archives, extracting and much more
* An example of using tar:
> tar options file.tar archivedFile
* tar is followed by an option like the one's bellow:
* ![](/imgs/FinalPics/tar.png)
* Then the tar file followed by the other file that you want to alter 
* Another useful tool for managing data is CPIO,  lets us restore and copy directories as well.
* The third tool used is Ar.  
* I personally prefer tar but the others work great as well.
* Another way to mange data is by "file compression".
* There is many file compression tools out there like gzip, xz, bzip2, zip, 7zip, and rar.
* I personally prefer WinRAR also know by the extension as rar.
* WinRAR can be used on any operating system and supports the rar, gzip, and other zip files.
* I has the potential to add integrity rules to an archive, as well as adding extra layers of security to an archive. 
* To create an archive use: 
  > rar a archiveName.rar
* To extract an archive use:
  > unrar archiveName.tar

## File permissions
* There are three types of users on the linux system:
  - File Owner (user) = u
  - Group = g
  - Other = o
  - all = a
* They are pretty self explanatory, but these groups may have three types of permissions:
  - r = read
  - w = write
  - x = execute
* For example you can either have read permission for Group or you can have read, write, execute. It doesn't matter, Its all up to the owner or whomever makes the permissions. 
* You can have separate permissions for each file or directory.
* To modify permissions we use "chmod".
* For example to give all permissions on a file to group we would use:
  > chmod g=rwx fileName.*
*   We can also use numeric values.
*   ![x](/imgs/FinalPics/chmod.png)
