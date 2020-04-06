---
title: Installing BIOS
sidebar: mydoc_sidebar
permalink: hakchi_bios.html
folder: hakchi
summary: These brief instructions will help you install BIOS files on your mini.
---

## Installing BIOS
{% include note.html content="BIOS files are proprietary and can not be provided." %}  

### Prerequisites:
 - You have the BIOS files required
 - BIOS file names are **IDENTICAL** to what is required in RetroArch.  For more information see link to consoles and cores documentation at end of this page.

### 1. Install (copy) BIOS to your mini  
  Your options for transferring BIOS files are:
 - 1a.  FTP
 - 1b.  KMFD's RA BIOS Master Module

#### 1a. FTP
From the hakchi main screen:  
Goto Tools > FTP
{% include image.html file="menu_tools.png"  alt="Jekyll" caption="Tools > FTP" %}  

This will open an FTP window.
{% include image.html file="ftp_Window.png"  alt="Jekyll" caption="FTP Window" %}  

Navigate to RetroArch system folder /etc/libretro/system/  
{% include image.html file="ftp_system_folder.png"  alt="Jekyll" caption="FTP system folder" %}  

 Now right click and **COPY** the BIOS files from your PC, then right click **PASTE** them in this folder.

 **Goto section 2 to validate they are installed properly**  

#### 1b.  KMFD's RA BIOS Master Module
From the hakchi main screen:
Goto Modules > KMFD's Mod Hub
{% include image.html file="menu_modules.png"  alt="Jekyll" caption="KMFD's Mod Hub" %}

Goto KMDF BIOS tab and Select "KMFD's RA BIOS Master Module"

The click "Download".  
{% include note.html content="If you click Download and install this is fine, you will just re-install it again shortly." %}  

On PC navigate to your hakchi folder.  In this example we will assume the 'hakchi' folder is located on the desktop.  
 - C:\Users\USERNAME\Desktop\hakchi

From there navigate to the \etc folder in the master module mod you just downloaded.  
- C:\Users\USERNAME\Desktop\hakchi\user_mods\_km_ra_bios_master_module.hmod\etc\libretro\system  

Right click **COPY** the BIOS files from your PC then right click **PASTE** them in this folder.

Now install the module.  

Goto Modules > Install extra modules  

{% include image.html file="menu_modules.png"  alt="Jekyll" caption="Install extra modules" %}  

Check the boxes for RA BIOS Master Module then click "OK".  Even if this is greyed out you can still check this box and install it.

System will reboot.  

 **Goto section 2 to validate they are installed properly**

### 2.  Validate BIOS with RetroArch

On the mini you can check if the BIOS file is installed properly.

Open RetroArch menu by:
- opening RetroArch 'Game' you have added to the UI   
  - This can be found as an optional step 6 in the 'Installing RetroArch' page under the "Installing RetroArch and Other systems" section of this site.  
- [SEGA] launch a game that that uses RetroArch and press reset on the system  
- [S/NES, SEGA] with a controller that has start and select, press both at the same time


For this example we are checking for Sega CD BIOS with the km_Genesis Plus GX Core.
From RetroArch got Main Menu > Load Core  
{% include image.html file="RA_LoadCore.png"  alt="Jekyll" caption="RA Load core" %}  

Press 'OK' button.  
Scroll down to 'Sega - MS/GG/MD/CD (km_Genesis Plus GX)'  
{% include image.html file="RA_SegaCore.png"  alt="Jekyll" caption="RA Sega core" %}

Press 'OK' button.  

This will return you to the Main Menu.  
Goto main menu > Information  
{% include image.html file="RA_SegaCore.png"  alt="Jekyll" caption="RA Sega core" %}

Press 'OK' button.  

Goto Core information  
{% include image.html file="RA_Information.png"  alt="Jekyll" caption="RA Sega core" %}

Press 'OK' button.

From here you can scroll down and see the 'Firmware(s)' status.  
If the BIOS file was copied properly it will include **Present** in the line.  The image below shows examples of both missing and present BIOS files.  
{% include image.html file="BIOS_PresentMissing.png"  alt="Jekyll" caption="Core information" %}   

**Your BIOS files are note installed!!!**

**Link to Google Doc that covers consoles, cores, required BIOS files and notes**  
<https://drive.google.com/file/d/1pd-_cy6fLKHvuWYD1s0e3cog3UKlq-B1/view>
