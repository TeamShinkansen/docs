---
title: Bluetooth
sidebar: mydoc_sidebar
permalink: hakchi_bluetooth.html
folder: hakchi
---

## Bluetooth overview
At the moment this document only covers adding bluetooth to the Sega Genesis systems.  S/NES is also possible but hasn't been documented yet
Bluetooth (S/NES requires WIFI and OTG HUB).  SEGA wifi not required due to USB ports.


## Bluetooth (SEGA)

### 1. Install BlueZ
From the hakchi main screen:  
goto Modules > Install extra modules  
{% include image.html file="menu_modules.png"  alt="Jekyll" caption="Install extra modules" %}

In "System" check box for BlueZ and click "OK"  
{% include image.html file="Select_the_modules.png"  alt="Jekyll" caption="Select the modules" %}  

You will see the installing mods dialog, then the mini will reboot and then you will see installing modes once more.  

When it is complete click "OK".  
{% include image.html file="UploadGamesDone.png"  alt="Jekyll" caption="Done" %}  

the "Bluetooth" Menu is now added to the top hakchi menu listing.  

### 2. Pair your bluetooth controllers
From the hakchi main screen:
Select the "Bluetooth" menu  and start your devices pairing mode.  
The device will show up under detected devices.  
{% include image.html file="menu_bluetooth_detected.png"  alt="Jekyll" caption="Detected devices" %}  

Click the device to pair it.  When it is paired it will show up under paired devices.    
 {% include image.html file="menu_bluetooth_paired_devices.png"  alt="Jekyll" caption="Paired devices" %}

**You are now ready to use your bluetooth controller**  

{% include note.html content="For a list of supported devices see the Advanced > Supported devices page." %}
