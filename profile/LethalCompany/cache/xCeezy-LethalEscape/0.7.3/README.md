
# Lethal Escape 0.5

The monsters escape outside the facility so now that nowhere is safe!.

# Mod semi requires all clients to have all the mod
if not all clients have the mod the AI can break when targeting them or in the case of the braken it can cause your game to go to 10 fps
The reason for this is because as far as I am aware its not possible to replicate the enemytype.isoutsideenemy variable so if a player without the mod has the ownership 
switch to them while the enemy is outside it will try to use the AI nodes that are in the facillity when its outside and because the game calculates AI on the client some of the time it can cause major lag when it tries to re calculate a path on tick 