# Quiet Life Rules
>Version 1.0.0

1. No enchanted weapons, shields, or armor. Tools are fine, though. Axes count as weapons.
2. No helmets. This is a socially oriented game, and helmets make your head less visible. (This rule is optional if skins are not unique or do not relate to the player.)
3. Dark and light green lives cannot kill anyone (self defense is an exception). Yellow lives can kill dark green, and reds can kill anyone. Any illegal kills can be reversed with: ```/scoreboard players add <player> lives 1```

> **What constitutes an illegal kill:** If someone aggressively attacks you with intent to kill you and they are not allowed to kill you (as per rule 3), it is an illegal kill and should be reversed as shown in the example command above. If someone accidentally kills you (it is up to you what that means), it is not an illegal kill and cannot be reversed.

## Setup Guide

1. Put a command block down, set it to a repeating command block, set it to not require redstone, and input the command ```function quiet_life:tick```(the / is not required in command blocks). 
2. With the data pack activated, run the command ```/function quiet_life:init```.
3. To set a world border, use ```/worldborder set <SizeInBlocks>```. Recomended size is 500 blocks.
4. The colors of people's names that reflect their life count may not work right away. If you have already completed steps 1 and 2 and people's names are still white, run ```/function quiet_life:reload_colors```. This should not be neccessary, but it is a failsafe if something is not working properly.
5. Force load the chunk that the command block is in. Go right above it and type the command ```/forceload add ~ ~ ~ ~```.