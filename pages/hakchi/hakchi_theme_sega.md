---
title: Sega theming
sidebar: mydoc_sidebar
permalink: hakchi_theme_sega.html
folder: hakchi
---

## Sega theming overview
This section goes over changing the theme of the Sega Genesis and Mega Drive mini systems.

Background resolution: 1280×720  

##  Theme setup options
- FTP
- HMOD

### FTP

#### Single theme  
{% include note.html content="Make sure the .png background image name is exactly as shown without quotes 'background.png'." %}  

From the hakchi main screen:  
Goto Tools > FTP
{% include image.html file="menu_tools.png"  alt="Jekyll" caption="Tools > FTP" %}  

From here you will need to navigate to:  
/usr/game/hakchi/ui/md/  

**BUT** at first only /usr/game/ will exist.  

Navigate to /usr/game  
- Create new folder named hakchi  

Navigate to newly created hakchi folder  
- Create new folder named ui  

Navigate to newly created ui folder  
- Create new folder named md  

Navigate to newly created md folder  

You are now in:  
/usr/game/hakchi/ui/md/  

**PASTE** your background.png here.  

**DONE**  

Cycle power on your mini and when it boots it will use this image for the background.

#### Theme per region
{% include note.html content="Read and understand the single theme section above prior to moving on to this section." %}

If instead of having a single background you would like to have a different background per region you can use the following folder structure.  
- /usr/game/hakchi/ui/md/us/background.png
- /usr/game/hakchi/ui/md/jp/background.png
- /usr/game/hakchi/ui/md/eu/background.png
- /usr/game/hakchi/ui/md/background.png

You will now have 4 separate background.png files.  

When booting the system checks the currently selected regions folder "{region}/background.png" first, if that doesn't exist it checks for "md/background.png".  
If none of these exist it will boot with the stock background.  

### HMOD
**TODO**
