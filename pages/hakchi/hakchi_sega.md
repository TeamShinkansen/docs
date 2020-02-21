---
title: Supported devices
sidebar: mydoc_sidebar
permalink: hakchi_sega.html
folder: hakchi
---

## SEGA

### System details
OS - Linux  
Controller ports - USB  
Emulator - M2engage  

Minimum power supply recommended  1.5  

Additional storage space gained with hakchi CE 3.7 about 54mb  
**Storage resize will revert back to stock after uninstalling**  

Clock speed   
Stock - 1008000  
Overclock - 1344000  

### Launching games from Sega UI  
  Press "A" to launch games with stock M2 emulator    
  Press "Start" to launch games with RetroArch (if installed)  
  To specify a core, Right click on a game from the hakchi "Custom Games" list and click "Select emulation core..."   

  When launching a game if a description does not exist it will launch directly into the game.  If a description does exist the standard game info box will pop up prior to game starting.


### Command line arguments:  
 - --3bpad=1     
	Used for games like zombies ate my neighbors that won't work with 6 button pads    
	example - /bin/m2engage /var/games/CLV-G-XXSMB/Zombies_Ate_My_Neighbors.md.7z --3bpad=1    
 - --smooth43=1    
	command line for factory scan lines (stock emulator only)    
- --sramsize=xxxx    
	forces sram size overriding detection    
- --sramtype=sram/eeprom    
	forces type, but most eeprom games currently won't save anyway, as only one type of eeprom is supported by m2engage  
