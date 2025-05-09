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
- Settings are now indicated as "work in progress": this is a temporary window which will be reworked soon.
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

## 202501a - 06.01.2025

### Additions

- Added player health and energy bars.

### Improvements

- The minimum Android version for launching the game is now Android 6.0 (API level 23).

### Corrections

- Fixed a problem where some enemies' names were not displayed completely above the central entity.

## 202502a - 12.01.2025

### Additions

- Added the name of the current underground under the region name.
- Added a slider to change the scale of UI elements.
- Added a button to reset game preferences in the settings.
- Added an information window, including the player's life and energy bars, to the left of the central entity.

### Improvements

- Major changes have been made to the UI so that visual elements adapt to all resolutions and screen definitions.
- Modification of the animation for region and underground changes.
- Removed a veil that appeared when the central entity was clicked.
- The score no longer increases when the entity clicked is an enemy.
- Changing region or underground now closes all UI windows.
- Moved some world map waypoints.
- Updated localization file.

## 202503a - 20.01.2025

### Additions

- Added an FPS counter at the top left of the dollar counter, which can be disabled in the settings.

### Improvements

- Modification of the statistics window to the left of the central entity.
- Support for "safe zones" on mobile devices: if the edges of the device are rounded or if a front camera is present, for example, no important UI elements will be hidden.

### Corrections

- Fixed a few performance problems that players could encounter.
- Fixed a problem where the game would launch with an interface size that was too large.

## 202504a - 27.01.2025

### Improvements

- Optimization of the UI window opening and closing system.

## 202505a - 04.02.2025

### Improvements

- Improved display of UI elements on screens with resolutions other than 16:9.

## 202506a - 09.02.2025

### Improvements

- Improved the UI scale slider.
- Removed the option to hide the FPS counter in the settings.
- Started redesigning the settings window.
- Moved the game version text.
- The display language at first game launch is now the device language.
- Improved display of UI elements on screens with resolutions other than 16:9.
- Updated localization file.

### Corrections

- Fixed a problem where the game would always launch with the UI at its maximum size.

## 202507a - 16.02.2025

### Improvements

- Redesign of part of the settings window.
- Modification of UI button animations.
- Modification of UI window masks.
- Optimized game launch.

### Corrections

- Fixed a problem where the game version text would overflow the settings window when the UI was zoomed out.

## 202508a - 24.02.2025

### Additions

- Added different durabilities for blocks and different numbers of HP for enemies.

### Improvements

- Improved UI scale slider.
- Modified the appearance of the FPS counter.

## 202509a - 03.03.2025

### Improvements

- Redesigned settings window.
- Significant changes have been made to the UI so that visual elements adapt to all resolutions and screen definitions.
- Improved UI window masks.
- Modification of the backgrounds of some of the game's regions.
- Updated localization file.

## 202511a - 17.03.2025

### Improvements

- Improved central entity animations.
- Improved button animations.
- The FPS counter is hidden by default and can now be displayed using the F key.
- The game will now close after deleting the save in the settings.
- Updated localization file.

## 202513a - 30.03.2025

### Improvements

- The UI scale change parameter is hidden on mobile.
- Redesign of some elements in the settings window.

### Corrections

- Fixed a problem where the click animation on the central entity would play once too often after the entity had been broken.
- Fixed a problem where the UI scale slider was not displayed correctly when the game started.

## 202514a - 06.04.2025

### Improvements

- Continued reworking of the settings window.
- Improved save system.
- The game is now automatically saved when the game is closed.
- The game is restarted automatically after the save is deleted.

### Corrections

- Fixed a problem where the last block or enemy encountered would not reappear when the next game was launched.

## 202515a - 14.04.2025

### Additions

- Added combat system basics.
- Added saving of warehouse blocks.

## 202516a - 20.04.2025

### Additions

- Added inventory item saving.

### Improvements

- It is now possible to swap two inventory or warehouse items.

## 202517a - 28.04.2025

### Additions

- Added quarry upgrade system.
- Warehouse blocks can now be sold by right-clicking on them.

### Improvements

- Added a one-second delay after deleting the save game and before starting a new game.
- Updated localization file.

## 202518a - 04.05.2025

### Improvements

- Improved opening and closing system for UI windows.
- The UI windows now always open in front of those already open.
- The dollar counter is now always displayed in front of UI windows.
- Improved FPS counter performance.
- Reduced delay after save deletion.

### Corrections

- Fixed a problem where the cost of a quarry upgrade was not displayed correctly in the quarry window.
