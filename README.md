# Redoran-Extended---Survival Addon

![Image 0](https://i.imgur.com/JEG7wqm.png)

# Introduction

Hello! This addon will integrate various mods designed to expand survival themed gameplay into the world of Redoran-ified Skyrim. This will be a **manual process** with various steps involving downloading, rearranging, etc. A provided megapatch will be available at the end of the guide.

You can install this on an **EXISTING SAVE**.

**IMPORTANT** - Before installing, **please toggle Survival Mode to be OFF in-game** if you have not done so already. Installing SunHelm will disable Survival Mode automatically, but if you decide to disable SunHelm mid-game via the MCM menu, Survival Mode will automatically be re-enabled if you did not toggle it to be off. Since SunHelm also disables the UI option to turn Survival Mode on/off, it's best to toggle it to be off BEFORE installing SunHelm so you're not stuck with Survival Mode being on with no available off switch.

**Currently designed to work with version 1.4.2 of Redoran.** A changelog is provided at the bottom.

# Installation

First of all, we're going to right-click on the left side of MO2 and highlight the "All Mods" option, then click the dropdown of "Create separator above". We'll call it **[NoDelete] [04.000] REDORAN EXTENDED - SURVIVAL**. All of the following mods will be installed under this separator, and the separator itself will go just below the separator called "THE DANGER ZONE". 

All the plugins going forward will be at the very bottom, **BELOW all of the Redoran patches** but **BEFORE DynDOLOD.esp**.

Screenshots are available at the bottom of this page to compare as you go.

## Campfire

1.) Download [Campfire - Complete Camping System (Supports Skyrim VR)](https://www.nexusmods.com/skyrimspecialedition/mods/667?tab=files&file_id=65049&nmm=1). Once you've installed Campfire, double-click the mod on the left side of MO2. Under the Filetree tab, extended the SKSE folder, then the Plugins folder. Right-click PapyrusUtil.dll and select Hide.

![Image 1](https://i.imgur.com/dKe7v9g.png)

   - Install it under the name **[NoDelete] [04.001] Campfire**
   
2.) Download [Campfire - Unofficial SSE Update](https://www.nexusmods.com/skyrimspecialedition/mods/17925?tab=files&file_id=62581&nmm=1).

   - Install it under the name **[NoDelete] [04.002] Campfire - Unofficial Update**
   
3.) Download [Campfire - Bits and Pieces Hoarding Fix](https://www.nexusmods.com/skyrimspecialedition/mods/69705?tab=files&file_id=292810&nmm=1).

   - Install it under the name **[NoDelete] [04.003] Campfire - Bits and Pieces Hoarding Fix**

4.) Download [Campfire - Hotkey Modded Menu Fix](https://www.nexusmods.com/skyrimspecialedition/mods/73343?tab=files&file_id=307622&nmm=1).

   - Install it under the name **[NoDelete] [04.004] Campfire - Hotkey Modded Menu Fix**
   
5.) Download [Eremite Camping and Combat v2.24](https://www.dracotorre.com/mods/eremitecamping/). Scroll down to the section under "download" and select the "main file - Eremite Camping and Combat v2.24 (2022-07-12) - EremiteCamping.7z (6.6 MB)" option. Place the newly downloaded file into the area where you designated Redoran's Download folder to go. Once placed, you should see it on the right side of MO2 in the downloads tab with a red triangle next to the name. If it isn't, sort by Filetime (may need to do it twice) and it will flip the downloads to most recent. If it still isn't showing, tick the Hidden Files box at the bottom of the Downloads tab. Once you see the file, double-click it, then proceed to installation.

   - Install it under the name **[NoDelete] [04.005] Eremite Camping**

6.) Download [Campfire - Fixation](https://www.nexusmods.com/skyrimspecialedition/mods/56595?tab=files&file_id=248879&nmm=1).

   - Install it under the name **[NoDelete] [04.006] Campfire - Fixation**
   
7.) Download [Campfire - Stamina Penalty for Backpacks](https://github.com/Foamimi/Redoran-Extended---Survival/blob/main/Campfire%20-%20Stamina%20Penalty%20for%20Backpacks.7z) ("View raw" button).

   - Install it under the name **[NoDelete] [04.007] Campfire - Stamina Penalty for Backpacks**

8.) Download [ElSopa - Campfire HD SE](https://www.nexusmods.com/skyrimspecialedition/mods/24511?tab=files&file_id=86443&nmm=1).

   - Install it under the name **[NoDelete] [04.008] ElSopa - Campfire HD**
   
9.) Download [Realistic HD Woodcutter's Axe Remastered - Campfire Patch](https://www.nexusmods.com/skyrimspecialedition/mods/7849?tab=files&file_id=78733&nmm=1).

   - Install it under the name **[NoDelete] [04.009] Realistic HD Woodcutter's Axe Remastered - Campfire Patch**

10.) Download [Campfire - Backpack HD](https://www.nexusmods.com/skyrimspecialedition/mods/34516?tab=files&file_id=133862&nmm=1). In the FOMOD, tick both Backpack and Bedroll options. Select Waterskin + Amulet, then press Next. Select 2k, 2k, 2k, then press Install.

   - Install it under the name **[NoDelete] [04.010] Campfire - Backpack HD**
   
11.) Download [Campfire - Torch Fix](https://www.nexusmods.com/skyrimspecialedition/mods/35563?tab=files&file_id=137876&nmm=1).

   - Install it under the name **[NoDelete] [04.011] Campfire - Torch Fix**

12.) Download [CC Fishing Campfire Patch](https://www.nexusmods.com/skyrimspecialedition/mods/63418?tab=files&file_id=302078&nmm=1).

   - Install it under the name **[NoDelete] [04.012] CC Fishing Campfire Patch**
   
13.) Download [Campfire - Pilgrim Patch](https://www.nexusmods.com/skyrimspecialedition/mods/57888?tab=files&file_id=238857&nmm=1).

   - Install it under the name **[NoDelete] [04.013] Campfire - Pilgrim Patch**

14.) Download [Lanterns Of Skyrim II - Campfire Addon](https://www.nexusmods.com/skyrimspecialedition/mods/30817?tab=files&file_id=275523&nmm=1). If you did not delete your downloads folder for Redoran, you may have this installed already. Select No to the MO2 pop-up if you receive one. On the right side of MO2 in the Downloads tab, type in "Lanterns Of Skyrim" and one file should appear. Double-click it to begin. When the FOMOD pops up, go to the bottom left corner and select Manual.

![Image 2](https://i.imgur.com/vpJxSHY.png)

Right-click LoS II - Campfire Addon, and select Set as data directory. 

![Image 3](https://i.imgur.com/jaFP34j.png)

You should then be at a page like below. Rename the file to the name below and press Ok. Then you're done!

![Image 4](https://i.imgur.com/z2NyPWY.png)

   - Install it under the name **[NoDelete] [04.014] Lanterns Of Skyrim II - Campfire Addon**
   
15.) Download [Campfire Chanterelle Tree Patch](https://www.nexusmods.com/skyrimspecialedition/mods/51194?tab=files&file_id=209106&nmm=1).

   - Install it under the name **[NoDelete] [04.015] Campfire Chanterelle Tree Patch**

## SunHelm

16.) Download [SunHelm Survival](https://www.nexusmods.com/skyrimspecialedition/mods/39414?tab=files&file_id=311142&nmm=1). In the FOMOD, select Next, tick the Campfire Skill Tree and Diseases boxes, select SkyrimSE, then press Next. Only tick the Wyrmstooth Region Patch, then press Install.

   - Install it under the name **[NoDelete] [04.016] SunHelm Survival**
   
17.) Download [SunHelm Survival - Settings Loader](https://www.nexusmods.com/skyrimspecialedition/mods/78535?tab=files&file_id=330873&nmm=1).

   - Install it under the name **[NoDelete] [04.017] SunHelm Survival - Settings Loader**

18.) Download [SunHelm Survival - Compatibility Patches](https://www.nexusmods.com/skyrimspecialedition/mods/41335?tab=files&file_id=168682&nmm=1). In the FOMOD, everything will be ticked automatically, however, we will want to untick the Wyrmstooth patch as the one we installed previously is more up-to-date. Once you have done so select Next, don't tick anything on the last page, then press Install. 

   - Install it under the name **[NoDelete] [04.018] SunHelm Survival - Compatibility Patches**
   
19.) Download [Water-Borne Diseases for SunHelm](https://www.nexusmods.com/skyrimspecialedition/mods/62572?tab=files&file_id=259778&nmm=1).

   - Install it under the name **[NoDelete] [04.019] Water-Borne Diseases for SunHelm**

20.) Download [Water-Borne Diseases for SunHelm - Campfire Patch](https://www.nexusmods.com/skyrimspecialedition/mods/69235?tab=files&file_id=289380&nmm=1).

   - Install it under the name **[NoDelete] [04.020] Water-Borne Diseases for SunHelm - Campfire Patch**
   
21.) Download [SunHelm - Simple Weather Icons](https://www.nexusmods.com/skyrimspecialedition/mods/75863?tab=files&file_id=318218&nmm=1).

   - Install it under the name **[NoDelete] [04.021] SunHelm - Simple Weather Icons**

22.) Download [SunHelm - Magical Heat Sources](https://www.nexusmods.com/skyrimspecialedition/mods/67864?tab=files&file_id=282870&nmm=1).

   - Install it under the name **[NoDelete] [04.022] SunHelm - Magical Heat Sources**

23.) Download [SkyUI Item Card Fixes for SunHelm](https://www.nexusmods.com/skyrimspecialedition/mods/29116?tab=files&file_id=108005&nmm=1). In the FOMOD, select Sovngarde ItemCard Fixes within the Without Frostfall section, then select None in the bottom section, then press Install.

   - Install it under the name **[NoDelete] [04.023] SkyUI Item Card Fixes for SunHelm**
   
24.) Download [More Wells for SunHelm - Vanilla](https://www.nexusmods.com/skyrimspecialedition/mods/62447?tab=files&file_id=258959&nmm=1).

   - Install it under the name **[NoDelete] [04.024] More Wells for SunHelm - Vanilla**

25.) Download [SunHelm - Creation Club Farming Patch](https://www.nexusmods.com/skyrimspecialedition/mods/62480?tab=files&file_id=259142&nmm=1).

   - Install it under the name **[NoDelete] [04.025] SunHelm - Creation Club Farming Patch**
   
26.) Download [Gray Cowl of Nocturnal - SunHelm Patch](https://www.nexusmods.com/skyrimspecialedition/mods/65623?tab=files&file_id=300063&nmm=1).

   - Install it under the name **[NoDelete] [04.026] Gray Cowl of Nocturnal - SunHelm Patch**

27.) Download [Midwood Isle - SunHelm Bucket - Patch](https://www.nexusmods.com/skyrimspecialedition/mods/64322?tab=files&file_id=267231&nmm=1).

   - Install it under the name **[NoDelete] [04.027] Midwood Isle - SunHelm Bucket Patch**

28.) Download [Igniting Animation for Campfire](https://www.nexusmods.com/skyrimspecialedition/mods/83142?tab=files&file_id=353695&nmm=1).

   - Install it under the name **[NoDelete] [04.028] Igniting Animation for Campfire - DAR**
   - **IMPORTANT** - No need to re-run Nemesis as this is a DAR mod and it works straight out of the box!

29.) Download [Patch for Sunhelm Survival and CCARA DAR](https://www.nexusmods.com/skyrimspecialedition/mods/62133?tab=files&file_id=258265&nmm=1).

   - Install it under the name **[NoDelete] [04.029] Patch for Sunhelm Survival and CCARA DAR**
   - **IMPORTANT** - No need to re-run Nemesis as this is a DAR mod and it works straight out of the box!

## OPTIONAL (FEEL FREE TO SKIP!)

30.) Download [Campfire Spooning](https://www.nexusmods.com/skyrimspecialedition/mods/21776?tab=files&file_id=75101&nmm=1).

   - Install it under the name **[NoDelete] [04.030] Campfire Spooning**

31.) Download [Campfire - Immersive Snuggling](https://www.nexusmods.com/skyrimspecialedition/mods/26975?tab=files&file_id=97433&nmm=1).

   - Install it under the name **[NoDelete] [04.031] Campfire - Immersive Snuggling**

32.) Download [SunHelm - Ultrawide Patch](https://www.nexusmods.com/skyrimspecialedition/mods/85961?tab=files&file_id=364071&nmm=1).

   - Install it under the name **[NoDelete] [04.032] SunHelm - Ultrawide Patch**

# Last Steps

### Snag the megapatch from here: [ [DOWNLOAD](https://github.com/Foamimi/Redoran-Extended---Survival/blob/main/Redoran%20Extended%20-%20Survival%20Megapatch.7z) ] ("View raw" button)

Name it **[NoDelete] [04.033] Redoran Extended - Survival Megapatch**, and place it directly AFTER [NoDelete] [04.032] SunHelm - Ultrawide Patch. If you did not install the optional mods, then place it directly AFTER [NoDelete] [04.029] Patch for Sunhelm Survival and CCARA DAR.

   -  Then here's how the Mod Name tab on the **left side of MO2** should look (ignore the optional mods if you skipped that part):

![Image 5](https://i.imgur.com/TdAAwTe.png)

   - Then here's how the Plugin tab on the **right side of MO2** should look (ignore the optional mods if you skipped that part):

![Image 6](https://i.imgur.com/y4fx1SZ.png)

![Image 7](https://i.imgur.com/krqKC9J.png)

### Then you are SET! Thanks for sticking with it the entire process, enjoy your game!

# Addon Compatibility

   - **Currently works with [Redoran-Extended - NPC Overhaul Addon](https://github.com/Foamimi/Redoran-Extended---NPC-Overhaul/blob/main/README.md).**
   - **Currently needs a patch to work with [Redoran-Extended - NPC Dialogue Addon](https://github.com/Foamimi/Redoran-Extended---NPC-Dialogue/blob/main/README.md).** To install the patch, go back to step #11 Serana Dialogue Add-On Patch Hub via the NPC Dialogue page. In the FOMOD, select Next, Next, tick the Campfire patch on the 3rd page then select Next, tick the following patches: NPCs Wear Amulets of Mara and Remiel. Then press Next. On the Feature Preference Patches page I personally tick the Clothed Sleep Patch, but I'll leave that option up to you. Either way, if you decide to tick it or not, it will not affect the megapatch in the end. Press Next one more time, then hit Install. Place the new SDA Campfire .esp below the other patches from that same FOMOD.
   - **Currently needs a patch to work with [Redoran-Extended - Textures Addon](https://github.com/Foamimi/Redoran-Extended---Textures/blob/master/README.md).** Download [HPP - My Fixes by Xtudo - AIO Campfire](https://www.nexusmods.com/skyrimspecialedition/mods/63425?tab=files&file_id=333337&nmm=1) and name it [NoDelete] [04.034] [HPP - My Fixes by Xtudo - AIO Campfire]. Place it after [NoDelete] [04.033] Redoran Extended - Survival Megapatch on the left side of MO2, and after Redoran Extended - Survival Megapatch.esp on the right side of MO2.

Left side of MO2 (ignore the incorrect numbering):

![Image 8](https://i.imgur.com/Twrm4Nu.png)

Right side of MO2:

![Image 9](https://i.imgur.com/VA1Kvfc.png)

### If using multiple addons, please see the image below for load order guidance:

![Image Addon Load Order](https://i.imgur.com/QA9N71C.png)

# Changelog 

**IMPORTANT** - If updating Redoran (like from v.1.0.1 to 1.0.2 for example) your load order may become a bit funky on the right side of MO2. Luckily we numbered everything while installing, so the left side of MO2 should still be in tact, but to get everything back in position for the right side, I'd suggest disabling the entire Survival addon, then re-enabling everything again one by one. This takes a hot second, but I find this method to be the fastest (for me anyway!).

Redoran v1.4.2
   - Moved SkyUI Item Card Fixes for Campfire to step #23 and renamed to SkyUI Item Card Fixes for SunHelm
   - Added Igniting Animation for Campfire
   - Added Patch for Sunhelm Survival and CCARA DAR
