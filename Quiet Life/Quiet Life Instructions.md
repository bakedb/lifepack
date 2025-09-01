# Quiet Life Rules
>Version 1.0.0

1. No enchanted weapons, shields, or armor. Tools are fine, though. Axes count as weapons.
2. No helmets. This is a socially oriented game, and helmets make your head less visible.
3. Dark and light green lives cannot kill anyone (self defense is an exception). Yellow lives can kill dark green, and reds can kill anyone. Any illegal kills can be reversed with: ```/scoreboard players add <player> lives 1```

## Setup Guide

1. With the data pack activated, run the command ```/function quiet_life:init```.
2. Put a command block down, set it to a repeating command block, set it to not require redstone, and input the command ```function quiet_life:tick```(the / is not required in command blocks). 
3. To set a world border, use ```/worldborder set <SizeInBlocks>```.
4. The colors of people's names that reflect their life count may not work right away. If you have already completed steps 1 and 2 and people's names are still white, run ```/function quiet_life:reload_colors```.
5. Force load the chunk that the command block is in. Go right above it and type the command ```/forceload ~ ~```.