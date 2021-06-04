# TILED-Python-to-C
Simple Python tool to turn content of a Tiled export into C.
This may be useful in the context of developing a SEGA Genesis/Megadrive game in C with SGDK, while handling level design with Tiled.
In our case, Tiled file contains 8x8 tiles which have a "Walkable" attribute to indicated where the player is allowed to go on the map.
Generated C code is adapted to a specific program not disclosed here.
You may consider another structure for your own C code, especially if you want to save ROM space.
