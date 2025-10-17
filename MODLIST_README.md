# **Wolf's Personal Modlist**
---
This is my personal Modlist on the mods that I personally like to use on my Skyrim. Read this carefully since, it contains instructions for some mods that need to be added manually.

I have carefully read and made the whole list. You can download each mod seperately and modify it as you please.

**⚠️ No help will be provided if you choose to modify this list.**

I have provided instructions regarding how to install the mods since some mods will require you to manually install some optional files, along with fixes to some issues that can be easily resolved with out using external tools.
___
# **Types of Mods**
- **⚙️ Core Mods**
- **🔧 UI and System Overhauls**
- **🖼️ Textures**
- **💇🏼‍♀️ PC & NPC Overhauls**
- **🗒️ Quests & Followers**
- **👚 Clothes Replacer**
- **Animations**
- **🩹 Patches**
---

## **⚙️ Performance, Optimizations and Bug Fixes**
<b>

- [ ] [Skyrim Script Extender**](https://www.nexusmods.com/skyrimspecialedition/mods/30379?tab=description) (SKSE)
⚠️ Nothing will work without this. duh
⚠️ Sometimes Vortex doesn't install this mod correcctly in that case, manually install it via the instructions in the archive.

- [ ] [Unofficial Skyrim Special Edition Patch](https://www.nexusmods.com/skyrimspecialedition/mods/266) (USSEP)

- [ ] [Unofficial Skyrim Creation Club Content Patches](https://www.nexusmods.com/skyrimspecialedition/mods/18975) (USCCCP)

- [ ] [SSE Engine Fixes (skse64 plugin)](https://www.nexusmods.com/skyrimspecialedition/mods/17230?tab=files)
⚠️ Download the Main File via Vortex
⚠️ Manually install the preloader file by extracting it into Skyrim root folder should be right beside Skyrim.exe
⚠️ Option `AnimationLoadSignedCrash` must be disabled in the `EngineFixes.toml` inside SSE Engine Fixes if you plan to install Animation Limit Crash Fix.

- [ ] [Optional] [Animation Crash Limit Fix SSE](https://www.nexusmods.com/skyrimspecialedition/mods/31146?tab=description)
⚠️ Option `AnimationLoadSignedCrash` must be disabled in the `EngineFixes.toml` inside SSE Engine Fixes. This mod just increases the amount of NPC that can be animated at a time.

- [ ] [SSE Display Tweaks]()
⚠️ If you feature a bug where you can't use the keyboard, add the following lines at the bottom in `SSEDisplayTweaks.ini`.
```
[Bethesda.net]

bEnablePlatform=0
```
- [ ] [Scrambled Bugs](https://www.nexusmods.com/skyrimspecialedition/mods/43532?tab=posts)
⚠️ If you get a CTD, similar to this:
    `[2 ] 0x7FFEDFDE384C ScrambledBugs.dll+000384C ScrambledBugs::Fixes::ModArmorWeightPerkEntryPoint::GetInventoryWeight`
    `    [C:\SkyrimSE\ScrambledBugs\ScrambledBugs\SourceFiles\Fixes\ModArmorWeightPerkEntryPoint.cpp:140]`

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Or, if you use Ostim (a NSFW mod), then do the following:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Open `ScrambledBugs.json`
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Change `modArmorWeightPerkEntryPoint` to `false`
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. Save and close the file.

- [ ] [Bug Fixes SSE](https://www.nexusmods.com/skyrimspecialedition/mods/33261?tab=posts)

- [ ] [Address Library for SKSE Plugins](https://www.nexusmods.com/skyrimspecialedition/mods/32444?tab=files)

- [ ] [Papyrus Tweaks NG](https://www.nexusmods.com/skyrimspecialedition/mods/77779)

- [ ] [powerofthree's Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/51073) (PO3's Tweaks)

- [ ] [powerofthree's Papyrus Extender](https://www.nexusmods.com/skyrimspecialedition/mods/22854)

- [ ] [ConsoleUtilSSE NG](https://www.nexusmods.com/skyrimspecialedition/mods/76649)

- [ ] [Navigator - Nevmesh Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/52641?tab=description)

- [ ] [Navigator - Navmesh Fixes - Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/111379)

- [ ] [Ultimate Optimized Scripts Compilation](https://www.nexusmods.com/skyrimspecialedition/mods/49616) (UOSC)

- [ ] [Animated Staic Reload - NG](https://www.nexusmods.com/skyrimspecialedition/mods/69331?tab=description)
⚠️ If you get an error that this plugin failed to load, just uninstall it. I'm sure you can live with a small harmless bug.

- [ ] [Animation Queue Fix](https://www.nexusmods.com/skyrimspecialedition/mods/82395)
</b>

___
## **🔧 UI and Improvements**
## **🖼️ Textures**
- [ ] [Optional] [Unofficial performance optimized textures AKA (UPOT) (SSE-ANNIVERSARY editions)](https://www.nexusmods.com/skyrimspecialedition/mods/21166)
⚠️ A low-resolution texture pack I use to enhance my FPS since I have a potato PC.
## **💇🏼‍♀️ PC & NPC Overhauls**
## **🗒️ Quests & Followers**
## **👚 Clothes Replacer**
## **🩹 Miscelleneous Patches**
