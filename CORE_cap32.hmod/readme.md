-----------------------
Name: Cap32
Creator: Libretro
Category: Libretro RetroArch Cores
-----------------------
![Libretro Cores](https://modmyclassic.com/wp-content/uploads/2020/06/LibRetroNeoCoresSmall.png)

=== Cap32 Core for RetroArch ===

Module adds support for Cap32

Available executables and arguments to run Core:
- /bin/cap32 <rom> <clover_args>
- /bin/caprice32 <rom> <clover_args>
- /bin/cpc <rom> <clover_args>

These cores are automatically built against the latest LibRetro Source code. You can find nightly builds and stable builds [here](https://modmyclassic.com/hmodcores)

Core by Libretro

Libretro 'Neo' Classic platform maintained by [ModMyClassic](https://modmyclassic.com) [Discord](https://modmyclassic.com/discord)

-----------------------

# Software Information
display_name = "Amstrad - CPC (Caprice32)"
authors = "Ulrich Doewich|dantoine"
supported_extensions = "dsk|sna|zip|tap|cdt|voc|m3u"
corename = "Caprice32"
license = "GPLv2"
permissions = ""
display_version = "v4.2.0"
categories = "Emulator"

# Hardware Information
manufacturer = "Amstrad"
systemname = "CPC"
systemid = "cpc"

# Libretro Features
database = "Amstrad - CPC"
supports_no_game = "true"
savestate = "true"
savestate_features = "serialized"
cheats = "false"
input_descriptors = "true"
memory_descriptors = "false"
libretro_saves = "true"
core_options = "true"
core_options_version = "1.0"
load_subsystem = "false"
hw_render = "false"
needs_fullpath = "true"
disk_control = "true"
is_experimental = "false"
needs_kbd_mouse_focus = "true"
