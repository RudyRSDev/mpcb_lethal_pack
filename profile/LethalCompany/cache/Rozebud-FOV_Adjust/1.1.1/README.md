# FOV Adjust
This is a simple mod that allows you to customize the game's field of view.

# How To Use
### Setup
Just put `FovAdjust.dll` in `BepInEx/plugins/`. After installing the mod and running the game, it will generate a config file in `BepInEx/config/`. You can adjust the FOV from there. You will need to restart the game for changes to take place.
### Chat Commands
There are two chat commands you can use; `/fov` and `/toggleVisor`.

`/fov #` will change your FOV to whatever you set as `#` (clamped between 66 and 130).

`/toggleVisor` will toggle the visibility of the first person visor.

_Note: Using chat commands will not change your config file, you still need to edit that to change the default values._

# Changelog

### v1.1.1
- Fixed a bug that made visor positioning weird if certain mods were used. _(It was because of my janky-ass coding, my bad.)_

### v1.1.0
- Added chat commands `/fov` and `/toggleVisor`.
- Adjusted visor scaling slightly.

### v1.0.0
- Inital release.