##### Arnaldo Jara

##### Professor Alberto

##### CIS-106-RE1

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
