# Disciples I & Disciples II OpenGL Wrapper (+ Patch)

> [!NOTE]
> This repository is a fork of the project found at https://github.com/Verokster/DisciplesGL  
> Verokster aka Verok is the original author of all code up to version 1.90

This patch/wrapper redirect legacy DirectDraw graphics into OpenGL and allows play games on modern PC with Windows 10 and 11. 
Added proper windowed mode and several upscale filters for better gaming on modern screens.

## Features & fixes
* Games render via OpenGL
* Games can now easily minimize on new OS
* Games can now easily switch into windowed/fullscreen mode
* Added several upscaling filters (ScaleNx, Super Eagle, Sal, ScaleHq and xBRz)
* Added game speed selection. Game can run faster now, up to 3x
* AI thinks much faster
* 32bpp rendering
* Added selection of any resolutions (4x3, 16x10, 16x9 ...) up to 4-8K
* Disciples II: Added option to select widescreen battle window
* Disciples II: Added new borders image for ingame windows/dialogs. Thanks to Мотлин.

## Supported games and versions
* Disciples I: Sacred Lands
* Disciples II: Dark Prophecy
* Disciples II: Gallean's Return
* Disciples II: Guardians of the Light
* Disciples II: Servants of the Dark
* Disciples II: Rise of the Elves

## Installation
### Disciples I
* Make sure Disciple.exe doesn't use any compability modes (especially for GOG releases), or just rename it (e.g. Game.exe)
* Download installation file below
* Launch this file and select a game root folder, where the game was previously installed
* Launch Config.exe from the game "\EXE\" folder and make sure DirectDraw option is checked
* Launch Disciple.exe
* Have fun ;)

### Disciples II
* Make sure Discipl2.exe doesn't use any compability modes (especially for GOG releases), or just rename it (e.g. Game.exe)
* Download installation file below
* Launch this file and select game root folder, where the game was previously installed
* Launch ConfigEditor.exe from the game folder and make sure Direct3D option is unchecked
* Launch Discipl2.exe
* Have fun ;)
