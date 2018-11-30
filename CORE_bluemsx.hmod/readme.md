-----------------------
Name: Bluemsx
Creator: Libretro
Category: Official RetroArch Cores
-----------------------

=== Bluemsx Core for RetroArch ===

Module adds support for Bluemsx

Available executables and arguments to run Core:
- /bin/bluemsx <rom> <clover_args>
- /bin/col <rom> <clover_args>
- /bin/msx <rom> <clover_args>

Core by Libretro

Libretro Classic platform maintained by [ModMyClassic](https://modmyclassic.com) [Discord](https://discordapp.com/invite/8gygsrw)

-----------------------

display_name = "MSX/SVI/ColecoVision/SG-1000 (blueMSX)"
authors = "Daniel Vik"
supported_extensions = "rom|ri|mx1|mx2|col|dsk|cas|sg|sc|m3u"
corename = "blueMSX"
manufacturer = "Various"
categories = "Emulator"
systemname = "MSX/SVI/ColecoVision/SG-1000"
systemid = "msx"
database = "Microsoft - MSX|Microsoft - MSX2|Coleco - ColecoVision|Sega - SG-1000"
license = "GPLv2"
permissions = ""
display_version = "SVN"
supports_no_game = "false"
notes = "(!) The libretro port of blueMSX requires the BIOS files|from full standalone package inside the 'System\Machines' directory |and media database files into 'System\Databases' directory.|https://docs.libretro.com/library/bluemsx/#bios|(!) ColecoVision Gamepad Mapping is as follow:|Button 1 as Retropad A|Button 2 as Retropad B|Dial keys 1 to 8 as X, Y, R, L, R2, L2, R3, L3|Star as Select, Hash as Start|0 & 9 are on keyboard 1 & 2 for Player 1|0 & 9 are on keyboard 3 & 4 for Player 2.|(!) To play SpectraVideo cassettes type 'cload' then 'run'|or BLOAD ''CAS:'',R depending of game."
