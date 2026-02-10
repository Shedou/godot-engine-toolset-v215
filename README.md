## Godot Engine 2.1.5 Toolset [![Github Releases](https://img.shields.io/github/downloads/Shedou/godot-engine-toolset-v215/total.svg)](https://github.com/Shedou/godot-engine-toolset-v215/releases)
Packaged by: Chimbal (https://github.com/Shedou, https://overclockers.ru/blog/Hard-Workshop)

Language: (EN / [RU](https://github.com/Shedou/godot-engine-toolset-v215/blob/main/README-RU.md))

Скачать: [Godot Engine ToolSet v2.1.5](https://github.com/Shedou/godot-engine-toolset-v215/releases/tag/first)

A standalone development kit for projects based on Godot Engine v2.1.5.

## Set contents:
- Godot Engine - Official version + unofficial version + source code.
- Export Templates - Official export templates + unofficial ones for Windows XP support.
- Rcedit v1.1.1 (Windows XP+) / v2.0.0 - Utility for changing icon during export (Windows).
- Mesa - Allows you to use the CPU instead of the graphics card to run the OpenGL API. Helps run in a virtual machine without 3D acceleration.
- Start-Editor-* - Scripts for launching the editor in portable mode. The home directory is moved to the UserData folder.

## Export templates:
- Export templates are located in the Templates directory.
- Official templates (Templates-Official) are not compatible with Windows XP!
- For compatibility with Windows XP, you should use templates from the Templates-XP folder.

1) If you plan to move your home directory to the UserData folder by launching the editor through the Start-Editor-* scripts, you need to copy the export template files to the following directories:
> Windows - UserData\Windows\AppData\Roaming\Godot\templates\
> Linux - UserData/Linux/.godot/templates/

2) If you launch the Godot Engine editor directly from the Editor directory, the export templates should be copied to the following directories:
> Windows - C:\Users\ИМЯ_ПОЛЬЗОВАТЕЛЯ\AppData\Roaming\Godot\templates\
> Linux - /home/ИМЯ_ПОЛЬЗОВАТЕЛЯ/.godot/templates/

## Mesa:
- This library allows you to run Godot Engine and other programs using the central processor instead of the video card.
- Works only with OpenGL API in Windows environment.
- To use, copy opengl32.dll to the program directory (where "*.exe").
- IMPORTANT! The 32-bit version of the program (game) will only work with 32-bit Mesa! Running a 64-bit program on 32-bit Mesa will result in an error!

## Kit compatibility:
- Godot Engine (Editor): Windows 7+ | Linux (glibc 2.17+), Debian 8+
- Export Templates (Official): Windows 7+ | Linux (glibc 2.15+), Debian 8+
- Export templates (unofficial): Windows XP+

## Notes:
- The unofficial editor may not work correctly in the Windows XP environment.


## Projects included in the set:

- Godot-2.1.5 Official:
> https://github.com/godotengine/godot
> 
> https://github.com/godotengine/godot/releases/tag/2.1.5-stable

- Godot-2.1.5-Windows-XP:
> https://github.com/DNS/Godot-2.1.5-Windows-XP

- Rcedit:
> https://github.com/electron/rcedit

- Mesa:
> http://mesa.fdossena.com
> 
> https://downloads.fdossena.com/Projects/Mesa3D
