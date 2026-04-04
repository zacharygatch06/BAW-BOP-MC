# Welcome to the BAW-BOP-MC Modpack!
Modpack for the BAW BOP Minecraft Server. {heavily wip}

{put a nicer description here soon}

## Mod List:
[(Link to Google Document containint the mod list)](https://docs.google.com/document/d/10r6xUfpXC2QrtwfRxElvx27GJ5jdHwNjNsDrACdMfjs/edit?tab=t.0)

^ This contains more specific information about each mod if you are curious. {reword this}

## Mod Installation Instructions {ROUGH - REVISE LATER}:  

**(0. Make sure you have Minecraft Forge - MC 1.20.1 Installed)**
 - Run Minecraft version 1.20.1 at least once to generate your game files
 - Go to [this link](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.20.1.html) and download the {CHECK WHICH VERSION TO PUT HERE}
 - Run the installer (you may have to right click > select "Open With" > Java). Select "Install client" and click "OK"
 - Select the new Forge profile in the Minecraft Launcher and launch the game to confirm it's working.

**1. Go to [BAW-BOP-MC Releases](https://github.com/Maltent/BAW-BOP-MC/releases) and download the latest version of the modpack**
- 'client-fast.zip' is the standard modpack that has everything necessary to join and play on BAW BOP MC
- 'client-fancy.zip' is for beefier computer. Download this if you think your computer can handle more graphically intensive mods (See mods list for specifics)

**2. Navigate to C:\Users\\[USERNAME\]\AppData\Roaming\.minecraft\mods**
- On your keyboard, press "Windows + R"
- Type '%appdata%' into the dialog and click "OK"
- Click throught the folders until you get to the mods folder

**3. {Unzip the contents of the modpack zip file into mods}**
- {TECHNICALLY, FORGE CAN READ .zip FILES DIRECTLY AS LONG AS ALL THE .jar FILES ARE IN THE ROOT DIRECTORY}
- {SO MAYBE JUST HAVE THEM CUT-PASTE THE .zip FILE DIRECTLY AND LEAVE IT AT THAT}

**4. Launch the game and join the server :D**
- If you are having issues, send us a message on the Discord server and we can help you out.

===============================
## TO-DO LIST FOR ADMINS
- Make sure that the current mod organization is correct
- Add some server-size mods (e.g. plug-ins, moderation, backups, optimization mods, etc.)
- create the releases for the mods
  - Consider adding version to the modpack to avoid confusion (e.g. client-fast-V1.0)
- Revise this markdown file with better sections and organizations
  -  Have instructions for people installing the modpack
    - Explain the folder organization w/ more detail
    - Put screenshots and other fun fancy stuff
      - Server logo? (we can put that as the server icon too :o)


## [Mods folder organization]
'/base' - mods that exist in all other folders  
'/serverOnly' - mods for only the server  
'/clientOnly' - mods for only players  
'/clientFancy' - mods if your computer can handle it  

## [Releases setup + combinations]  
- serverMods.zip - zip folder for the server (not technically needed but maybe it would be nice to have?)  
  - base + serverOnly  
- client-fast.zip - basic modpack for clients  
  - base + clientOnly  
- client-fancy.zip - modpack installation for clients with beefier computers  
  - base + clientOnly + clientFancy  

<!---
guide to markdown formatting:
https://www.markdownguide.org/cheat-sheet/

Heading	
# H1
## H2
### H3

Bold	
**bold text**

Italic	
*italicized text*

Blockquote	
> blockquote

Ordered List	
1. First item
2. Second item
3. Third item

Unordered List	
- First item
- Second item
- Third item

Code	
`code`

Horizontal Rule	
---

Link	
[title](https://www.example.com)

Image	
![alt text](image.jpg)



---> 