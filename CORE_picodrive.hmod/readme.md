-----------------------
Name: Picodrive
Creator: Libretro
Category: Official RetroArch Cores
-----------------------

=== Picodrive Core for RetroArch ===

Module adds support for Picodrive

Available executables and arguments to run Core:
- /bin/32x <rom> <clover_args>
- /bin/picodrive <rom> <clover_args>

Core by Libretro

Libretro Classic platform maintained by [ModMyClassic](https://modmyclassic.com) [Discord](https://discordapp.com/invite/8gygsrw)

-----------------------

display_name = "Sega - MS/MD/CD/32X (PicoDrive)"
authors = "notaz|fdave"
supported_extensions = "bin|gen|smd|md|32x|cue|iso|sms|68k"
corename = "PicoDrive"
manufacturer = "Sega"
categories = "Emulator"
systemname = "Sega 8/16-bit + 32X (Various)"
systemid = "mega_drive"
database = "Sega - Master System - Mark III|Sega - Mega-CD - Sega CD|Sega - Mega Drive - Genesis|Sega - PICO|Sega - 32X"
license = "MAME"
permissions = "dynarec_optional"
display_version = "1.91"
supports_no_game = "false"
firmware_count = 3
firmware0_desc = "bios_CD_E.bin (MegaCD EU BIOS)"
firmware0_path = "bios_CD_E.bin"
firmware0_opt = "false"
firmware1_desc = "bios_CD_U.bin (SegaCD US BIOS)"
firmware1_path = "bios_CD_U.bin"
firmware1_opt = "false"
firmware2_desc = "bios_CD_J.bin (MegaCD JP BIOS)"
firmware2_path = "bios_CD_J.bin"
firmware2_opt = "false"
notes = "(!) bios_CD_U.bin (md5): 2efd74e3232ff260e371b99f84024f7f|(!) bios_CD_E.bin (md5): e66fa1dc5820d254611fdcdba0662372|(!) bios_CD_J.bin (md5): 278a9397d192149e84e820ac621a8edd"