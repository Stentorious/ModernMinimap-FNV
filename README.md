# Modern Minimap
<p align="left">
    <img height="350px" src="https://i.imgur.com/J7PASnx.png">
</p>

## Overview
- Adds a modern and feature rich minimap to the HUD.
- Dynamic icons indicating the position/status of NPCs, items, and interactables.
- Dozens of configuration options to customize the map to your liking.

### Lite Version
- Slim & Efficient
- NPC, Creature, and Door Icons
- Quest Markers

### Full Version
- Full Icon Suite
- [ySI - Sorting Icon](https://www.nexusmods.com/newvegas/mods/74358) Integration
- [KEYWORDs](https://www.nexusmods.com/newvegas/mods/83088) Support
- Fully Configurable
- Includes all of the features described below

## Configuration
- Configurable via the included ModernMinimap.ini

### Key Binds
- Toggle visibility - Default: M
- Switch rotation mode - Default: End
- Zoom In - Default: PgUp
- Zoom Out - Default: PgDown

### Map
- Set size
- Set screen position/offset
- Set default interior/exterior zoom
- Toggle compass rose
- Toggle scan effect
- Toggle combat indicator
- Set location name mode
- Set rotation mode:
  - Fixed north
  - Rotate with player

### Icons
- Set size
- Toggle drop shadow
- Toggle height indicator
- Toggle perception based visibility distance
- Toggle alpha distance fade
- Toggle which icons to display

### Actor Icons
- Show NPCs, creatures or both
- Shade icon color based on actor hostility
- Add dynamic icons to vendors
- Hide empty corpses

### Object Icons
- Crafting Stations - Workbenches, Reloading Benches, and Cooking Stations
- Locked Containers - Shows lock level and if you have the appropriate key
- Terminals - Shows lock level and if you have the appropriate key
- Mines - Shows NPC placed armed mines

### Item Icons
- Skill Books
- Skill Magazines
- Notes
- Keys
- Unique Items
- Quest Items

### Collectables
- Snow Globes - Fallout NV
- Caravan Cards - Fallout NV
- Sunset Sarsaparilla Star Bottle Caps - Fallout NV
- Dean's Stashes - Dead Money
- Survivalist Caches - Honest Hearts
- Warheads - Lonesome Road
- Ralphie Posters - Lonesome Road
- Bobbleheads - Fallout 3
- Steel Ingots - The Pitt
- Intel Briefcases - Anchorage

## Adding Map Icons
Requires the *Full* version of Modern Minimap.

Adding minimap icons to any Item, Activator, Container, or Projectile is as simple as adding the ***MinimapIcon*** Keyword to the appropriate form. See the [KEYWORDs](https://www.nexusmods.com/newvegas/mods/83088) mod page for detailed instructions on the different ways you can manage Keywords.

Icons will be automatically assigned based on the ySI - Sorting Icons framework.
Every inventory item will already have assigned ySI - Sorting Icons textures, but Activators, Containers, and Projectiles will not.

You can assign icons to any game form using the same .JSON framework that ySI - Sorting Icons uses for items. Check the Modern Minimap installation directory for an example ModernMinimapTags.json, where I have assigned icons to the forms supported by default.

Here is an [in depth guide](https://www.nexusmods.com/newvegas/mods/76521) on the ySI .JSON framework, the information provided can be applied to any form type, not just items.

## Recommended
- [Local Map Overhaul](https://www.nexusmods.com/newvegas/mods/88533)
- [Colorful Inventory Ycons](https://www.nexusmods.com/newvegas/mods/78674)
- [ySI - Colorful Icons Support](https://www.nexusmods.com/newvegas/mods/85075)

## Requirements
- [xNVSE](https://www.nexusmods.com/newvegas/mods/67883) (6.3.3+)
- [JIP LN NVSE](https://www.nexusmods.com/newvegas/mods/58277)
- [JohnnyGuitar NVSE](https://www.nexusmods.com/newvegas/mods/66927)
- [ShowOff xNVSE](https://www.nexusmods.com/newvegas/mods/72541)
- [High Res Local Maps](https://www.nexusmods.com/newvegas/mods/77963)
- [User Interface Organizer](https://www.nexusmods.com/newvegas/mods/57174)
- [yUI - User Ynterface](https://www.nexusmods.com/newvegas/mods/74357) (Full Version Only)
- [ySI - Sorting Ycons](https://www.nexusmods.com/newvegas/mods/74358) (Full Version Only)

## Installation
Installs with a mod manager via the FOMOD installer.