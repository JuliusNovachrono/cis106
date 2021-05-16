##### Arnaldo Jara

##### CIS-106-RE1

##### Professor Alberto

##### May 8,2020
# Deliverable 3: Turning Ubuntu into an everyday OS

<!-- TOC --> 
* [Step 1.1 Downloading Ubuntu disc](#step-11-downloading-ubuntu-disc)
    * [Step 1.2 Downloading Rufus to USB](#step-12-downloading-rufus-to-usb) 
* [Step 2.1 Preparing PC for Installation of Ubuntu](#step-21-preparing-pc-for-installation-of-ubuntu)  
    * [Step 2.2 Installing Ubuntu](#step-22-installing-ubuntu) 
* [Step 3 Update Ubuntu & other apps(if necessary)](#step-3-update-ubuntu--other-appsif-necessary) 
* [Step 4.1 Understanding basic Commands for Installing  Software](#step-41-understanding-basic-commands-for-installing--software) 
* [Step 4.2 Connecting to the internet](#step-42-connecting-to-the-internet) 
* [Step 4.3 Installing useful Applications for every day use](#step-43-installing-useful-applications-for-every-day-use) 
  * [Installing Thunder Bird (e-mail app)](#installing-thunder-bird-e-mail-app) 
  *  [Installing Remmina (remote assistance/connection app)](#installing-remmina-remote-assistanceconnection-app) 
  *   [Installing Libre Office (Office Suite app)](#installing-libre-office-office-suite-app) 
  *  [Installing Kodi (Entertainment / TV app )](#installing-kodi-entertainment--tv-app-) 
  *  [Installing PacMan (linux version game)](#installing-pacman-linux-version-game) 
  * [Installing Discord (Chat app)](#installing-discord-chat-app)
  * [Installing Visual Studio Code (app for coding)](#installing-visual-studio-code-app-for-coding) 
  *  [Installing zoom (Video calling app)](#installing-zoom-video-calling-app) 
*   [Step 5: Final Tips](#step-5-final-tips) 
*    [Works Cited](#works-cited)<!-- /TOC -->

## Step 1.1 Downloading Ubuntu disc
* Visit [ubuntu](https://ubuntu.com/) and click on the download tab, you should be able to see Ubuntu Desktop 20.04 LTS.
* After doing so you should be able to see the following image.
* ![x](../imgs/DelPics/step.1.png)
* If the download hasn't started simply click on download now.
* you should be able to see the following image.
* ![x](../imgs/DelPics/step.1.2.png)
* Then click on "save file" option, and then click "OK".
## Step 1.2 Downloading Rufus to USB
* Rufus will be used to boot Ubuntu into a computer using a USB drive 
* You will need to visit [Rufus](https://rufus.ie/en_US/).
* Then scroll down to the download section and click on Rufus 3.14 (Portable). 
* ![x](../imgs/DelPics/step1.3.png)
* Click on Save File.
* After download is finished open up the rufus saved file and press "YES" to allow permissions to make changes to your computer (don't panic nothing will happen yet.)
* The following menu should appear.
* ![x](../imgs/DelPics/step1.4.png)
* Next you will have to make the following changes:
* ![x](../imgs/DelPics/step1.5.png)
* Device = The USB name or name of storage device you will be using.
* For "Boot selection" click on SELECT on the right hand side  and select the ubuntu OS disc that was downloaded 
* After selecting Boot selection the rest of options will be selected by default.(PLEASE LEAVE EVERYTHING ON DEFAULT, UNLESS YOU ARE FAMILIAR WITH THE OPTIONS)
* Then click START
* ![x](../imgs/DelPics/step1.6.png)
* After status is ready, you can begin to prepare your PC for installation of Ubuntu.
## Step 2.1 Preparing PC for Installation of Ubuntu
* You are now ready to install Ubuntu onto a new PC (recommended) 'OR' You can delete the windows OS currently on your PC if you so desire. 
* Here is a 3 minute "visual instruction video" on how to delete the Windows OS or switch Ubuntu as default https://www.youtube.com/watch?v=nfNbwBLqwvI
  
## Step 2.2 Installing Ubuntu
* After deleting the Windows OS restart the PC. 
* Insert the USB drive containing ubuntu. 
* Select on Install Ubuntu.(using the arrow keys)
* Once it has loaded you are now ready to begin selecting options.(Order of options may vary on Ubuntu's latest updates)
* Start by selecting Keyboard layout:
![x](../imgs/DelPics/step2.1.png)
* Click continue
* Next select "Normal Installation" & for "other options" select "both options" to be able to download third-party software.
* ![x](../imgs/DelPics/step2.2.png)
* Click continue
* Next for Installation type select erase disk and install ubuntu.(This step will permanently make Ubuntu your main OS)
* ![x](../imgs/DelPics/step2.3.png)
* Click 'Install Now & Continue'
* Next select your time zone.
* ![x](../imgs/DelPics/step2.4.png)
* Click continue
* Next create your username & password
* ![x](../imgs/DelPics/step2.5.png)
* Click continue 
* ![x](../imgs/DelPics/step2.6.png)
* Kick back and relax & wait for installation to complete :)
* ![x](../imgs/DelPics/step2.7.png)
* Congratulations Installation is now complete!
* Click 'Restart Now'
* Next select your account & Enter Password:
* ![x](../imgs/DelPics/step2.8.png)
* Welcome to Ubuntu!
* ![](../imgs/DelPics/step2.9.png)
## Step 3 Update Ubuntu & other apps(if necessary)
* click the 3x3 grid on the lower left hand side of the screen.
* Type Terminal into search bar.
* ![x](../imgs/DelPics/step3.1.png)
* click on terminal to open
* Enter the following command:
* > sudo apt-get update
* ![x](../imgs/DelPics/step3.2.png)
* Then run: 
* > sudo apt update; sudo apt upgrade -y
* ![x](../imgs/DelPics/step3.3.png)
* Updates and upgrades are complete.
## Step 4.1 Understanding basic Commands for Installing  Software
* (Combine commands to run on terminal)
* using "sudo apt ..."
* sudo -  is used to use your root privileges
* apt - is a utility used to manage updates, installing, and removing packages 
* install - is used to install
* update - is used to update
* upgrade - is used to upgrade 
* remove - is used for removing
* -y is used to enter yes in advance
* ; - semi-colon is used to end a command on a line & continue a new command on the same line
* | - is the pipe symbol is used to enter multiple commands separated by the pipe
* wget - is also used to download
* rm - can be used to remove as well 
* Example of Installing a screenshot software called flameshot:
* ![x](../imgs/DelPics/step4.18.png)
## Step 4.2 Connecting to the internet
* Connecting to the internat is easy!
* First you will want to select the icon on the top right hand side. (It looks like two wires connecting)
* ![x](../imgs/DelPics/step4.19.png)
* Second you will want to select "Edit Connections..."
* ![x](../imgs/DelPics/step4.21.png)
* Third you will want to select the "+" sign to add a connection.
* ![x](../imgs/DelPics/step4.22.png)
* Fourth step you will want to select the type of connection & select create
* ![x](../imgs/DelPics/step4.23.png)
* Last step simply enter your internet information and select save.
* ![x](../imgs/DelPics/step4.24.png)
* The last used status indicates you have successfully connected to the Internet.
* ![x](../imgs/DelPics/step4.25.png)
* ![x](../imgs/DelPics/step4.26.png)
* Enjoy!!
## Step 4.3 Installing useful Applications for every day use
* First app we will Install is an Internet Web browser! (choose your web browser of prefrence)
* For Firefox enter the following command: 
* > sudo apt install firefox -y
* For Google Chrome enter the following command: 
* > wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
* Then enter: 
* > sudo dpkg -i google-chrome-stable_current_amd64.deb
* ![x](../imgs/DelPics/step4.1.png)
* Google chrome is ready to use!
## Installing Thunder Bird (e-mail app)  
* Second we will install an e-mail app called Thunder Bird: (it's a great email software that has the ability to write emails using html)
* To download enter the following command: 
* > sudo apt-get install thunderbird
* ![x](../imgs/DelPics/step4.2.png)
* Then enter your email account information:
* ![](../imgs/DelPics/step4.3.png)
* Click continue
* ![x](../imgs/DelPics/step4.4.png)
* Thunder Bird is ready to use!
## Installing Remmina (remote assistance/connection app)
* Next we will Install an app called Remina: (it's a free open source remote desktop client for Linux: it's used to remotely access one or many computers)
* To download enter the following command: 
* > sudo apt-get install remmina remmina-plugin-* -y
* ![x](../imgs/DelPics/step4.5.png)
## Installing Libre Office (Office Suite app)
* Next we will install an open source office suite called Libre Office: (Libre Office is a free open source software that includes applications for: Writing, spreadsheets, presentaions, graphs & flowcharts, databases, and math formulas) 
* To download enter the following command: 
* > sudo add-apt-repository ppa:libreoffice/ppa
* ![x](../imgs/DelPics/step4.6.png)
* ![](../imgs/DelPics/step4.7.png)
* Calc = Excel
* Draw = Visio
* Impress = PowerPoint
* Writer = Word
* Remember to use "sudo apt upgrade" or "update" if you wish to do so.
## Installing Kodi (Entertainment / TV app ) 
* Next we will Install an Entertainment app to watch movies & TV shows called Kodi.
* Enter: 
* > sudo apt install kodi
* ![x](../imgs/DelPics/step4.8.png)
* link to add movie ad-ons https://www.youtube.com/watch?v=4U3nDNbz0hQ
## Installing PacMan (linux version game)
* Next we will Install a game called PacMan.
* Enter: 
* > sudo apt-get install pacman4console
* ![x](../imgs/DelPics/step4.9.png)
* ![x](../imgs/DelPics/step4.10.png)
## Installing Discord (Chat app) 
* Next we will install a chat service called Discord:
* Enter: 
* > sudo snap install discord
* ![x](../imgs/DelPics/step4.11.png)
* ![x](../imgs/DelPics/step4.12.png)
## Installing Visual Studio Code (app for coding)
* Next we will install an app for Web Developers & all other computer science students called 'Visual Studio Code'
* Enter: 
* > sudo apt install software-properties-common apt-transport-https wget
* Enter: 
* > wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
* Enter: 
* > sudo apt update
* Then enter:
* > sudo apt install code
* ![x](../imgs/DelPics/step4.13.png)
* ![x](../imgs/DelPics/step4.14.png)
## Installing zoom (Video calling app)
* Next we will be installing Zoom for school remote classes.
* Enter:
* > sudo snap install zoom-client
* ![x](../imgs/DelPics/step4.15.png)
* Congratulations you have completed a fully functional Linux Operating System!
## Step 5: Final Tips
* Final Tips: The manual page also known as the 'man' page if you ever have trouble with a command type 'man' followed by the command you need help with.
* Example: 
* > man sudo
* ![x](../imgs/DelPics/step4.16.png)
* Tip 2: GOOGLE
* ![](../imgs/DelPics/step4.17.png)
* I hope you've enjoyed this step by step tutorial! I wish you the best in your linux journey!
## Works Cited
* Alberto, R. (n.d.). CIS 106: Linux commands. Retrieved May 09, 2021, from https://robertalberto.com/linuxcommands/home.html
* Norman, Reedus. “Apt Command in Linux.” Linuxize, Linuxize, 24 Feb. 2020, linuxize.com/post/how-to-use-apt-command/. 
* Rana, Ben. “How to Delete an Operating System from Dual Boot Computer.” YouTube, YouTube, 8 Mar. 2018, www.youtube.com/watch?v=nfNbwBLqwvI. 
