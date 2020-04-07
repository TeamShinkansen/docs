---
title: Installing RetroArch and other systems
sidebar: mydoc_sidebar
permalink: hakchi_RA_and_other.html
folder: hakchi
---

### Installing RetroArch and cores
For this tutorial we will download RetroArch and our cores individually then install them in the final step.  You can also use the "Download and install option" for each item in the KMFD's Mod Hub if you wish.  

### 1. Start and connect hakchi

### 2. Download RetroArch
From the hakchi main screen:
Goto Modules > KMFD's Mod Hub
{% include image.html file="menu_modules.png"  alt="Jekyll" caption="KMFD's Mod Hub" %}

Goto KMFD RetroArch tab and select your flavor of RetroArch either Ozone, RGUI or XMB then click download.
{% include image.html file="Mod_Hub_RetroArch.png"  alt="Jekyll" caption="KMFD's RetroArch" %}

The image above includes an example image for RetroArch OZone interface.  The image below is an example image of the XMB interface.  

{% include image.html file="RA_XMB_example.png"  alt="Jekyll" caption="XMB exmaple" %}

{% include note.html content="You have just downloaded RetroArch.  Now you MUST download cores for whatever systems you wish to use." %}


### 3. Download cores
As in Step 2 Goto Modules > KMFD's Mod Hub.  
But now goto "KMDF Cores Tab" and select the cores you wish to run, for this tutorial we will get both 'PicoDrive' and 'Genesis Plus GX'.  Select both of these and **download** them.  
{% include image.html file="Mod_Hub_Cores.png"  alt="Jekyll" caption="Cores" %}

### 4. Install modules  
Goto Modules > Install extra modules  
{% include note.html content="Any modules greyed out are already installed." %}  

{% include image.html file="menu_modules.png"  alt="Jekyll" caption="Install extra modules" %}  

Check the boxes for RA and the cores then click "OK".  
{% include image.html file="Select_the_modules.png"  alt="Jekyll" caption="Select modules" %}  

System will reboot.  
{% include image.html file="WaitingForReboot.png"  alt="Jekyll" caption="Waiting for mini" %}  

Mods will now be installed on the mini  
{% include image.html file="UploadGames.png"  alt="Jekyll" caption="Installing mods" %}   

The done dialog box will display when completed.  
{% include image.html file="UploadGamesDone.png"  alt="Jekyll" caption="Done" %}  

**RA and your cores are now installed!!!**  


### 5. Selecting core to run (optional)  
By default games will attempt to run in stock emulator.  Use this option if you wish to specify a different emulator (core).  
From the hakchi main screen:  
Right click on one of your added games. And click on "Select emulation core..."
{% include image.html file="game_right_click_menu.png"  alt="Jekyll" caption="Right click menu" %}  

This will open the "Select Cores" windows.
{% include image.html file="select_cores.png"  alt="Jekyll" caption="Select cores window" %}

When you select a game in the left section it will populate the "Console" and "Core" listings with installed options.  
After you select your game choose the console it is for, then which core you wish to associate with it.  
The command line will automatically be populated.  
**Only mess with the command line if you know what you are doing**  
{% include image.html file="select_cores_game_selected.png"  alt="Jekyll" caption="Select cores window" %}

When you are happy with your selections click "Apply"  
When complete select "Close"  

### 6. (Optional) Add the RetroArch 'Game' to mini
If you wish to enter the RetroArch UI without playing a game you can add the RetroArch 'game' to the mini UI.  This is just an Icon for your systems UI that will load RetroArch.  

#### 6a. Via mod hub
From the hakchi main screen:
Goto Modules > KMFD's Mod Hub  
{% include image.html file="menu_modules.png"  alt="Jekyll" caption="KMFD's Mod Hub" %}  

Goto the games tab.  
{% include image.html file="Mod_Hub_Games.png"  alt="Jekyll" caption="KMFD's Mod Hub games tab" %}  

Scroll down until you see the 'RetroArch UI:...' options.  
{% include note.html content="There are multiple options, they are just different icons for opening RetroArch." %}  

Select one of them and click download.  

This will add the 'game' to your hakchi games list.  

Verify 'RetroArch' UI is "Checked" in the games list and click "Synchronize selected games with mini".

#### 6b. With CLV-Z-RARCH file
First download the RetroArch game "CLV-Z-RARCH".  If this link isn't available you can ask for it in our Discord channel, someone will be able to provide it.  

Once downloaded drag the zipped game file onto your "Games Collection" on the hakchi main screen.  It will be added as a new app.  
{% include image.html file="RetroArch_InGamesList.png"  alt="Jekyll" caption="RetroArch in games list" %}  

Verify 'RetroArch UI' is "Checked" in the games list and click "Synchronize selected games with mini".  

The RetroArch icon will now be on your system UI.
{% include image.html file="RetroArch_InUI.png"  alt="Jekyll" caption="RetroArch on system" %}  

**RetroArch is now installed!!!**

{% include note.html content="Some systems will require you to add a or multiple BIOS file(s).  Move onto the next section to learn how to install required BIOS files." %}
