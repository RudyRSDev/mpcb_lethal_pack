# Lethal Company Minimap

Introducing a **Minimap mod** for Lethal Company, a dynamic solution designed 
to enhance your gaming experience. This mod seamlessly integrates a persistent 
minimap on your screen, ensuring that you're never left in the dark, whether 
you're playing solo or in co-op mode.

For solo players, this mod emulates the real-time information flow that would 
typically be provided by a partner stationed at the ship's terminal.

In co-op mode, the Minimap mod ensures that everyone can join in the excitement 
of venturing into the building, eliminating the need for one player to stay 
back at the ship.


# Usage

These are the **default hotkeys**:
- `F1` - open the Minimap Mod menu
- `F2` - toggle the Minimap visibility
- `F3` - override the ship controls
- `F4` - switch the Minimap target (when ship controls are overridden)

**All hotkeys can be easily reconfigured via the Minimap mod menu.**

The Minimap size, position, and the hotkeys, can be customized via the mod menu.

By default, the Minimap is synced with the ship's control panel. However, you 
can override the ship controls. This way, you can ensure that the Minimap focus 
doesn't change even if your teammate switches to a different player in the ship.
It also allows you to switch the focused player on your Minimap without 
affecting the Minimap or ship map of other players.

This is a client-sided mod, meaning that other players don't need to have this 
mod installed.


# Features

- Minimap that can be toggled on and off
    - You can toggle the Minimap via a configurable hotkey
- Auto-rotate the Minimap based on where the player is looking at
    - You can turn this feature on and off via the mod menu
- Customize all aspect of the Minimap:
    - the Minimap size
    - the Minimap position
    - the Minimap zoom level
    - the Minimap brightness
- Switch Minimap focus without affecting other players map
    - or you can have the Minimap linked with the ship's control panel
- Customize all the available hotkeys via a user-friendly GUI:
    - Hotkey for opening the mod menu
    - Hotkey for toggling the Minimap
    - Hotkey for overriding ship controls
    - Hotkey for switching Minimap target
- Easily reset specific (or all) configurable settings
- All settings configurable via a user-friendly in-game GUI
- All configurable settings saved across sessions
- Toggle visibility of different Minimap icons
    - Loots, Enemies, Alived Players, Dead Players, Terminal Codes, and 
Radar Boosters
- Informs if the mod is outdated and a newer version is available

![Minimap GUI](https://raw.githubusercontent.com/tyzeron/LethalCompanyMinimap/main/Images/minimap-gui.png)


# Installation

1. Install **BepInEx** (see [BepInEx Installation Guide](https://docs.bepinex.dev/articles/user_guide/installation/index.html))

2. Launch **Lethal Company** _once_ with **BepInEx** installed to generate necessary mod folders and files

3. Navigate to your **Lethal Comanpy** game directory and go to `./BepInEx/plugins`
    - The `BepInEx` and `plugins` folder should have been generated in the previous step
    - **Example:** `C:\Program Files\Steam\steamapps\common\Lethal Company\BepInEx\plugins`

4. Download the Minimap mod, unzip it, and navigate to `./BepInEx/plugins`

5. Copy the **DLL file** (ex. `Minimap-v1.x.x.dll`) to the `plugins` folder

6. Launch the **Lethal Comanpy** game and enjoy your new Minimap mod :)
