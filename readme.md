# Tiled extension for Cataclysm: Dark Days Ahead

Add the extension and extras folder to your [Tiled](https://www.mapeditor.org/) extensions folder.
[Check out the Tiled docs for more information](https://doc.mapeditor.org/en/stable/reference/scripting/#script-extensions)

The 'extras' folder contains png images for the extension tileset. This adds relative tiles like region groundcover.

=======
![tiledcddaextension](https://user-images.githubusercontent.com/30750303/202532520-69f460d4-2f5e-49c0-b3e7-46e10fc9637e.gif)

![tiled_screenshot](https://user-images.githubusercontent.com/30750303/199577624-fcc35ebf-7ec3-4617-9c5e-3c670f156607.png)

## Menu Actions

### File > Import CDDA Tileset

Import tilesets installed in CDDA folder by folder path.

- Takes a bit of time.

### File > Import CDDA Map

Import a CDDA map by its path, based on imported tileset. Must have imported tileset.

- Takes a bit of time.

### File > Export As... > CDDA map format

Export the current map as a json for CDDA.

- Furniture and Terrain (items, monsters, and other entities not quite)
- Map must be open in Tiled

### Tileset > Find CDDA Tile (ctrl+shift+f)

Jump to tile with CDDA id, such as "t_floor".

### Tileset > Add Sprite to Favorites (ctrl+shift+d)

Add sprite to 'Favorites' sprite sheet for easy access.

=======

What works

- nothing

What kind of works

- Import CDDA Tilesets
- Import CDDA map
  - Maps missing some definitions (results in empty tiles).
  - Some items and entities are imported when not using relative definitions.
- Export CDDA map
  - Can export a file that might load in CDDA.
  - Currently only exports terrain and furniture.
- Remember settings
  - Could be less annoying. But it isn't.
