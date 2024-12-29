# Snapshots Changelog

## 202444a - 03.11.2024

First snapshot of **Striving Fighter**!

## 202445a - 11.11.2024

### Additions

- Added textures for the first four blocks of the game: Dirt, Grass, Sand, Stone.
- Added settings window.
- Added quarry upgrade system.
- Added saving system for game and user preferences.
- The game can now be closed by pressing Escape.

### Improvements

- Redesigned many UI elements.

## 202446a - 17.11.2024

### Additions

- Added current region name at the top of the screen.
- Added Undergrounds and World Map windows.
- Added textures for inventory, workshop, settings, undergrounds and world map buttons.
- Added first in-game background.
- Added background to UI windows.
- Added game quit button in settings.

### Improvements

- The quarry upgrade button is now grayed out when no upgrade is possible.
- Settings are now opened by pressing Escape.
- Updated localization file.

### Corrections

- AZERTY keyboards are now supported.
- Fixed a problem where the dollar counter was displayed too far to the left on screens with resolutions other than 16:9.
- Fixed a problem where buttons could be clicked with the Space key.

## 202447a - 24.11.2024

### Additions

- Added animations to the central block.
- Added display and hide animations to UI windows.

### Improvements

- Modification of UI window background.
- Redesigned save buttons in settings.
- Redesigned UI window display and hiding system.
- Updated localization file.

## 202448a - 01.12.2024

### Additions

- Added textures for warehouse and quarry buttons.
- Added inventory system.

### Improvements

- Modification of the UI window display and hiding system.
- Modification of certain inventory UI elements.

## 202449a - 08.12.2024

### Improvements

- Overhaul of the block and inventory system.
- Overhaul of some sprites and textures.
- The default number of inventory slots is 10.
- Modification of the 10 backgrounds of the game's 10 regions.
- Updated localization file.
- Many important elements have been modified in the game code.
- Removed the Unity logo at game startup.

### Corrections

- Fixed a problem where clicking on a broken block would momentarily spawn a new block before reloading a second one.

## 202450a - 15.12.2024

### Additions

- Added world map.
- It is now possible to change the region by clicking on one of the waypoints on the world map.

### Improvements

- The Escape key is now used to close other UI windows before displaying settings.

### Corrections

- Fixed a problem where some UI windows could not be closed properly.

## 202451a - 24.12.2024

### Additions

- Added items for the Enchanted Glade, each with a different rate of spawn for each underground.
- Added enemies in the Enchanted Glade, with a 10% chance to spawn instead of the central block, and a different spawn rate for each underground.
- Addition of 20 slots in the warehouse.
- Added game icon.

### Improvements

- Removed warehouse and quarry windows.
- Settings are now indicated as “work in progress”: this is a temporary window which will be reworked soon.
- Map waypoints are now locked when a region has not yet been unlocked by the player.
- Removed the fade to black in the game background when the player tries to access the region he is already in.
- Removed the fade to black at game startup.
- When the game starts, the enemy or block loaded first is no longer the last one that previously spawned before the game was saved, but a completely new enemy or block.
- Moved the item counter to an inventory or warehouse slot and added a shadow behind it.
- Modification of the game's loading screen.
- Added a shadow behind the central block or enemy.
- Removal of the black veil when moving the mouse over the central block or enemy.
- Many important elements have been modified in the game code.
- Updated localization file.

## 202452a - 29.12.2024

### Corrections

- Fixed a problem where the game icon was not displayed correctly on Android.
