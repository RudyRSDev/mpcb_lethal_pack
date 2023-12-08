# 1.0.0
+ Initial release
# 1.1.0
+ Reserved item slots now won't fade with the main hotbar.
# 1.2.1
+ Revamped functionality.
+ You can no longer swap to the reserved item hotbar slots, even if they're filled.
+ You can now swap to the reserved item hotbar slots by holding Alt, and scrolling up and down to switch between them.<br>
This way, you can swap to these items to drop them, as well as other actions, such as charging, storing, etc.<br>
The reserved item slots are still on the right side of the screen.
+ Added configs so you can change the swap hotbar modifier.
# 1.2.2
+ Fixed issue with non-host clients not correctly picking up the ReservedItemSlot items.
# 1.2.4
+ Hopefully fixed all of the issues with grabbing and dropping reserved items, and a few other issues.
+ There are a few minor issues I ran into that I will fix soon.
# 1.2.5
+ Swapping hotbar states should now be synced with all clients using this mod.<br>This means that the item held in each player's hand should be the same for everyone else.
# 1.2.6
+ Fixed syncing issue with clients that occurs when clients leave and rejoin.
# 1.2.7
+ Fixed a few desync issues and tweaked some of the network transport settings.
+ Optimized some areas of code.
# 1.2.8
+ Fixed issue where non-reserved items were going into the reserved item slots when the rest of the inventory is full.
+ Fixed a cursor tooltip issue showing that your inventory is full when looking at a ReservedItem, but you still have an available slot for it.
# 1.2.9
+ Fixed issue with being able to grab reserved items off of other players (caused de-sync)
# 1.4.0
+ Major code restructure/organization to optimize network syncing and stability.<br>
Along with the restructure, more bugs and issues may be introduced, but these will be addressed asap!<br>
+ Reverted some functions to rely on built-in code to reduce the likelyhood of desyncs caused by these mods.<br>
This will help with future syncing with clients not uses these mods, but will likely not play nice with them at this point.
+ Other various fixes.
# 1.4.1
+ Fixed not properly handling PlayerActions in the OnDisable method if they were not yet initialized.
# 1.4.2
+ Finally tracked down and fixed the bug preventing players from using their hotkeys to swap hotbars, or activate their reserved items with [F] or [X]
# 1.4.3
+ Fixed (again?) being able to switch to your reserved hotbar while holding a two-handed item.
+ Improved logic for swapping between hotbars, or preventing you, while in certain animations or events.
+ Removed old debug logs.