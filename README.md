### Always PTT v2.2.7 by Software Solutions Australia (Disguise_AU)

Always PTT will keep your default capture device (your mic) muted unless an assigned push-to-talk key is being pressed.

It will only work with whichever recording device you have set as your default.

This program by default will set the CapsLock key as a universal push-to-talk (PTT) key while Always PTT is running.

It will appear as an icon in the task tray which has a menu when you right-click on the icon.

You can set another key to be the push-to-talk key by right clicking the Always PTT icon in the Windows task tray (bottom right of your screen), hover your mouse over the "Assign Push-to-Talk Key" menu, from there you can select various keys to use as your push-to-talk key.

Always PTT is designed for Windows 10 and has not been tested on any other versions of Windows.

You can exit Always PTT and set the assigned push-to-talk key back to its original functionality by right clicking on the Always PTT icon in the task tray and selecting the "Exit and Unmute Mic" option.


## INSTALL INSTRUCTIONS:
1. Run AlwaysPTT_v2.2.7_install and follow the prompts to install the program, you can use the default install location or set a custom install location.
2. Run Always PTT from the shortcut in the Start Menu, you will now see a white headset icon appear in your task tray. Right-click the Always PTT icon and go to the "Assign Push-to-Talk Key" submenu, then select your desired push-to-talk key from the various submenus. The keys are organised into categories to make it easy.
3. Test that Always PTT is working. You can do this from the Recording tab in the Sound window or in an application that detects sound.


## USAGE INSTRUCTIONS:
1. Always PTT will keep your microphone muted while it is running except for while you are holding the assigned push-to-talk key down.
2. Always PTT will show as a white headset icon in your task tray, the icon will be green while the assigned push-to-talk key is being held down.
3. To exit Always PTT and return the assigned push-to-talk key to its original functionality right-click the Always PTT icon in the task tray and select Exit.
This will immediately exit Always PTT and return the assigned push-to-talk key to its original functionality.


## HOW TO SET DEFAULT DEVICE:
1. Left click the Always PTT headphone icon in the task tray. This will show the Windows Sound dialog with the "Recording" tab automatically selected.
2. Find the microphone device you want to use, right click it and select "Set as Default Device". You can then close the Windows Sound dialog.


## TROUBLESHOOTING:
If you have set a default device and Always PTT hasn't detected it even after restarting Always PTT. Restart your computer.

If Always PTT doesn't work with a particular game or program (such as Discord), run Always PTT as administrator.

If you still have problems with this program, try reading the instructions again and follow them carefully.

If you are still having problems, join my Discord server and explain your problem there: https://discord.gg/EfAu2db


## CHANGELOG:

### v2.2.7; OSD functionality & Minor UI update

Added ability to show mic status as OSD. You can change the position and size of the OSD.

Added "OSD Settings" in "Always PTT Settings" submenu.

Added "Help" menu in the "Always PTT Settings" submenu which contains links to send an email to Software Solutions or join the GAME TIME! Discord.

Added "Reset Settings to Default" option  in "Help" submenu.

Added "Show Windows Settings" submenu.

Moved "Show Recording Devices" and "Show Volume Mixer" to "Show Windows Settings" submenu.

Fixed changing settings no longer unnecessarily reloads the Always PTT process.

Fixed if config file becomes corrupted due to an external source Always PTT will now reset it's settings to default.

Fixed microphone would stay muted under certain conditions after exiting Always PTT.

Changed Always PTT no longer needs to be restarted after selecting a different default device. However if you encounter a problem just restart Always PTT.

Changed installer now resets Always PTT settings to default when updating to a newer version.

### v2.2.6; Bug fixes, Beep option & Installer improvements

Fixed installer not deleting files from previous versions of Always PTT when installing a newer version.

Fixed bug where on rare occasions using the "Disable push-to-Talk" menu option could freeze Always PTT. Completely new code is now used for this.

Fixed bug where under certain conditions Always PTT could be prevented from saving the selected push-to-talk key to the config file (ptt.ini).

Fixed bug where settings would not carry over between version updates.

Added "Always PTT Settings" menu option which contains "Enable Beep", Automatically Run as Admin" and "Run on Windows Startup".

Added "Enable Beep" menu option which when enabled will play a beep sound when pressing and releasing the assigned push-to-talk key. (disabled by default)

Added "Automatically Run as Admin" menu option. This is only for users who require Always PTT to be running as admin.

Moved "Run on Windows Startup" menu option to the "Always PTT Settings" submenu.

Moved config file (ptt.ini) location from Always PTT install directory to "..\AppData\Roaming\Always PTT".

Changed installer icon to the Always PTT headset icon.

Changed red headset icon used when Always PTT is disabled to a grey one.

Changed font for the Always PTT header at the top of the main menu to bold font.

Removed bold font from "Show Recording Devices" menu text.

### v2.2.5; Run on Windows Startup, Show Volume Mixer & Disable Push-to-Talk

Added "Run on Windows Startup" menu option which allows you to toggle if Always PTT will run on Windows startup or not (disabled by default).

Added "Show Volume Mixer" menu option which opens the Windows Volume Mixer dialog.

Added "Disable Push-to-Talk" menu option which will disable Always PTT and return the assigned key to it's normal functionality.

### v2.2.4; Show Recording Devices

Added ability to open the Windows Sound dialog with the Recording tab already selected on single click of the Always PTT task tray icon.

Added "Show Recording Devices" menu option which is another way to open the Windows Sound dialog with the Recording tab already selected.

Moved "Software Solutions 2022" text to the bottom of the menu.

Changed "Exit" menu text to "Exit and Unmute Mic".

### v2.2.3; Installer & key icons

Added NSIS installer to install Always PTT with ease.

Added License Agreement which can be found on the first page of the installer and at the end of this ReadMe file.

Added key icons to the following submenus within the "Assign Push-to-Talk Key" submenu:
	Functions Keys
	Letter Keys
	Number Keys
	Numpad Keys

### v3.2.2; Minor UI update

Changed "Assign Key" submenu text to "Assign Push-to-Talk Key".

Fixed a spelling mistake.

### v2.2.1; Assigned Key indicators

Changed "Currently Assigned:" text to "Assigned Key:".

Moved "Assigned Key:" text from the "Assign Key" submenu to the main menu.

Added indicators on the menu items to show which push-to-talk key is selected.

### v2.2; Mouse button compatibility

Added compatibility for mouse buttons.

Added "Mouse Buttons" submenu in the "Other Keys" submenu.

### v2.1; Assign Key menu

Added "Assign Key" submenu with various keys in various key categories to select from to select a push-to-talk key from a menu rather than changing the config file.

### v2.0; Complete redesign of Always PTT from scratch

Removed microphone setup process, Always PTT now uses your default microphone device.

Added ability to change the assigned push-to-talk key to any key using a config file (ptt.ini).


## LICENSE AGREEMENT:

Copyright 2022 Software Solutions Australia

This software is provided 'as-is', without any express or implied warranty. In no event will the author be held liable for any damages arising from the use of this software.

Permission is granted to anyone to use this software for any purpose, including commercial applications, and to redistribute it freely, subject to the following restrictions:

1. The origin of this software must not be misrepresented; you must not claim that you wrote the original software.
   If you use this software in a product, an acknowledgment in the product documentation would be appreciated but is not required.
2. Altered versions must be plainly marked as such, and must not be misrepresented as being the original software.
3. This notice may not be removed or altered from any distribution.


-Disguise_AU
