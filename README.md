# Exile-Installer
To install Double click on the Install.bat
If you are installing MySQL Server and MySQL Workbench do not apply the update it will cause it to crash.
Select Custom and then hit next
Click on the plus next to the MySQL Servers then click the plus next to MYSQL Server and then the plus next to MYSQL Server 5.6 then pick the version of the installer that you need (x64 or x86(32bit)) and then click on the arrow to move the install to Products/Features to be installed. The next thing you will want is MySQL Workbench.
Click on the plus next to Applications and then the plus next to MySQL Workbench and then the plus next to MySQL Workbench 6.3 and then select the version you will need as above. 

Then click next and if there are Requirements click Execute and then click next
and then click Execute
Depending on what you installed The configuration will come up for either SQLWorkbench or the SQLServer

If its the SQLServer

Click next and next again
Make sure your settings are set to TCP/IP check Port 3306 and Open Firewall port for network accsess and the config type Development Machine
Click next
Now it is time to set a Root password and Add an exile user
After setting a Root password click Adduser
Set a username for Exile make sure the host is set to All host, The role is set to DB Admin and then set the password.
Then click next and next again
Then click Execute 
Then click finish then next and Ok 

