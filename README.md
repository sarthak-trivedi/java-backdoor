# java-backdoor
Access file system , delete files , send message remotely


#prerequisite
JRE

#About app
You can access victim's computer remotely with this small application
Send messages, delete files , access files using this app
You can access multiple coumputers at a time
Cross platform application (Works in Linux, Windows, MAC OS etc.)

#Installation
Run Server.java on your computer to access victim's computer

Install Client.java into victims pc (Change localhost to an ip or domain on line 72 if you want to access computer from outside of network)

Remember you need to forward port for getting incoming connections

#How to use
After getting successful connection you can use follow operations

/send [Enter]
$YourMessageOnNextLine [Enter]
*Message sent*
*You can see reply on the same terminal*
/stop <-- to come back to main menu

/file_handler [Enter]
ls [Enter] (To see list of file)
*file listed*
cd [Enter]
Enter dir name on next line listed using ls command to change directory
*Directory changed*
rm [Enter]
Enter dir or file name on next line listed using ls command to delete file
*File deleted*
/stop <-- to come back to main menu

/exit [Enter]
To exit an application
