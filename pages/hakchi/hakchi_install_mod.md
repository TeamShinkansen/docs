---
title: Installing the mod on your system
sidebar: mydoc_sidebar
permalink: hakchi_install_mod.html
folder: hakchi
---

##  Installing the hakchi mod onto your system

In the following example we will be install hakchi on a SEGA Genesis mini.  But the process is the same for other systems.

### 1. Start hakchi
When starting hakchi you will see it is offline.  This is noted by the red circle in the lower left corner and the status of 'offline' next to it.
{% include image.html file="offline.png"  alt="Jekyll" caption="Offline indicator" %}

### 2. Install the kernel
For this step it doesnt' matter which system you have selected in under 'Current games collection' since the kernel is the same for all systems.  

From the hakchi main screen:
Select Kernel > Install / Repair
{% include image.html file="install_repair.png"  alt="Jekyll" caption="Kernel Install / Repair" %}

You will be prompted with a confirmation screen, click "Yes"
{% include image.html file="kernalInstallConfirm.png"  alt="Jekyll" caption="Kernel Instal / Repair confirmation" %}

Next you will see the step by step instructions for installing the kernel.  
**Follow them exactly!**
{% include image.html file="ModInstallInstructions.png"  alt="Jekyll" caption="Kernel install instructions" %}

When the steps have been completed it will automatically be detected.
{% include image.html file="InstallingHakchiKernel1.png"  alt="Jekyll" caption="Kernel installing" %}

After a few moments it will automatically change to waiting for reboot.
{% include image.html file="WaitingForReboot.png"  alt="Jekyll" caption="Waiting for reboot" %}

When the reboot is complete hakchi will continue installation.
{% include image.html file="InstallingHakchiKernel2.png"  alt="Jekyll" caption="Installing again" %}

After a few more moments it will automatically change to waiting for reboot again.
{% include image.html file="WaitingForReboot.png"  alt="Jekyll" caption="Waiting for reboot" %}

Finally when it is completed you will see the Done! message box.
Click 'OK'.
{% include image.html file="CustomKernelDone.png"  alt="Jekyll" caption="Done!" %}
{% include image.html file="online.png"  alt="Jekyll" caption="online" %}

You will now be connected to the mini.  This is indicated by the green circle in the lower left corner and the status box alternating between 'Online' and 'SSH'.

### 3. Your device is taking to long to reboot.  

*Are you installing Hakchi, but you're getting a message saying "Your system is taking too long to reboot"? Try the following suggestions:*  
- Use the original USB Cable if using a NES/SNES Classic. The OEM cable has a white sticker  
- Turn off Windows Firewall  
- Turn off your VPN (if you have one) (In some instances, VPN may need uninstalled)  
- Turn off WiFi (if using a laptop)  
- Turn off your Antivirus  
- If using a Virtual Machine on a Mac/Linux, go to USB Settings and enable in both FEL/Powered On Mode  
- Also, If using Virtual Machine, make sure you have the virtual box extension pack and usb set to at least 2.0  
- You may need to install or update RNDIS Drivers  
- Unplug power from back of system, wait 30 seconds, plug back in, try again!  
- Restart Computer and/or hakchi  

Want to send this information in Rockin' the classics discord? Use the command !reboot in chat on the server.  

*You are now ready to install games on your mini.*


{% include links.html %}
