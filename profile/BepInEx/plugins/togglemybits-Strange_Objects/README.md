# Strange Objects v1.2.1
### Adds a new rarity tier of scrap items. These items are more valuable but also dangerous!

## Instructions
Place the ```StrangeObjects.dll``` file in your ```BepInEx/plugins``` folder.

Everyone in your multiplayer game needs a copy of the mod installed for it to work properly

A config has been added! Want strange objects to spawn more or less? Now you can change it!

See the Config section below for more information.

## Description
- Strange objects are worth over 30% more scrap than normal scrap items
- Strange objects can be identified by their red enemy-like color in scans
- There are 4 possible curses that could be in a strange object:
    - Curse of Pain: Damages the player
    - Curse of Sight: Makes the player a lil tipsy
    - Curse of Sloth: Reduces the player's movement speed
    - Curse of Midas: Lucky you! These objects change name and scrap value every time they're picked up
- Curses are removed when the strange object is dropped, at the end of a round, or death
- Curses can stack if you pick up more than one strange object so be careful!
- Multiple players can get the same curse from picking up the same item

## Config
When you launch the game with the mod installed a ```Bits.StrangeObjects.cfg``` file should generate in your ```BepInEx/config``` folder.

There are two general settings you can change in the config:
- SpawnRate - Controls how often strange objects spawn on average. Default: 20%
- ValueMultiplier - Controls how high the scrap values of strange objects are. Default: 0.3 or 30% higher scrap

You can also set curse specific settings such as the ones for Sloth:
- EnableCurseofSloth - Disables curse if false
- Level1MovementDebuff - Percentage of Movement Speed after Level 1 Debuff. Default is 0.75 or 75% less speed
- Level2MovementDebuff - Percentage of Movement Speed after Level 2 Debuff. Default is 0.5 or 50% less speed

## Changelog
    - v1.2.1
        - Fixed bug causing lobbies to not start properly when this mod was used with the MoreCompany mod
    - v1.2.0
        - Curses have been reworked to turn on and off when strange objects are picked up or dropped. Level 2 of Curse of Pain has been removed.
    - v1.1.6
        - Added config settings for each curse. Curses can now be disabled individually. Added Curse of Voice back but it's buggy so disabled by default
    - v1.1.5
        - Added a config file that generates on game launch
    - v1.1.4
        - Refactored some of the code
    - v1.1.3
        - Strange objects now start off with the "Strange" title and change into curse specific titles on pickup
        - Added scaling to Sloth Curse and lowered initial movement speed debuff
        - Max value a Midas Curse object can roll is now 100
    - v1.1.2
        - Made the scrap value of Curse of Midas objects a lil more random
        - Added more possible adjectives for strange objects
        - Curse of Midas objects should now stay as that curse for other players
    - v1.1.1
        - Improved handling of curse removal on death
    - v1.1.0
        - Lowered strange object spawn rate down to 10% or 1/10 items on average
        - Increased the damage done to a player by "Curse of Pain"
        - Removed "Curse of Sound" until a later rework
        - Added "Curse of Sloth"
        - Added "Curse of Midas"
        - Fixed bug where strange objects would sometimes not have an additional adjective in their name
    - v1.0.0
        - Release

## Known Issues
- Items revert back to regular scrap when a save file is loaded
- Strange objects sometimes don't trigger properly on pickup

## Special Thanks
- My boyfriend for helping me test the mod <3
- MrMiinxx for this [YouTube Tutorial](https://youtu.be/4Q7Zp5K2ywI?si=8dpUhJFCa6BvxkM5) that got me started
- [LC Modding Discord](https://discord.gg/ECvSzsPT7V)
