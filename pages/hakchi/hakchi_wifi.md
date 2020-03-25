---
title: WIFI
sidebar: mydoc_sidebar
permalink: hakchi_wifi.html
folder: hakchi
---

## WIFI overview
This section goes over setting up WIFI on your mini systems.

##  Wifi setup

### 1. Install WPA Supplicant
From the hakchi main screen:  
Goto Modules > KMFD's Mod Hub
{% include image.html file="menu_modules.png"  alt="Jekyll" caption="KMFD's Mod Hub" %}

Goto KMFD System (tab)
{% include image.html file="Mod_Hub_System.png"  alt="Jekyll" caption="KMFD System tab" %}

Select 'WPA Supplicant' and click 'Download and install'   

WPA Supplicant will now be installed on the mini and it will reboot.

### 2.  Configure WIFI via telnet
From the hakchi main screen:  
Goto Tools > Open telnet client  
{% include image.html file="menu_tools.png"  alt="Jekyll" caption="hakchi tools menu" %}

This will open a new window with a 'madmonkey login:' prompt.  
{% include image.html file="telnet_login_prompt.png"  alt="Jekyll" caption="Telnet prompt" %}  

At this prompt  enter "root" and you will be logged in.  
{% include image.html file="telnet_logged_in.png"  alt="Jekyll" caption="Telnet logged in" %}

Now type **wifi-wpa-setup** and enter your SSID and password when asked.  
Then follow instructions on screen.    
{% include image.html file="telnet_wifi_entered.png"  alt="Jekyll" caption="wifi-wap-setup" %}

hakchi will now connect to your mini via wireless!  

{% include note.html content="While rebooting the Wi-Fi adapter must be the only USB device plugged in." %}  
{% include note.html content="Failure to do so will require un-installing WPA Supplicant and starting over." %}

**Your mini now has wifi enabled!!**
