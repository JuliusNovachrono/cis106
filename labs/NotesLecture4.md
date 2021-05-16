##### Arnaldo Jara

##### Professor Alberto

##### CIS-106-RE1

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
