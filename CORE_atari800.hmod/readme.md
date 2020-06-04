-----------------------
Name: Atari800
Creator: Libretro
Category: Libretro RetroArch Cores
-----------------------
![Libretro Cores](https://modmyclassic.com/wp-content/uploads/2020/06/LibRetroNeoCoresSmall.png)

=== Atari800 Core for RetroArch ===

Module adds support for Atari800

Available executables and arguments to run Core:
- /bin/a52 <rom> <clover_args>
- /bin/atari800 <rom> <clover_args>

These cores are automatically built against the latest LibRetro Source code. You can find nightly builds and stable builds [here](https://modmyclassic.com/hmodcores)

Core by Libretro

Libretro 'Neo' Classic platform maintained by [ModMyClassic](https://modmyclassic.com) [Discord](https://modmyclassic.com/discord)

-----------------------

# Software Information
display_name = "Atari - 5200 (Atari800)"
authors = "Petr Stehlik"
supported_extensions = "xfd|atr|atx|cdm|cas|bin|a52|xex|zip"
corename = "Atari800"
categories = "Emulator"
license = "GPLv2"
permissions = ""

# Hardware Information
manufacturer = "Atari"
systemname = "Atari 5200"
systemid = "atari_5200"
database = "Atari - 5200"
display_version = "3.1.0"

# Libretro Features
supports_no_game = "false"
savestate = "false"
savestate_features = "null"
cheats = "false"
input_descriptors = "true"
memory_descriptors = "false"
libretro_saves = "false"
core_options = "true"
core_options_version = "1.0"
load_subsystem = "false"
hw_render = "false"
needs_fullpath = "true"
disk_control = "false"
is_experimental = "false"
needs_kbd_mouse_focus = "true"

# BIOS/Firmware
firmware_count = 1
firmware0_desc = "5200.rom (5200 BIOS)"
firmware0_path = "5200.rom"
firmware0_opt = "false"
notes = "(!) 5200.rom (md5): 281f20ea4320404ec820fb7ec0693b38"
