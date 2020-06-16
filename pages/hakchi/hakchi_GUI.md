---
title: Supported devices
sidebar: mydoc_sidebar
permalink: hakchi_GUI.html
folder: hakchi
---




## Menu items  

### Kernel  
***  
This section goes over installing, reseting and uninstalling hakchi.  

##### Install / Repair  
Install or re-install the kernel mod and /hakchi (folder)  
**This will update any existing hakchi scripts, but doesn't delete anything**  

##### Reset  
Reset hakchi by deleting /hakchi folder then installing it again  
**This will delete any ROMs and HMODs from NAND resulting in a freshly flashed console**  

##### Uninstall  
Uninstalls /hakchi folder, ROMS, HMODs and kernel updates but *NOT* saves  
**Completely removes hakchi mod and reverts they system back to stock**  

*There is also a factory reset option that is like uninstall, but it also wipes your saves*  

### Advanced  
***  
This section has advanced options you should only use when instructed by a dev.  

### Modules  
***  
##### Install extra modules  
Select which downloaded modules you want to install.  
If a module is greyed out it is already installed.  

#### Uninstall extra modules  
Select which installed modules you want to uninstall.  
Greyed out items are not installed.  

#### Generate modules report  
Creates an HTML report with details of installed modules.  

#### KMFD's Mod Hub  
Hub / repository for downloading of RetroArch, cores and other options.  

#### Manage mod repositories
Used for adding and removing repositories.  

### View  
***  
Options for sorting the games list.  

### Settings  
***  
#### Language  
Change the hakchi CE UI language.  

#### SEGA UI Theme  
Allows the changing of the Sega UI  between United States, Europe and Japan.  

#### SFROM tool  
Sfrom is the rom format that the stock emulator of the SNES uses.  

#### Convert SNES ROMs to SFROM
hakchi CE has basic sfrom generation, but the sfrom tool (above) is a separate app that does it better.  

#### Separate games storage  
Creates a separate 'Games list' for each system in the UI.  
These lists are maintained in separate folders in the hakchi2-ce folder.
Examples:  
- /games  
- /games_md  
- /mages_snes  
etc...  

#### Compress games when adding  
TODO  

#### Compress box art when adding  
TODO  

#### Center box art thumbnail  
TODO  

#### Disable hakchi2 popups  
TODO  

#### Separate games for multiboot  
TODO  

#### Always copy original games  
TODO  

#### Use linked sync  
TODO  

#### Global command line (Experts!)  
TODO  

### Tools  
***  
##### Save state manager  
TODO  

#### Take screenshot  
TODO  

#### Save DMESG output  

##### Open FTP client  
Opens a file explorer window to transferring files to your mini.  

Shouldn't be needed when using this option, but if you need to enter the info manually:
Host: 169.254.13.37  
Port: 21  
Login: root  
Pass: none   

##### Open Telnet client  
Remote telnet login to the system

Host: 169.254.13.37  
Port: 23  
Login: root  
Pass: none  

#### Boot splash  
TODO  

#### Reboot  
Sends reboot command to console  

#### Switch running firmware  
TODO  

#### Format SD card  
TODO  

#### Prepare art folders  
TODO  

### Bluetooth  
***  

### Buttons and options  
***  
#### Games list  
List of games currently added to hakchi.  
Checked games are sync'd when selected.  

Right clicking on games expands more options.  
e.g. Select emulation core.  

#### Add more games  
Adds more games to current games list.  

##### Export to USB
Syncs your checked games to a USB stick.  Requires  a USB 2.0 or 3.0 (system USB ports are only 2.0) formatted to EXT4 or NTFS.   
Insert USB into your PC running hakchi and press export.   
Safely remove.  
While mini is powered off insert into OTG cable, hub or port on your mini.  
Power on.  
When using USB storage on your mini and hakchi is connected the space estimation in the bottom right corner now reflects the USB storage.  
Pressing SYNC now syncs with the USB NOT the mini.  

##### Synchronize selected games with mini
Syncs all checked game from the game list to the mini when USB storage is not used.  If USB storage (Export to USB) is used **AND** connected to the mini sync games will be sync'd to the USB.  
