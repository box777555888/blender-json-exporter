# NOTICE
As of 16 Feb 2026, this script is no longer the primary maintained version. 
The original author has since released an official Python3 port here:
[ORIGINAL](https://github.com/Epic-Fight/blender-json-exporter)

Please use that repository instead.




# Epic Fight Animation & Model exporter
This is my Blender `>2.8` fork of the Epic Fight Mod Blender export add-on originally written by [Yesman](https://github.com/Yesssssman).     
Blender `2.79` and below used python2 syntax. From `2.8` onwards they moved to python3 and had some changes in the API.      
Tested on Blender `2.8`, `3.6`, `4.0.1` and `4.1.1`. 
Should not have any issues on future versions unless the Blender API changes drastically or python4 is released.  
It will ignore exporting IK bones to prevent errors, so best to bake your animation and play it before you export it.

## Installation
1. Download the release.
2. Import it to Blender through Edit > Preferences > Add-ons > Install... > Select the .zip file
3. Make sure the add-on is enabled.
4. File > Export > menu should now contain `Animated Minecraft Model(.json)`

## Support
I'm in the [EFM discord server](https://discord.com/invite/NbAJwj8RHg) > Epic Fight Animation files thread is pinned in the #forums channel. Do not ask metal or Yesman for support for this version of the script. 

## Changelog
1.3: Added check for blender version to determine if calculating normals is needed (handled automatically in Blender 4.1.x)  
1.2: Fixed UV caused deformed mapping on the torso   
1.1: Armature and mesh exports will now be unchecked by default. Rewrite of export_mesh() to fix an error while exporting mesh.     
1.0: Ported python2 syntax to python3  
