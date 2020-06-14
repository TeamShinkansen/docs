---
title: Upgrading to hakchi CE from 2.31 or older
sidebar: mydoc_sidebar
permalink: hakchi_upgrade_old.html
folder: hakchi
---

## How to update from hakchi2 2.31 or older to hakchi2 CE  

If possible, it's recommended to uninstall the kernel from the system and restore it back to the stock state before proceeding.  

You can find the latest version of Hakchi2 CE at https://github.com/TeamShinkansen/Hakchi2-CE/releases/  

In most cases, you can just update the application by extracting the zip file of the new version over the existing files while replacing each file it asks about.  

If you want to start fresh and only transfer the games to the new install (recommended), all you need to do is copy the games inside the games and games_snes folders to the games folder in the new version.  

You'll need to install the new kernel from the Kernel > Install menu, in most cases you'll also need to download and install the newest versions of mods, Retroarch Neo is not compatible.  

A note about paths  
If you use the installer version, your data will be stored in the hakchi2 folder in your documents, if you use the portable version, it will be stored in the same folder as hakchi.exe.  

Your system is taking too long to reboot  
This can be as simple as your computer not being able to provide enough power or more complex, for a more complete list see "Taking to long to reboot" section of [Installing the mod page.](./hakchi_install_mod.html)    

If you're using a virtual machine, there are different USB devices depending on which stage the installation is on, one is the FEL mode USB device, the other is an RNDIS device, this will typically show up as "classic" or perhaps a Samsung mobile device.  Virtual box also requires the 'virtual box extension pack'.    

Want to send this information in Rockin' the classics discord? Use the command !update in chat on the server.  
