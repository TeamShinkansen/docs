---
title: "Getting started with hakchi2 CE"
keywords: sample homepage
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: index.html
summary: These brief instructions will help you get started quickly with hakchi2 CE.
---


## Installing hakchi

Follow these instructions to install the latest version hakchi2 CE.

### 1. Downloading hakchi

First, download hakchi.     
goto <https://github.com/teamshinkansen/hakchi2-ce/releases/>  
Click on the "Latest release" box then scroll to the bottom and find the "Assets" section.  
{% include image.html file="releasesPage.png"  alt="Jekyll" caption="hakchi2 CE release page" %}  

{% include image.html file="assets.png"  alt="Jekyll" caption="Assets" %}
Download your prefered version: debug, installer.exe or release.zip.

### 2. Installing hakchi

For this example we are using the installer.exe.  
Find the location of the downloaded installer (Typically C:\Users\{username}\Downloads)  
Double click the installer.  
If you are prompted by the UAC click 'yes'.  

When prompted for installation options the defaults are fine:  
{% include image.html file="installOptions.png"  alt="Jekyll" caption="Select components to install:" %}
Click 'Next >'

{% include image.html file="installOptionsDest.png"  alt="Jekyll" caption="Destination folder" %}
Click 'Install'

{% include image.html file="installing.png"  alt="Jekyll" caption="Installing" %}
When complete click 'Close'

####  hakchi is now installed!!!

## Starting hakchi

To start hakchi double click the icon located in the defualt install location.
Exmaple below from Windows 10.
C:\Program Files (x86)\Team Shinkansen\Hakchi2 CE  
{% include image.html file="iconHakchi.png"  alt="Jekyll" caption="Icon" %}

When starting you will first see the software loading and restoring original games.  
The firt time you run the software you may see an "Important message" containing updates or information.
{% include image.html file="importantInfo.png"  alt="Jekyll" caption="Important message" %}  

Click "OK" and you will now be at the main screen.  
{% include image.html file="hakchiMain.png"  alt="Jekyll" caption="hakchi main screen" %}

##  Installing the hakchi mod onto your system

In the following example we will be install hakchi on a SEGA Genesis mini.  But the process is the same for other systems.  

### 1. Start hakchi
Starting hakchi you will see it is offline and has a red circle in the lower left corner.
{% include image.html file="offline.png"  alt="Jekyll" caption="Offline indicator" %}  

For this step it doesnt' matter which system you have selected in under 'Current games collection' since the kernel is the same for all systems.
Select Kernel > Instal / Repair
{% include image.html file="install_repair.png"  alt="Jekyll" caption="Kernel Install / Repair" %}

You will be prompted with a confirmation screen, click "Yes"
{% include image.html file="kernalInstallConfirm.png"  alt="Jekyll" caption="Kernel Instal / Repair confirmation" %}

Next you will see the step by step instructions for installing the kernel.
Follow them exactly!
{% include image.html file="ModInstallInstructions.png"  alt="Jekyll" caption="Kernel install instructions" %}

When the steps have been completed it will automatically be detected.
{% include image.html file="InstallingHakchiKernel1.png"  alt="Jekyll" caption="Kernel installing" %}

After a few moments it will automatically change to waiting for reboot.
{% include image.html file="WaitingForReboot.png"  alt="Jekyll" caption="Waiting for reboot" %}

When the reboot is complete hakchi will continue installation.
{% include image.html file="InstallingHakchiKernel2.png"  alt="Jekyll" caption="Waiting for reboot" %}

After a few more moments it will automatically change to waiting for reboot again.
{% include image.html file="WaitingForReboot.png"  alt="Jekyll" caption="Waiting for reboot" %}

Finally when it is completed you will see the Done! message box.
Click 'OK'.
{% include image.html file="CustomKernelDone.png"  alt="Jekyll" caption="Done!" %}
{% include image.html file="online.png"  alt="Jekyll" caption="online" %}

You will now be connected to the mini.  This is indicated by the green circle in the lower left corner and the status box alternating between 'Online' and 'SSH'.

###  You are now ready to install games on your mini.


##  Adding games

##  Adding and scraping art



{% include links.html %}
