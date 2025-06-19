# GTA V Gameconfig.xml

Add-on mods in GTA V typically require a modified gameconfig.xml to increase various memory pool limits. 
This repository serves as a central location for known-working gameconfig files for each GTA V update.
This gameconfig is generally kept in sync with the version included with [RDE 4](https://www.gta5-mods.com/misc/realism-dispatch-enhanced).

The [versions](versions) folder has a folder for each supported GTA V build number, containing the gameconfig.xml for 
that game version. For the latest game version, check the [releases](https://github.com/pnwparksfan/gameconfig/releases). 

## LML Installation instructions
 1. Open the Mod Manager UI
 2. Go to [the download page](https://www.lcpdfr.com/downloads/gta5mods/misc/24718-gameconfigxml-for-lml/) on lcpdfr.com
 3. Click "Download with Mod Manager"
 4. The package will be installed automatically

 _or_, you can download the package manually and copy the "gameconfig" folder into your GTAV/LML folder. 

## Manual Installation instructions

 1. Using OpenIV or Codewalker Explorer, open `[mods]\update\update.rpf\common\data\`  
    (We recommend using the "mods folder" feature in OpenIV)
 2. Make a backup of the original `gameconfig.xml`
 3. Copy in the modified `gameconfig.xml`
 4. Install any additional limit adjusters that may be required (see below)

## Other recommended files

 - [Heap Limit Adjuster](https://www.gta5-mods.com/tools/heapadjuster) - increases available memory for the game
 - [Packfile Limit Adjuster](https://www.gta5-mods.com/tools/packfile-limit-adjuster) - allows more DLC RPFs to be added
 - [WeaponInfo Limit Adjuster](https://www.gta5-mods.com/tools/cweaponinfoblob-limit-adjuster) - allows for more add-on weapons to be defined
 - [PedProp Limit Adjuster](https://www.gta5-mods.com/scripts/pedprop-limit-adjuster) - allows for more add-on ped props to be added
 - [Siren Setting Limit Adjuster](https://www.gta5-mods.com/scripts/sirensetting-limit-adjuster) - allows for more custom siren setting IDs to be used

## Credits

 - Game updates maintained by: PNWParksFan and Jax765
 - Original primary gameconfig adjustments: Dilapidated
 - Reverse engineering/research by: alexguirre, CamxxCore, and Dilapidated 
 - Additional assistance from: Unknown, PNWParksFan, Cass, Jax765, and the RDE Team

Permissions: You may redistribute these XMLs in your own mods permitted you give credit and leave all commented lines in the XML intact. 
If you make any new gameconfig discoveries or find better settings, please make a Pull Request.
