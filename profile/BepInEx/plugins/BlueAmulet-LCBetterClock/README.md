# BetterClock
Allows the clock to be customizable, all features may be changed via config file.  
<!-- Thunderstore I can't believe I have to rename my mod because I have another mod called BetterClock for Muck. -->
## Features
Clock visible inside ship or inside factory  
Smaller more compact clock  
Leading zeros for consistent clock size  
Raised clock to be less obstructive of vision  
Faster clock ui update rate  
24 hour time

## Installation (manual)
If you are installing this manually, do the following

1. Extract the archive into a folder. **Do not extract into the game folder.**
2. Move the contents of `plugins` folder into `<GameDirectory>\BepInEx\plugins`.
3. Run the game.

## Changelog
<details>
<summary>Click to expand</summary>

### 1.0.3
Added a keybind option to override the visibility of the clock.  
Can be set to toggle or hold mode.

### 1.0.2
Allow dark leading zero to be configured.  
Better compatibility with 24 hour time and mods that change the ship auto leave time like [LaterNights](https://thunderstore.io/c/lethal-company/p/ATK/LaterNights/).  
Added option to automatically fix time formatting issues from base game or other mods.  
Notably midnight being 12 PM (base game) or 0 AM (LaterNights)

### 1.0.1
Allow clock raising to be configured, requires compact to be enabled.  
Added compatibility between [Solo's Ring Compass](https://thunderstore.io/c/lethal-company/p/CapyCat/Solos_Ring_Compass/) and [LineCompass](https://thunderstore.io/c/lethal-company/p/juniper/LineCompass/), automatically lowering the clock as necessary.
</details>
