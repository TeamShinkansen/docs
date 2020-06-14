---
title: Adding games to your mini
sidebar: mydoc_sidebar
permalink: hakchi_adding_games.html
folder: hakchi
---

## Adding a new game to your mini

### 1. Click 'Add more games'
With hakchi started and connected.
From the hakchi main screen:
Click 'Add more games'
{% include image.html file="AddMoreGames.png"  alt="Jekyll" caption="Add more games" %}

### 2. Select your games
Browse your computer and select the game you would like to add and Click "Open"
{% include note.html content="When selecting your game(s) you may select a single game by clicking on it, a group of games by holding shift while you click on the second game or individual games by holding CTRL while clicking on each game after the first." %}
{% include image.html file="SelectGame.png"  alt="Jekyll" caption="Select your game" %}

The game will now be added to the "New apps" area of the "Current games collection:"
{% include image.html file="NewApps.png"  alt="Jekyll" caption="New apps" %}

### 3. Click 'Synchronize selected games'  
{% include note.html content="**As of hakchi 3.8.0 a scraper has been added for NES, SNES and Sega.  This will attempt to pull cover art and info from thegamesdb.  If this fails, you wish to change it or you are using a system that doesn't scrape you can follow the steps below.**." %}


## Adding art

### 1. Select game and click "Artwork" tab
To add art to a single game, select the game and press the "Artwork" tab in the "Game options" area.
{% include image.html file="Artwork.png"  alt="Jekyll" caption="Artwork" %}  
  Button descriptions:  
    Default - Restores the default Images  
    Browse - Locate and use images located on your local computer  
    Google - Brings up a window of google images based on the game name  
    Spine - (Sega only) Opens the Spine generator window with a Google images window for spine art  

### 2a.  Add individual art from google image search
For our Sega Genesis Battletoads example we will click the "Google" Button.
{% include image.html file="GoogleImagesBattletoads.png"  alt="Jekyll" caption="Google image Battletoads" %}

Double click on the image you like and it will populate cover artwork.
{% include image.html file="BattletoadsCoverAdded.png"  alt="Jekyll" caption="Battletoads cover artwork added" %}

{% include note.html content="Spine art is only for the Sega Genesis / Mega Drive." %}
Now we click on "Spine", Select our spine art and style then Click "OK"
{% include image.html file="SpineGenerator.png"  alt="Jekyll" caption="Spine generator" %}

Now your artwork is complete!
{% include image.html file="BattletoadsSpineAdded.png"  alt="Jekyll" caption="Spine artwork added" %}

### 2b. Adding art to multiple games from google image search
To add art to a multiple games, select the games you want to add art to, right click on one of them and select "Download box art for selected games"
{% include image.html file="DownloadBoxArt.png"  alt="Jekyll" caption="Download box art" %}

{% include note.html content="This will use the first google image result that is found based on the name.  It also will not populate spine art for the Sega Genesis / Mega Drive.  To add spine art refer to Step 2a" %}

### 3. Click 'Synchronize selected games with mini'
Now we add the game to the mini.
Make sure the game(s) you want to add are checked in the "Current games collection" then click "Synchronize selected games with mini".

You will see the uploading dialog box.
{% include image.html file="UploadGames.png"  alt="Jekyll" caption="Uploading games" %}

Then when it's completed the "Upload games done" dialog box will appear.
{% include image.html file="UploadGamesDone.png"  alt="Jekyll" caption="Done" %}

{% include note.html content="System game limits per folder.  On the S/NES systems it is recommended to keep the number of items (games and folders) to 30 or less per screen / folder.  Going beyond this may cause errors.  On the SEGA system you *may* be able to go as high as 200 before you experience menu lag. " %}    
    
**You are now ready to play your newly added game(s)!!!**
