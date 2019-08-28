This is a modification of SuperTiled2Unity, hardcoding a few things for my own convenience so that I don't have to go and reconfigure them manually in my project.  Maybe they'll be useful to you, too.

Modifications:
* Tile layers, by default, are assigned to the "Tiles (background)" sorting order.  (You need to have a sorting order with this name in your game already.)
* Exception for tile layers with "foreground" or "fg" in their name.  Those get assigned "Tiles (foreground)" instead.  (You'll need to have a sorting order with the 'Tiles (foreground)' name as well.)
* All imported collison layers are set to synchronous polygon mode.
* If a tile layer has the phrase "no collision" or "nocollision" as part of its name, it won't have collisions generated for it.
