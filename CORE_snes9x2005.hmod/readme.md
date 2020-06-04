-----------------------
Name: Snes9x2005
Creator: Libretro
Category: Libretro RetroArch Cores
-----------------------
![Libretro Cores](https://modmyclassic.com/wp-content/uploads/2020/06/LibRetroNeoCoresSmall.png)

=== Snes9x2005 Core for RetroArch ===

Module adds support for Snes9x2005

Available executables and arguments to run Core:
- /bin/snes <rom> <clover_args>
- /bin/snes05 <rom> <clover_args>

These cores are automatically built against the latest LibRetro Source code. You can find nightly builds and stable builds [here](https://modmyclassic.com/hmodcores)

Core by Libretro

Libretro 'Neo' Classic platform maintained by [ModMyClassic](https://modmyclassic.com) [Discord](https://modmyclassic.com/discord)

-----------------------

# Software Information
display_name = "Nintendo - SNES / SFC (Snes9x 2005)"
categories = "Emulator"
authors = "Snes9x Team|dking|BassAceGold|ShadauxCat|Nebuleon"
corename = "Snes9x 2005"
supported_extensions = "smc|fig|sfc|gd3|gd7|dx2|bsx|swc"
license = "Non-commercial"
permissions = ""
display_version = "v1.36"

# Hardware Information
manufacturer = "Nintendo"
systemname = "Super Nintendo Entertainment System"
systemid = "super_nes"

# Libretro Features
savestate = "true"
savestate_features = "deterministic"
cheats = "true"
input_descriptors = "true"
memory_descriptors = "true"
libretro_saves = "true"
core_options = "true"
core_options_version = "1.0"
load_subsystem = "false"
supports_no_game = "false"
database = "Nintendo - Super Nintendo Entertainment System|Nintendo - Super Nintendo Entertainment System Hacks|Nintendo - Sufami Turbo|Nintendo - Satellaview"
hw_render = "false"
needs_fullpath = "false"
disk_control = "false"

description = "Snes9x 2005 is a fork of the classic and popular SNES emulator Snes9x from circa 2005. This core is significantly faster than the newer cores, but that speed comes at the price of accuracy, and this core has some bugs in mostly obscure games and lower audio quality. This core is ideal for very weak devices, such as New 3DS and single-board computers. Users who cannot maintain full speed with this core--much less any of the newer Snes9x cores--should fall back to Snes9x 2002 as a last resort."
