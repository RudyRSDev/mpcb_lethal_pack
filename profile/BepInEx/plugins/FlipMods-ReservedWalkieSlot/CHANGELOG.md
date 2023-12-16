# 1.0.0
+ Initial release
# 1.0.1
+ Fixed a bug in the item controls tooltip where some text was duplicating.
# 1.1.0
+ You can now change hotkey for talking in the walkie in the config.
+ Various tweaks to support the updated core mod.
# 1.2.0
+ Updated dependency to support the updated Core plugin.
# 1.2.1
+ The activate walkie keybind shouldn't "try" to run on non-owned players anymore.
+ Fixed bug causing players to get stuck on terminal.
# 1.2.2
+ Updated to support a few tweaks in the ReservedItemSlotCore mod.
+ Fixed some desync issues, and tweaked some other settings.
# 1.4.0
+ The walkie now straps nicely to your chest when not in your hand.
+ Involved in a code restructure/organization and updated to support ReservedItemSlotCore 1.4.0
+ Refer to the ReservedItemSlotCore 1.4.0 patch notes for more.
# 1.4.1
+ Fixed not properly handling PlayerActions in the OnDisable method if they were not yet initialized.
# 1.4.2
+ Updated load order to ensure the core mod loads first.
# 1.4.3
+ Finally tracked down and fixed the bug preventing players from using their hotkeys to swap hotbars, or activate their reserved items with [F] or [X]
# 1.4.4
+ Fixed some cases where the walkie mesh's active state was incorrect.<br>
I will re-add the mesh to the local player when I get a good position for it.
# 1.4.5
+ Should be able to activate the walkie again with LMB when currently held.
# 1.4.6
+ Updated dependency.