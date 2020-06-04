-----------------------
Name: Flycast
Creator: Libretro
Category: Libretro RetroArch Cores
-----------------------
![Libretro Cores](https://modmyclassic.com/wp-content/uploads/2020/06/LibRetroNeoCoresSmall.png)

=== Flycast Core for RetroArch ===

Module adds support for Flycast

Available executables and arguments to run Core:
- /bin/flycast <rom> <clover_args>

These cores are automatically built against the latest LibRetro Source code. You can find nightly builds and stable builds [here](https://modmyclassic.com/hmodcores)

Core by Libretro

Libretro 'Neo' Classic platform maintained by [ModMyClassic](https://modmyclassic.com) [Discord](https://modmyclassic.com/discord)

-----------------------

display_name = "Sega - Dreamcast/NAOMI (Flycast)"
authors = "flyinghead"
supported_extensions = "chd|cdi|iso|elf|bin|cue|gdi|lst|zip|dat|7z|m3u"
corename = "Flycast"
manufacturer = "Sega"
categories = "Emulator"
systemname = "Sega Dreamcast"
systemid = "dreamcast"
database = "Sega - Dreamcast|Sega - NAOMI"
license = "GPLv2"
permissions = ""
display_version = "Git"
supports_no_game = "false"
firmware_count = 8
firmware0_desc = "dc/dc_boot.bin (Dreamcast BIOS)"
firmware0_path = "dc/dc_boot.bin"
firmware0_opt = "true"
firmware1_desc = "dc/dc_flash.bin (Date/Time/Language)"
firmware1_path = "dc/dc_flash.bin"
firmware1_opt = "true"
firmware2_desc = "dc/naomi.zip (Naomi Bios from MAME)"
firmware2_path = "dc/naomi.zip"
firmware2_opt  = "true"
firmware3_desc = "dc/hod2bios.zip (Naomi The House of the Dead 2 Bios from MAME)"
firmware3_path = "dc/hod2bios.zip"
firmware3_opt  = "true"
firmware4_desc = "dc/f355dlx.zip (Naomi Ferrari F355 Challenge deluxe Bios from MAME)"
firmware4_path = "dc/f355dlx.zip"
firmware4_opt  = "true"
firmware5_desc = "dc/f355bios.zip (Naomi Ferrari F355 Challenge twin/deluxe Bios from MAME)"
firmware5_path = "dc/f355bios.zip"
firmware5_opt  = "true"
firmware6_desc = "dc/airlbios.zip (Naomi Airline Pilots deluxe Bios from MAME)"
firmware6_path = "dc/airlbios.zip"
firmware6_opt  = "true"
firmware7_desc = "dc/awbios.zip (Atomiswave BIOS from MAME)"
firmware7_path = "dc/awbios.zip"
firmware7_opt  = "true"
notes = "(!) dc_boot.bin (md5): e10c53c2f8b90bab96ead2d368858623|(!) dc_flash.bin (md5): 0a93f7940c455905bea6e392dfde92a4|(!) naomi.zip|(!) hod2bios.zip|(!) f355dlx.zip|(!) f355bios.zip|(!) airlbios.zip|(!) awbios.zip"
required_hw_api = "OpenGL Core >= 3.0 | OpenGL ES >= 2.0"
