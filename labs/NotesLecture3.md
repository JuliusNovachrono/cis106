##### Arnaldo Jara

##### Professor Alberto

##### CIS-106-RE1

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
* ![x](/imgs/root.png) 
