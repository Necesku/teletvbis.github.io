# Changing world type

By default, your FPS.ms will have NORMAL world type, but you may prefer SUPERFLAT for building.

### How to do that?

First, you need to enter the panel and select your server. Then, you need to go to "Files" tab and click "server.properties".
Scroll down until you see "level-type" option. Replace the default type with any world type you would like (Scroll down to see the list of world types).
Click save and you're done!

### World Types

- minecraft:normal - Standard world with hills, valleys, water, etc.
- minecraft:flat - A flat world with no features, can be modified with generator-settings.
- minecraft:large_biomes - Same as default but all biomes are larger.
- minecraft:amplified - Same as default but world-generation height limit is increased.
- minecraft:single_biome_surface - A buffet world which the entire overworld consists of one biome, can be modified with generator-settings.
- buffet - **Only for 1.15 or before**. Same as default unless generator-settings is set.
- default_1_1 - **Only for 1.15 or before**. Same as default, but counted as a different world type.
- customized - **Only for 1.15 or before**. After 1.13, this value is no different than default, but in 1.12 and before, it could be used to create a completely custom world.
*source: https://minecraft.fandom.com/wiki/Server.properties*
