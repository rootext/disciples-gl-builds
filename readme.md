# Disciples I & Disciples II OpenGL Wrapper

This wrapper redirects legacy DirectDraw graphics into OpenGL, allowing you to play these games on modern PCs with Windows 10 and 11. 
Added proper windowed mode and several upscale filters for a better gaming experience on modern screens, and much more.

![Disciples II](/docs/d2display.png)

## Download

### [DisciplesGL_2.0.0-dev.4](./../../raw/refs/heads/main/DisciplesGL_2.0.0-dev.4.7z)
* Add `Ctrl+Q` hotkey to add an auto-incremented index to quick save  
  Example: `QuickSave001.sg`
* Add `Archive saves` option  
  If enabled, all saved games, including auto saves and quick saves, are archived with the name
  `~name-date-time-turn.sg` in the Archive directory  
  Example:
```
  Archive
  |-20241101
    |~BossBattle!!!-20241101-122030-34.sg
    |~QuickSave-20241101-112030-11.sg
    |~AutoSave-20241101-102030-7.sg
```
* If `Shift` key is presed, the save is always archived  
  This feature works with auto and quick saves as well 

* Load quests (maps/saves) from all subfolders recursively  
  Example:
```
  Export
  |-In Gold We Trust.sg
  | Subfolder
    |-Drega Zul.sg
    | Subfolder
      |-Vaglan 1 - Highlands.sg
```
* Add simple zoom on `Ctrl+Wheel`
* Remove external dependecies (libpng and zlib)

### [DisciplesGL_1.90](./../../raw/refs/heads/main/DisciplesGL_1.90.7z)

* Latest stable build

> [!NOTE]
> This repository is a fork of https://github.com/Verokster/DisciplesGL  
> Verokster aka Verok is the original author of all code up to version 1.90

## Features & fixes
* Games render via OpenGL
* Games can now easily minimize on new OS
* Games can now easily switch into windowed/fullscreen mode
* Added several upscaling filters (ScaleNx, Super Eagle, Sal, ScaleHq and xBRz)
* Added game speed selection. Game can run faster now, up to 3x
* AI thinks much faster
* 32bpp rendering
* Added selection of any resolutions (4x3, 16x10, 16x9 ...) up to 4-8K
* Disciples II: 
    * Load quests from all subfolders recursively
    * Extended quick save
    * Added option to archive all saves
    * Added option to select widescreen battle window
    * Added new borders image for in game windows/dialogs. Thanks to Мотлин.

## Supported games and versions
* Disciples I: Sacred Lands
* Disciples II: Dark Prophecy
* Disciples II: Gallean's Return
* Disciples II: Guardians of the Light
* Disciples II: Servants of the Dark
* Disciples II: Rise of the Elves

## Installation
### Disciples I
* Make sure Disciple.exe doesn't use any compatibility modes (especially for GOG releases), or just rename it (e.g. Game.exe)
* Download installation file below
* Extract archive into game folder and replace existing files
* Launch Config.exe from the game "\EXE\" folder and make sure DirectDraw option is checked
* Launch Disciple.exe
* Have fun ;)

### Disciples II
* Make sure Discipl2.exe doesn't use any compatibility modes (especially for GOG releases), or just rename it (e.g. Game.exe)
* Download installation file below
* Extract archive into game folder and replace existing files
* Launch ConfigEditor.exe from the game folder and make sure Direct3D option is unchecked
* Launch Discipl2.exe
* Have fun ;)
