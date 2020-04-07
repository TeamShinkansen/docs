---
title: Overclocking
sidebar: mydoc_sidebar
permalink: hakchi_overclock.html
folder: hakchi
---

## Overclocking overview  

**USE AT YOUR OWN RISK**  

This section goes over overclocking your mini systems.  While overclocking your mini **MAY** become unstable and crash.  This is due to the quality of the manufactured CPU.  If you experience crashing disable any overclocking.  


##  Overclock options
- Easy Overclock **Preferred**
- Xtreme Overclock
- --overclock

### 1. Easy Overclock
The **preferred method** of overclocking  is Easy Overclock.  
You can get Easy Overclock from:  
Modules > KMFD's Mod hub > Games (tab)  
Select this 'Game' and click Download.  
When sync'd this "Game" is added to the UI menu to allow toggling of overclock.  
{% include note.html content="Overclocking is reset after power cycle." %}  


### 2. Xtreme Overclock
**Read 'Warnings and Xtreme Overclock Usage' when you have Xtreme Overclock selected in the mod hub prior to use!**

Xtreme Overclock can be found in:  
Modules > KMFD's Mod hub > KMFD RetroArch (tab) > Xtreme Overclock  
Click Download and install.  

Xtreme Overclock Can be verified and toggled via telnet with the commands below.  Stock freq - 1008000, Overclock freq - 1344000.
- hakchi overclock - Display current speed and temp
- hakchi overclock boot - Set stock clock speed
- hakchi overclock max - Enables overclock

{% include note.html content="Xtreme overclock is always active and is maintained after power cycle!" %}

### 3. --overclock
If --overclock is added to the command line of a RetroArch game the system will overclock for game then down clock on exit
