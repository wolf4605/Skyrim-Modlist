# **Wolf's Personal Modlist**

This is my personal Modlist on the mods that I personally like to use on my Skyrim. Read this carefully since, it contains instructions for some mods that need to be added manually.

I have carefully read and made the whole list. You can download each mod seperately and modify it as you please.

**⚠️ No help will be provided if you choose to modify this list.**

I have provided instructions regarding how to install the mods since some mods will require you to manually install some optional files, along with fixes to some issues that can be easily resolved with out using external tools.

# **Types of Mods**
- ⚙️ [**Performance, Optimizations and Bug Fixes**](#️-performance-optimizations-and-bug-fixes)
- 🛠️ [**Tools**](#-tools)
- 🔧 [**UI and System Overhauls**](#-ui-and-improvements)
- 🖼️ [**Textures**](#️-textures)
- 💇🏼‍♀️ [**PC & NPC Overhauls**](#️-pc--npc-overhauls)
- 🗒️ [**Quests & Followers**](#️-pc--npc-overhauls)
- 👚 [**Clothes Replacer**](#-clothes-replacer)
- 💃 [**Animations**](#-animations)
- 🩹 [**Miscelleneous Patches**](#-miscelleneous-patches)

## **⚙️ Performance, Optimizations and Bug Fixes**
<b>

- [ ] [Skyrim Script Extender](https://www.nexusmods.com/skyrimspecialedition/mods/30379?tab=description) (SKSE)<br>
⚠️ Nothing will work without this. duh<br>
⚠️ Sometimes Vortex doesn't install this mod correcctly in that case, manually install it via the instructions in the archive.

- [ ] [Unofficial Skyrim Special Edition Patch](https://www.nexusmods.com/skyrimspecialedition/mods/266) (USSEP)

- [ ] [Unofficial Skyrim Creation Club Content Patches](https://www.nexusmods.com/skyrimspecialedition/mods/18975) (USCCCP)

- [ ] [Address Library for SKSE Plugins](https://www.nexusmods.com/skyrimspecialedition/mods/32444?tab=files)

- [ ] [PapyrusUtil SE - Modders Scripting Utility Functions]()

- [ ] [SSE Engine Fixes (skse64 plugin)](https://www.nexusmods.com/skyrimspecialedition/mods/17230?tab=files)<br>
⚠️ Download the Main File via Vortex<br>
⚠️ Manually install the preloader file by extracting it into Skyrim root folder should be right beside Skyrim.exe<br>
⚠️ Option `AnimationLoadSignedCrash` must be disabled in the `EngineFixes.toml` inside SSE Engine Fixes if you plan to install Animation Limit Crash Fix.

- [ ] [Optional] [Animation Crash Limit Fix SSE](https://www.nexusmods.com/skyrimspecialedition/mods/31146?tab=description)<br>
⚠️ Option `AnimationLoadSignedCrash` must be disabled in the `EngineFixes.toml` inside SSE Engine Fixes.

- [ ] [SSE Display Tweaks]()<br>
⚠️ If you feature a bug where you can't use the keyboard, add the following lines at the bottom in `SSEDisplayTweaks.ini`.
```
[Bethesda.net]

bEnablePlatform=0
```

- [ ] [Optional] [Actor Limit Fix](https://www.nexusmods.com/skyrimspecialedition/mods/32349)<br>
⚠️ Increases the amount of actors that can be animated at a time. Nothing else.

- [ ] [Scrambled Bugs](https://www.nexusmods.com/skyrimspecialedition/mods/43532?tab=posts)<br>
⚠️ If you get a CTD, similar to this:<br>
    `[2 ] 0x7FFEDFDE384C ScrambledBugs.dll+000384C`<br>`ScrambledBugs::Fixes::ModArmorWeightPerkEntryPoint::GetInventoryWeight`<br>
    `    [C:\SkyrimSE\ScrambledBugs\ScrambledBugs\SourceFiles\Fixes\ModArmorWeightPerkEntryPoint.cpp:140]`<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Or, if you use Ostim (a NSFW mod), then do the following:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Open `ScrambledBugs.json`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Change `modArmorWeightPerkEntryPoint` to `false`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. Save and close the file.

- [ ] [Bug Fixes SSE](https://www.nexusmods.com/skyrimspecialedition/mods/33261?tab=posts)

- [ ] [Papyrus Tweaks NG](https://www.nexusmods.com/skyrimspecialedition/mods/77779)

- [ ] [powerofthree's Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/51073) (PO3's Tweaks)

- [ ] [powerofthree's Papyrus Extender](https://www.nexusmods.com/skyrimspecialedition/mods/22854)

- [ ] [ConsoleUtilSSE NG](https://www.nexusmods.com/skyrimspecialedition/mods/76649)

- [ ] [Navigator - Nevmesh Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/52641?tab=description)

- [ ] [Navigator - Navmesh Fixes - Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/111379)

- [ ] [Ultimate Optimized Scripts Compilation](https://www.nexusmods.com/skyrimspecialedition/mods/49616) (UOSC)

- [ ] [Animated Staic Reload - NG](https://www.nexusmods.com/skyrimspecialedition/mods/69331?tab=description)<br>
⚠️ If you get an error that this plugin failed to load, just uninstall it. I'm sure you can live with a small harmless bug.

- [ ] [Animation Queue Fix](https://www.nexusmods.com/skyrimspecialedition/mods/82395)

- [ ] [Crash Logger SSE AE VR - PDB support](https://www.nexusmods.com/skyrimspecialedition/mods/59818)

- [ ] [Weapons Armor Clothing and Clutter Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/18994) (WACC)

- [ ] [JContainers SE](https://www.nexusmods.com/skyrimspecialedition/mods/16495)

- [ ] [RaceMenu](https://www.nexusmods.com/skyrimspecialedition/mods/19080)

- [ ] [XP32 Maximum Skeleton Special Extended - XPMSSE](https://www.nexusmods.com/skyrimspecialedition/mods/1988)

- [ ] [Better Dialogue Controls](https://www.nexusmods.com/skyrimspecialedition/mods/1429)

- [ ] [Better MessageBox Controls](https://www.nexusmods.com/skyrimspecialedition/mods/1428)

</br>

## 🛠️ Tools
<b>

- [ ] [BodySlide and Outfit Studio](https://www.nexusmods.com/skyrimspecialedition/mods/201)<br>
⚠️ Required for building Body and Clothes.

- [ ] [Project New Reign - Nemesis Unlimited Behavior Engine](https://www.nexusmods.com/skyrimspecialedition/mods/60033)<br>
⚠️ Required for generating skyrim animations.

- [ ] [Fores New Idles in Skyrim SE - FNIS SE](https://www.nexusmods.com/skyrimspecialedition/mods/3038)<br>
⚠️ Required for generating skyrim animations.<br>
⚠️ Either use this or Nemesis Unlimited Behhaviour Engine Personally I prefer Nemesis over FNIS.

</b>

## **🔧 UI and Improvements**
<b>

- [ ] [SkyUI](https://www.nexusmods.com/skyrimspecialedition/mods/12604)

- [ ] [SkyHUD](https://www.nexusmods.com/skyrimspecialedition/mods/463?tab=description)<br>
⚠️ Download the optional file too
- [ ] [Sneak Tools SE Edition](https://www.nexusmods.com/skyrimspecialedition/mods/1863)

</b>

## **🖼️ Textures**
<b>

- [ ] [Optional] [Unofficial performance optimized textures AKA (UPOT) (SSE-ANNIVERSARY editions)](https://www.nexusmods.com/skyrimspecialedition/mods/21166)<br>
⚠️ A low-resolution texture pack I use to enhance my FPS since I have a potato PC.

- [ ] []

</b>

## **💇🏼‍♀️ PC & NPC Overhauls**

<b>

- [ ] [CBBE 3BA](https://www.nexusmods.com/skyrimspecialedition/mods/30174) <span style="color: red;">[NSFW]</span><br>
⚠️ Use Nevernude Option in FOMOD for SFW version.

- [ ] [Caliente's Beautiful Bodies Enhancer -CBBE-](https://www.nexusmods.com/skyrimspecialedition/mods/198) <span style="color: red;">[NSFW]</span><br>
⚠️ Use Nevernude Option in FOMOD for SFW version.

- [ ] [SMP-NPC crash fix](https://www.nexusmods.com/skyrimspecialedition/mods/91616)

- [ ] [CBPC - Physics with Collisions for SSE and VR](https://www.nexusmods.com/skyrimspecialedition/mods/21224) <span style="color: red;">[NSFW]</span>

- [ ] [FSMP - Faster HDT-SMP](https://www.nexusmods.com/skyrimspecialedition/mods/57339)

- [ ] [HeelFix](https://www.nexusmods.com/skyrimspecialedition/mods/64442?tab=description)
⚠️ Use this inplace of [RaceMenu High Heels (Height Fixes)](https://www.nexusmods.com/skyrimspecialedition/mods/18045)
</b>

## **🗒️ Quests & Followers**
## **👚 Clothes Replacer**

<b>

- [ ] [Somewhere in Between - 3BA Armor compilation replacer](https://www.nexusmods.com/skyrimspecialedition/mods/98945?tab=files)<br>
⚠️Doesn't contain all armors and clothing. Not yet anyways.<br>
⚠️If you find some missing piece of armors, regenerate that specific armor piece in BodySlide instead of Batch Build.

- [ ] [BD's Armor and Clothes Replacer - CBBE 3BA (3BBB)](https://www.nexusmods.com/skyrimspecialedition/mods/32518) <span style="color: red;">[NSFW]</span><br>
⚠️<span style="color: red;">Warning: It contains really Skimpy Armors.<br>
⚠️ Only install one this or Somewhere in Between. Both are incompatible.</span>

- [ ] [CBBE 3BA Vanilla outfits redone](https://www.nexusmods.com/skyrimspecialedition/mods/109194?tab=files)
⚠️ For 3BA variants of clothes missing from Somewhere in Between.
</b>

## **💃 Animations**

<b>



</b>

## **🩹 Miscelleneous Patches**

<b>



</b>