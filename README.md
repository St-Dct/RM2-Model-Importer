EN only now.

# Redmatch-2-Model-Importer (RM2MI)
Tools and instructions for importing custom models into Redmatch 2. (RM2)

RM2MI is a version of GIMI and 3DMigoto that I have modified to be compatible with RM2.(only config, so.)

 Feel free to use or modify any of the scripts on this repo as you wish, though please give credit if you use these programs in your projects. I am continuing to update this page with new features and fixes, so check back often.

# IMPORTANT BUGS
- Textures and UV-maps are broken
- on Linux RM2MI is loading, but not working (I guess from vulcan, and as I tested it)

# To create your own mod tutorials (we dont have a guides for rm2 yet, but guides for GIMI is working):
For a simple walkthrough of removing a portion of a character mesh using these tools, see [Mona Walkthrough](Guides/MonaWalkthrough.md). For an intermediate walkthrough of creating custom weapons, see [Custom Weapon Modding Walkthrough](Guides/BananaWeaponWalkthrough.md). For a more advanced example of importing a custom model, see Cybertron's great video walkthrough [here](https://www.youtube.com/watch?v=7ijMOjhEvBw) and SinsOfSeven#3164 annotated transcript and troubleshooting guide [here](https://rentry.co/3dmigPlug_AnimeGame).

## Installation Instructions (3DMigoto\GIMI)

1. Download a 3dmigoto .zip from [releases](https://github.com/St-Dct/RM2-Model-Importer/releases) and extract it.

2. Extract all from .zip to RM2 root folder. If everything is correct so far, 3DMigoto should be injected into the game and you should see a green text overlay (only if using the "for development" version, the "for playing" version does not show the green text):

![image](https://raw.githubusercontent.com/St-Dct/RM2-Model-Importer/refs/heads/main/imgs/rm2root.png)

<img src="https://user-images.githubusercontent.com/107697535/174325193-1f58ab2c-86f8-4ce9-8697-6e7d140b2014.png" width="800"/> (no image or rm2 yet)

4. Installation complete! You should now be able to load custom resources and override textures and shaders with 3DMigoto. To add mods, place them in the ModZ folder (one mod per character at a time) and press F10 to load them in game:

![image](https://user-images.githubusercontent.com/107697535/175611402-c3f600ca-4136-4561-b33a-f4edf6153d1a.png)

&nbsp;
## Installation Instructions (3DMigoto Blender Plugin)

In order to modify game models, you need to also setup your Blender plugins and environment. The 3DMigoto plugin works with Blender 2.80+

1. Download and install Blender

2. Download and install the modified 3DMigoto plugin (blender_3dmigoto_gimi.py) from [releases](https://github.com/SilentNightSound/GI-Model-Importer/releases). You can install an add-on in Blender by going to Edit -> Preferences -> Add-Ons -> Install, then selecting the .py file. 

3. If done correctly, you should see 3dmigoto in the plugin list as well as new options in the import and export menus

<img src="https://user-images.githubusercontent.com/107697535/174328624-ccb14ded-57b2-4ac7-b0a0-0de118119174.png" width="800"/>

<img src="https://user-images.githubusercontent.com/107697535/174329025-981a1a9f-7c56-4f44-804b-1b0394b8bd33.png" width="800"/>

&nbsp;
## Usage Instructions

See [Usage Instructions](Guides/UsageInstructions.md)

Also, if you any questions about modding come join the Genshin modding discord at https://discord.gg/gR2Ts6ApP7. The only verification is that you can 3dmigoto GIMI working by following the steps above.

&nbsp;
## Acknowledgements

Huge thank you to SilentNightSound for GIMI & DarkStarSword, bo3b and Chiri for 3dmigoto!
