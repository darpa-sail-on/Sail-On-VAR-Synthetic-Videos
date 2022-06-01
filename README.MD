# Summary

This repository is used for the purpose of storing and cataloging all of the synthetic video clips created for use in the SAIL-ON project's Video Activity Recognition Domain.

Each class/sub class has its own folder, and within each will be a text file detailing the naming convention, items used, in game location recorded at, etc so that they can be recreated.

## File Organization
The top level folders are the individual class names given to the video sets. WIthin each class folder, are folders for the game in which the videos were recorded. (Example: Swimming/GTA/clip.mp4). SOme classes may be firther sub-divided into differetn categories for convenience.

Also included in these folders are some extra files to help with figuring out how to recreate the settings used to record each set of clips.

In the misc folder are the character presets created for and used in recording the present clips in Skyrim and Fallout 4, which can be used in conjunction with the RaceMenu mods for each respective game, as well as a python script used to generate the annotations for these files, based on the annotation constraints file used for the domain.

For Skyrim, these preset files go into: "Skyrim Special Edition\Data\SKSE\Plugins\CharGen\Presets"
For Fallout, they go into: "Fallout 4\Data\F4SE\Plugins\F4EE\Presets"

# Recording Process

These instructions will provide a general guide for how these clips were recorded and the tools used to create them. For videos recorded using Elder Scrolls V: Skyrim, and Fallout 4, various user created game mods were used to assist in setup.

