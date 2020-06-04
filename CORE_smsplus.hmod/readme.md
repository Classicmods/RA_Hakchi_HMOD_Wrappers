-----------------------
Name: Smsplus
Creator: Libretro
Category: Libretro RetroArch Cores
-----------------------
![Libretro Cores](https://modmyclassic.com/wp-content/uploads/2020/06/LibRetroNeoCoresSmall.png)

=== Smsplus Core for RetroArch ===

Module adds support for Smsplus

Available executables and arguments to run Core:
- /bin/smsplus <rom> <clover_args>

These cores are automatically built against the latest LibRetro Source code. You can find nightly builds and stable builds [here](https://modmyclassic.com/hmodcores)

Core by Libretro

Libretro 'Neo' Classic platform maintained by [ModMyClassic](https://modmyclassic.com) [Discord](https://modmyclassic.com/discord)

-----------------------

display_name = "Sega - MS/GG (SMS Plus GX)"
authors = "Charles MacDonald|gameblabla"
supported_extensions = "sms|bin|rom|col|gg"
corename = "SMS Plus GX"
manufacturer = "Sega"
categories = "Emulator"
systemname = "Sega 8-bit"
systemid = "master_system"
database = "Sega - Game Gear|Sega - Master System - Mark III"
license = "GPLv2"
permissions = ""
display_version = "1.8"
supports_no_game = "false"

# BIOS/Firmware
firmware_count = 2

firmware0_desc = "bios.sms (Master System BIOS)"
firmware0_path = "bios.sms"
firmware0_opt = "true"

firmware1_desc = "BIOS.col (Colecovision BIOS)"
firmware1_path = "BIOS.col"
firmware1_opt = "true"
