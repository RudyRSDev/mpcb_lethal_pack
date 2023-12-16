# 1.1.0
+ Initial release
# 1.1.1
+ Fixed BepInEx dependency
# 1.1.2
+ Emotes weren't rebinding correctly. Should be good now.
# 1.2.0
+ First attempt at chain dropping items. Will tweak animation a bit to look smoother soon.
# 1.2.1
+ Minor fixes
# 1.2.2
+ Synced hotbar swap slots with all clients. This will work with any hotbar size.
# 1.2.3
+ The sync was previously only syncing to the host. It should sync between everyone properly now.
# 1.2.4
+ Fix some sync issues.
+ Fixed a bug that caused pressing escape to tab in the terminal to open the menu.
# 1.2.5
+ All clients will now sync the number of hotbar slots with the host.<br>
If the host has the number of hotbar slots set to 4 in their config, then other clients with the mod will also have 4 hotbar slots, regardless of their config settings.
# 1.2.6
+ Old configs shouldn't persist anymore.
+ Selecting a lower amount of hotbar slots than the default 4, in the config, should now work without issues.
+ You shouldn't be able to use the numerical hotkeys to swap hotbar slots while carrying a two-handed object.
# 1.2.7
+ Disabling item quick drop until I fix the desync issues.
# 1.2.8
+ Fixed an issue where the mod would complain about reloading the config before it was created.
# 1.2.9
+ Fixed the issue preventing players from using their hotkeys to swap hotbar slots, or emoting with the rebound keys.
# 1.3.0
+ Forgot to update the dll.
# 1.3.1
+ Updated to support new game update
# 1.3.2
+ Fixed bug with "fixed" emote rebinds not working.