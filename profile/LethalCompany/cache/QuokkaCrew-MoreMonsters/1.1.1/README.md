# MoreMonsters
Adds mob quantity scaling for the MoreCompany mod (found here: https://thunderstore.io/c/lethal-company/p/notnotnotswipez/MoreCompany/).

Players access a menu via the Insert key that allows them to customize how many monsters spawn inside the building and how often they spawn.
(Previously it was set to spawn 0.75 * number of players for anyone wishing to recreate the mob spawning quantity from the previous version.)

Mobs will spawn shortly after players drop.

# How to Use
Once in-game, the host opens the menu by pressing the Insert Key
The Number of Mobs slider changes the maximum number of monsters allowed inside the building from either 0 to 100 (This can lag quite badly after > 30 monsters, especially if you are far away from the building.
Although this may only affect the host's performance).
The Time Between Mob Spawns slider adjusts the amount of time between each new individual monster spawn, From 0 to a max of 8 hours. 0 results in instantaneous spawning of the selected number of monsters.
When "Spawn an extra mob after..." is toggled, it will spawn a new monster after finding 25%, 50%, and 75% of the total scrap contained in the level, for a total of 3 additional monsters. Is is toggled off by default.

# Future Updates
Planning on adding the ability to customize allowed quantity of each monster, 
alongside enabling modifying the number of outside and daytime monsters as well.
Add more customization with regards to having more mobs spawn at various checkpoints, like with collecting
a certain amount of scrap or even reaching a various part of the dungeon.

# Installation
1. Install BepInEx.
2. Run game once with BepInEx installed to generate folders/files.
3. Drop the DLL inside of the BepInEx/plugins folder.
4. No further steps needed.

# Credits
Menu was possible thanks to @lawrencea13's code, creator of the Lethal Company Game Master Mod.
