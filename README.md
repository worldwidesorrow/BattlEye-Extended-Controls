Battleye Extended Controls for DayZ Epoch
=================
# Install Instructions

1. Copy the bans.txt file into your Battleye folder if you don't already have one.

2. Copy files servermonitor.bat and start_server.bat into the server config folder wherever you installed it.
	The default location and name of this folder is C:\DZE_Server_Config

If you are using a different map than Chernarus, then edit file start_server.bat and change
line 9 to call the batch file of the alternate map that you are using.

3. Move the server_tools folder to the root of the C drive.

4. Follow the instructions in file "Hosts file edit.txt" to add the ibattle.org redirects to the Hosts file.

5. Open server_tools\Bec\Config and decide if you want 2, 3, or 4 hour restarts.
	Open the appropriate folder and copy the preconfigured scheduler.xml file.
	Back up one directory and paste scheduler.xml into the Config folder. It should appear above the Scheduler-FAQ.txt file.

6. Open file scheduler.xml and scroll towards the bottom. You can edit the entries in section "BEC Messages" to suit your needs.

7. You can add extra entries, remove unnecessary entries and edit the existing entries.

Please refer to my youtube video around the 6 minute mark where I explain this further.

Additional configurations can be made in file Config.cfg.

9. You may have to right-click and select properties on file server_tools\Bec\Bec.exe and unblock it.

10. You may also have to whitelist Bec.exe or the directory where the file resides in your antivirus software.

8. Start server by double clicking file servermonitor.bat.

For a full install and demo of these files, please refer to my install video on youtube at URL:

## Credits
***[ibattle.org](ibattle.org)***

***[Salival](https://github.com/oiad)***

***[EbayShopper](https://github.com/ebayShopper)***

***[Grave](https://github.com/bbatton)***
