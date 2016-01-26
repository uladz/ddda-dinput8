# Dragon's Dogma: Dark Arisen dinput8.dll hook
## Features
### Save backups
You need to set the right path to your save folder in dinput8.ini.  
A hook is placed just before the game creates a save. When it gets there, the current save gets duplicated with a timestamp added to it.  
If you need to revert to previous save, simply rename it to "ddda.sav".

### Character customization screen
Allows you to enter the character customization screen at any time:  
1) go to the main menu (either the one with load game/options/etc or the one with main menu/manual/exit game)  
2) hold Home (can be changed in dinput8.ini) and press Enter  
!!!you need to really press enter, it doesn't work with mouse!!!

### In-game clock
Displays in-game time in top right corner of the screen.  
May not work with enb, steam overlay, etc.

You need to enable it in dinput.ini.  
You can change the font size/color in dinput.ini.

## Installation
Copy dinput8.dll and dinput8.ini into the main DDDA folder.

## Credits
MinHook - The Minimalistic x86/x64 API Hooking Library:
http://www.codeproject.com/Articles/44326/MinHook-The-Minimalistic-x-x-API-Hooking-Libra

inih - simple .INI file parser
https://github.com/benhoyt/inih

Idea for entering customization screen + pointers for clock taken from:
http://forum.cheatengine.org/viewtopic.php?p=5641841#5641841