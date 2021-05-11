### Arnaldo Jara

### CIS-106-RE1

# Homework: 4  The Linux Filesystem

1. **Explain the difference between absolute path and relative path:**
* Absolute path is the full path name, and can access any file in any directory. Realtive path only uses partial of the full path, which is used when working within a current directory. 

2. **Why Linux uses / instead of \ for its directory paths?**
* Its because Linux is a unix like OS, and the forward slash "/" is used to seperate a directoy. Windows uses backslash because they think their cool lol.

3. **In Windows, these files are all the same: File FILE file and FiLE. But in Linux this is not the case, Why?**
* Linux directories/files are case sensitive, unlike windows file system.


4. **What is the Filesystem Hierarchy Standard (FHS) and who maintains it?**
* The FHS is a policy that sets the rules for directory structures and content on most linux distibutions, and the "Linux Foundation" maintains the FHS policy.

5. **Explain what type of files are stored in the following directories:**

Directory | What is it used for?
--------- | --------------------
/bin    | used for containing binary commands that can be used by scripts, admin and other users
/dev    | used for containing device files such as a cd drive
/etc    | used for containing static configuration files
/home   | used for containing the home directory
/lib    | used for containing shared libaries that load after a program is started.     
/opt    | used for containing static add on software packages
/tmp    | used for containing temporary files from booting the computer
/var    | used for containing variable data, such as files 
/proc   | used for containing system information created when the computer is booted
/usr    | used for containing sharable read only files

6. **How does a period at the beginning of a file name means (example .bashrc)?**
* It seperates the file from it's extension.

7. **Which command would you use to list all the files inside the /usr/share/ directory?**
* ls -a


8. **If you are working in the /usr/share/icons directory and want to move to your home directory, which command would you use?**
* cd

9. **Explain what these commands do:**

`cd .config/.htop; cd ../; ls -lX`
* long list and sort by extension name everything in the .config directory.



10. **John has a lot of files in the directory /var/www/html/webapp. He wants to long list all the files, including hidden files, by modification time (newest first), and with human-readable file sizes. Which command should he use conjuring that his current working directory is:** 
    
`/home/john/.git/`
* cd --> cd /var/www/html/webapp --> ls -lath
