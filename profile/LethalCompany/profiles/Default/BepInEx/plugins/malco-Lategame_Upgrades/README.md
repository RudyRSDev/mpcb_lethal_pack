# LateGameUpgrades
***INSTALL THE DEPENDENCIES***  
***ALL CLIENTS NEED THIS MOD INSTALLED***  

*Everything about this mod can be changed via the config*

to install just put the MoreShipUpgrades folder in your BepInEx plugins folder.

Type `lategame` in the terminal to see mod info.  
Type `lategame store` to view current upgrade status and cost.  
Type `info <upgrade>` for dynamic info.

This adds 12 powerful ship upgrades to make lategame last longer and remedy having a bunch of money and nothing to spend it on.


```
V 2.0.0

[New]
- Custom Store
    ~ Type `lategame store` to access the custom store.
    ~ Prevents buying upgrades twice and tracks current upgrades.
    ~ Physical items (like portable tele) are still purchased through `store`.
- More Config Settings
    ~ Mainly the ability to change how much tiered upgrades change per level.
- Many many many fixes
    ~ Better safer netcode
- Custom Saving and Loading and Syncing system
    ~ This was nescessary for tiered upgrades.
    ~ Should increase compatibility and loading consistency.
    ~ LGU save files are in LocalLow/ZeekersRBLX/Lethal Company

[ Upcoming ]
The mod feels pretty stable at the moment so I may get back to adding additional content for a bit.

[ Known Bug ]
If a remote client purchases a tierable upgrade sometimes it will say the wrong level was upgraded
due to latency. EX: Upgrade to lvl 2, it says 'Upgraded to level 1'. This is purely visual and I'll
hotfix it soon.
```

Please post bugs or ideas [on this post](https://discord.com/channels/1168655651455639582/1178407269994594435) after joining [this modding discord.](https://discord.gg/hzEcKFSSDX)

Feel free to [create a pull request](https://github.com/Malcolm-Q/LC-LateGameUpgrades) and help with the mod.

## Credit
- GitHub Contributors
    - Dilly_The_Dillster
- Graphics / Art
    - Sad Amazon
- Beta Testers
    - Lann
    - Kapt
    - Rootbeer
    - Glitched

## Upgrades
* __Portable Teleporter - $300__
    * An item that when used teleports you back to the ship.
    * Keeps items.
    * 90% chance to get destroyed on use.

* __Advanced Portable Teleporter - $1750__
    * Same as above.
    * 20% chance to get destroyed on use.

* __Beekeeper - $450__
    * Circuit bees do significantly less damage to you.

* __Bigger Lungs - $700__
    * Increased sprint duration.

* __Running Shoes - $1000__
    * Increased movement speed.

* __Strong Legs - $300__
    * Jump higher.

* __Malware Broadcaster - $650__
    * Instead of disabling turrets and landmines; Destroy them.

* __Light Footed - $350__
    * Enemies have to be closer to hear your footsteps.
    * Applies to both walking and running.

* __Night Vision - $700__
    * Press Left Alt to toggle night vision.
    * Has self regenerating batery.

* __Discombobulator - $550__
    * Enter `initattack` into the terminal to stun enemies around the ship.
    * Enter `cooldown` to view cooldown (120 seconds).
    * Attracts enemies in a larger radius than loud horn.

* __Better Scanner - $650__
    * Increase distance of Ship and Entrance pings drastically.
    * Increase distance of all other pings.
    * Line of sight is no longer needed for pings.

* __Back Muscles - $835__
    * No longer experience effects from carryweight.


*Compatibility*

This changes and patches quite a bit of stuff so problems may arise.  
A user has reported minimap mod and bodycam mod to not be compatible.  
A user has reported latecompany to not be compatible.  
A user said issues may arrive with saving upgrades if using LCBetterSaves  

Compatibility issues will be investigated and hopefully resolved when higher priority tasks are out of the way.
