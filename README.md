# Image2Map "E"

A Fabric and Quilt mod that allows you to render an image onto a map(s), allowing you to display it on your vanilla compatible server even in survival mode!

![Some images](https://raw.githubusercontent.com/TheEssem/Image2Map/master/images.png)
![More images](https://imgur.com/qy8JF5B.png)

## Commands:
- `/image2map create <WIDTH> <HEIGHT> <[dither/none]> <URL>` - Creates map of specified size (in pixels, single map is 128x128), with/without dither, using provided image
- `/image2map create <[dither/none]> <URL>` - Creates map with/without dither, using provided image
- `/image2map preview <URL>` - Creates dynamic preview before saving the map as item. It's recommended to do so before creating any images.

### Commands in preview mode
- `/dither <[dither/none]>` - Changes dither mode. You can choose either the [Floyd–Steinberg dithering](https://en.wikipedia.org/wiki/Floyd%E2%80%93Steinberg_dithering) or none.
- `/size` - Displays current size
- `/size <WIDTH> <HEIGHT>` - Changes size of map to specified one (in pixels, single map is 128x128)
- `/normalize <WIDTH>` - Resize the image, while maintaining the original aspect ratio, by the specified width in Minecraft blocks ranging from 1 to 8.
- `/grid` - Toggles visibility of map grid
- `/save` - Exits preview and saves map as items
- `/exit` - Exits preview without saving

## Changes from original version
For more suitable usage in survival mode, some features are added and removed from the mod.
- Multimaps in bundle are disabled. Created images of any size will give all individual maps into the inventory instead. Existing map bundles will work like usual.
- Newly created multimaps will not get deleted when remove from item frames. However, item frames are also not automatically made invisible when placing a generated map on them; for now, you will need another way to do so/
- Unless in Creative Mode, player will need to have enough empty maps in their inventory to create images.
- Added `/normalize' command to allow easier image resizing in Minecraft blocks without changing the aspect ratio.

## Credits
- Patbox - Current original mod maintainer. Original repository can be found [here](https://github.com/Patbox/Image2Map).
- Ahydul - Most of the changes found in this fork.

Will you port this to Forge/Bukkit/Paper?  
   ![no lol](https://i.imgur.com/tf5W69k.png)