## Software
### 1) OBS (Open Broadcaster Software)
OBS ([Download here](https://obsproject.com/)) is a free streaming/screen recording software tool, which was used to capture the in game videos found here. See the Setup section below for how OBS was set up to record in game clips.

### 2) Steam
Steam ([Download here](https://store.steampowered.com/about/)) is a digital video game marketplace where the various games used to record can be purchased and installed.

### 3) Games Used
The following games were used to perform actions in and record video clips.
Grand Theft Auto 5 ([Store Page](https://store.steampowered.com/app/271590/Grand_Theft_Auto_V/))
The Elder Scrolls V: Skyrim Special Edition ([Store Page](https://store.steampowered.com/app/489830/The_Elder_Scrolls_V_Skyrim_Special_Edition/))
Fallout 4 ([Store Page](https://store.steampowered.com/app/377160/Fallout_4/))

### 4) Vortex
In order to set up certain scenarios for recording, increase visual quality, and improve general game performance, many user created game add-ons (or 'mods') were used. In order to properly manage and keep track of these mods, a mod manager was used. Nexus is a website which hosts a large swath of these user created mods, so their manager was used. [Download the manager here](https://www.nexusmods.com/about/vortex/)

### 5) Mod lists
Below are lists of urls for all of the various mods used throughout the process of recording clips in this repository. Mods were only used with Skyrim and Fallout 4. For all of these it is recommended to read their descriptions and usage guide's in order to understand what they do and how best to utilize them. For any new set of recordings, new functionality not present in the game may be desired, and therefore new mods may be necessary.

DISCLAIMER: These are user created and curated. We are not affiliated with or in contact with the mod authors showcased here. They have complete rights and control over the mod pages listed. Some of the mods in these lists contain optional content that would be considered 18+, or could be changed to incude 18+ content. Please keep that in mind as you navigate to these mods. 

Skyrim:  
[ACC - Autorun Console Commands](https://www.nexusmods.com/skyrimspecialedition/mods/24919)  
[Address Library for SKSE Plugins](https://www.nexusmods.com/skyrimspecialedition/mods/32444?tab=files)  
[BodySlide and Outfit Studio](https://www.nexusmods.com/skyrimspecialedition/mods/201)  
[Caliente's Beautiful Bodies Enhancer -CBBE-](https://www.nexusmods.com/skyrimspecialedition/mods/198)  
[Clean Save Collection - Main Quest Complete](https://www.nexusmods.com/skyrimspecialedition/mods/45425)  
[ConsoleUtilSSE](https://www.nexusmods.com/skyrimspecialedition/mods/24858)  
[Dynamic Animation Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/33746)  
[Dynamic Distant Objects LOD - DynDOLOD](https://www.nexusmods.com/skyrimspecialedition/mods/32382)  
[Enhanced Lights and FX](https://www.nexusmods.com/skyrimspecialedition/mods/2424)  
[Fores New Idles in Skyrim SE - FNIS SE](https://www.nexusmods.com/skyrimspecialedition/mods/3038)  
[Footprints](https://www.nexusmods.com/skyrimspecialedition/mods/3808)  
[Go to bed](https://www.nexusmods.com/skyrimspecialedition/mods/4224)  
[Immersive HUD - iHUD Special Edition](https://www.nexusmods.com/skyrimspecialedition/mods/12440)  
[KS Hairdos SSE](https://www.nexusmods.com/skyrimspecialedition/mods/6817)  
[Majestic Mountains](https://www.nexusmods.com/skyrimspecialedition/mods/11052)  
[MCM Helper](https://www.nexusmods.com/skyrimspecialedition/mods/53000)  
[PapyrusUtil SE - Modders Scripting Utility Functions](https://www.nexusmods.com/skyrimspecialedition/mods/13048)  
[Playable Monster Mod](https://www.nexusmods.com/skyrimspecialedition/mods/13108)  
[Proper Length Arrows](https://www.nexusmods.com/skyrim/mods/5164)  
[RaceMenu](https://www.nexusmods.com/skyrimspecialedition/mods/19080)  
[Realistic Ragdolls and Force SE](https://www.nexusmods.com/skyrimspecialedition/mods/1439)  
[Realistic Water Two SE](https://www.nexusmods.com/skyrimspecialedition/mods/2182)  
[Skyrim Script Extender (SKSE)](https://skse.silverlock.org/)  
[Skyrim Flora Overhaul SE](https://www.nexusmods.com/skyrimspecialedition/mods/2154)  
[Skyrim SE Controller Interface Fix](https://www.nexusmods.com/skyrimspecialedition/mods/1147)  
[SkyUI](https://www.nexusmods.com/skyrimspecialedition/mods/12604)  
[Static Mesh Improvement Mod - SMIM](https://www.nexusmods.com/skyrimspecialedition/mods/659)  
[SmoothCam](https://www.nexusmods.com/skyrimspecialedition/mods/41252)  
[Smooth Combat - Non Combat Animation System](https://www.nexusmods.com/skyrimspecialedition/mods/45221)  
[Stronger Swimming Animation SE](https://www.nexusmods.com/skyrimspecialedition/mods/32625)  
[Tempered Skins for Females CBBE](https://www.nexusmods.com/skyrimspecialedition/mods/8505?tab=files&file_id=167956&nmm=1)  
[Tempered Skins for Males - Dressed Version](https://www.nexusmods.com/skyrimspecialedition/mods/7902?tab=files&file_id=162982&nmm=1)  
[True Directional Movement - Modernized Third Person Gameplay](https://www.nexusmods.com/skyrimspecialedition/mods/51614)  
[Unofficial Skyrim Special Edition Patch](https://www.nexusmods.com/skyrimspecialedition/mods/266)  
[Vivid Weathers - Definitive Edition](https://www.nexusmods.com/skyrimspecialedition/mods/2187)  
[Woodchop Freecam](https://www.nexusmods.com/skyrimspecialedition/mods/23994)  
[Wood Chopping To Max Carry Weight](https://www.nexusmods.com/skyrimspecialedition/mods/4443)  


Fallout 4:  
[AnimalArmors](https://www.nexusmods.com/fallout4/mods/24667)  
[Better Console - F4SE](https://www.nexusmods.com/fallout4/mods/26582)  
[BodySlide and Outfit Studio](https://www.nexusmods.com/fallout4/mods/25)  
[Caliente's Beautiful Bodies Enhancer -CBBE-](https://www.nexusmods.com/fallout4/mods/15)  
[Complete Vanilla Save](https://www.nexusmods.com/fallout4/mods/9200)  
[Custom Camera](https://www.nexusmods.com/fallout4/mods/29905)  
[Driveable Motorcycle Mod](https://www.nexusmods.com/fallout4/mods/21899)  
[Enhanced Lights and FX](https://www.nexusmods.com/fallout4/mods/13596)  
[Enhanced Vanilla Bodies-NeverNude Male](https://www.nexusmods.com/fallout4/mods/22110?tab=files&file_id=90290&nmm=1)  
[Fallout 4 Script Extender (F4SE)](https://f4se.silverlock.org/)  
[Green Commonwealth - Performance Friendly Grass Mod](https://www.nexusmods.com/fallout4/mods/11623)  
[LooksMenu](https://www.nexusmods.com/fallout4/mods/12631)  
[Mod Configuration Menu](https://www.nexusmods.com/fallout4/mods/21497)  
[No Throwing Arc - Demolition Expert Perk](https://www.nexusmods.com/fallout4/mods/11794)  
[NSA No Settlement Attacks](https://www.nexusmods.com/fallout4/mods/11317)  
[PipboyRemover](https://www.nexusmods.com/fallout4/mods/13603)  
[Place Everywhere](https://www.nexusmods.com/fallout4/mods/9424)  
[Real Throwing Weapons](https://www.nexusmods.com/fallout4/mods/35800)  
[Realistic Jumping and Falling](https://www.nexusmods.com/fallout4/mods/1674)  
[Scrap Everything](https://www.nexusmods.com/fallout4/mods/5320)  
[See you sleep](https://www.nexusmods.com/fallout4/mods/18324)  
[Springtime Trees](https://www.nexusmods.com/fallout4/mods/15421)  
[Throwing Weapons In Fallout 4 (Bricks Included)](https://www.nexusmods.com/fallout4/mods/8794)  
[Throwing Weapons Westored](https://www.nexusmods.com/fallout4/mods/13771)  
[Unofficial Fallout 4 Patch](https://www.nexusmods.com/fallout4/mods/4598)  
[Water Enhanced - 4K Water](https://www.nexusmods.com/fallout4/mods/3281)  


## Setup

### Game Setup
Once a game is installed, launch it normally through steam to access a small menu. Hit Options, and in the pop up, check Windowed Mode, then uncheck Borderless. Set Detail for the highest setting possible, and change Resolution to a smaller size to minimize video downscaling for recordings.

### Vortex and Mod Installation
For setup instructions and how to use Vortex, as well as tutorials on how to install game mods, use [this youtube video guide playlist](https://www.youtube.com/playlist?list=PLE7DlYarj-DfYgxma5znKGYEqAHDU_WU-)

### OBS
Once OBS is installed, there will be some key settings that need to be configured to match what was used during the recording process.

1) Once launched, navigate to File > Settings > Output > Recording  
    a) Customize Recording Path  
    b) Recording Format: mp4  
    c) Rescale Output: unchecked  
    d) Rate Control: CBR  
    e) Bitrate: 500 Kbps  
    f) Preset: Max Quality  
2) Navigate from Output to Video and customize the settings as follows:  
    a) Base (Canvas) Resolution: (Match this to the game screen resolution, while maintaining a 4:3 aspect ratio)  
    b) Output (Scaled) Resolution: 320x240  
    c) Downscale Filter: Lanczos (Sharpened scaling, 36 samples)  
    d) Integer FPS Value: 25  
3) Optionally, hotkeys can also be assigned to easily start/stop recording without having to navigate to OBS by navigating from Video to Hotkeys right below it and setting hotkeys for Start Recording and Stop Recording  
4) Now set up the actual game capture by doing the following:  
    a) Outside of settings, in the main window, go to the Soruces box  
    b) Click the + sign and select Game Capture  
    c) Create New and name apropriately  
    d) For Mode, select Capture Specific Window  
    e) Select game from Window list (game must be launched to be present)  
    f) Window Match Priority: Match title, otherwise find window of same executable  
    g) Uncheck all except Limit capture framerate  
    h) Hook Rate: Normal (recommended)  
5) Also optionally, an output timer can be set so that OBS automatically stops recording a clip after a specified timeframe by going to Tools > Output Timer and customizing the "Stop recording after:" setting.  
6) Optionally mute sound in the recordings by hitting the Mute icons in the Audio Mixer section.  

## In Game setup

Once all of the required software is installed and properly set up, the process of determining what to record can begin. 

Much of this process is dependant on the needs of the class being recorded for and the novelties being focused on. Some key recommendations though are as follows:  
  
1) Study the world map and find an ideal location.  
2) Plan ahead which character presets you will use, in game objects, actions, clothing, perspectives, etc.  
3) Create a filming set. Remember that recording in video games is more akin to live action. You as the player control the character, and need to act out the part.  
4) For some activities, using a game controller will give you more control over the character while recording  
5) Be sure to hide all traces of the games User Interface from the recording window as shown in the preview pane in OBS.  

From here, the recording process for Skyrim and Fallout are different from that of GTA V, so they will require different instructions.  

### Skyrim and Fallout 4

For some clips, you will want to use a free camera. Others may call for the third person perspective following the player. In order to access the fre camera, as well as other developer tools to modfy the world in-game, use the ~ key. From here you will have access to the games developer console. Some key commands include 'tfc' (Toggle Free Camera), 'tm' (Toggle Menu's. Note this also hides the developer console), tgm (Toggle God Mode), and 'showracemenu' (skyrim) or 'showlooksmenu' (fallout). For an exhuastive list of console commands and how to use them, use [this guide for Skyrim](https://elderscrolls.fandom.com/wiki/Console_Commands_(Skyrim)) and [this guide for Fallout 4](https://fallout.fandom.com/wiki/Fallout_4_console_commands).

It is also recommended to take advantage of the quick save and quick load features as you make any changes to the games state in case the game breaks or becomes unstable as a result of using console commands.

As a last recommendation, use the character presets provided to quickly and easily swap between character models when recording sets of videos.

Finally, to actually record in these games, just simply line everything up, hit the start recording hotkey, and perform the activity in game. There are a lot of different approaches that can be taken to speed up the process such as grouping different types of novelties, together per character before switching to a new one. Changing characters will be the slowest part of the process (other than switching locations), so do as many recordings with a given character in a given location as needed before moving on ot the next one.

### GTA V

The process for GTA is a bit different in that there is a proper theater mode in this game that can be taken advantage of called the Rockstar Editor, as well as a director mode that lets you customize certain aspects of the game's world environment. In addition, while GTA does have a character selector, the options are more limited and it is harder to do things like change clothing, gear, etc. You can create more characters using GTA Online, but can only save up to 2 at a time.

Once you are ready and have your scene and character set up in Director Mode to record though, set up the in game recording, and then perform the action (or actions). The game will typically save up to 2 minutes worth or so, but you can also stop the recording earlier if desired. Once finished, exit from Director Mode and navigate to the Theater Mode, and select your latest clip. From here, you will have access to what is essentially a recoridng of not just the game screen, but the actual game world during the time recorded, which will allow for a large variety of alteration and customization in camera perspective. Make the most of each game recording, as switching between modes takes a significant amount of time. 

To actually record the clips for usage, just like for Skyrim and Fallout, line everything up, press play on the video in game, and then press the start recording hotkey.

For a full guide on how to access and use these modes and the features they offer, use these youtube guides:   
[Director Mode Guide](https://www.youtube.com/watch?v=fZe1Gh4eukU)  
[Rockstar Editor Guide](https://www.youtube.com/watch?v=zShrh6YG8dQ)  

## Naming conventions

Come up with a good, easy to sort through, naming convention for the video clips before hand. OBS will automatically name each clip with its timestamp. In order to prevent mix up and user error, name the videos as they are recorded, or in batches as they are recorded.

### Credits

This effort was overseen by Adam Kaufman as part of PAR Government's contributions to the Sail-On Project under DARPA through the Video Activity Recognition domain.

Videos in this dataset were recorded by:  
Adam Kaufman  
Braeden Bowen  
Brendon Grates  
Connor Wyman  
Ed Reznichenko  
Kayla Cull
