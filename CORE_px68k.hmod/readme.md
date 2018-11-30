-----------------------
Name: Px68k
Creator: Libretro
Category: Official RetroArch Cores
-----------------------

=== Px68k Core for RetroArch ===

Module adds support for Px68k

Available executables and arguments to run Core:
- /bin/px68k <rom> <clover_args>
- /bin/sharp <rom> <clover_args>

Core by Libretro

Libretro Classic platform maintained by [ModMyClassic](https://modmyclassic.com) [Discord](https://discordapp.com/invite/8gygsrw)

-----------------------

display_name = "Sharp - X68000 (PX68k)"
authors = "hissorii"
supported_extensions = "dim|zip|img|d88|88d|hdm|dup|2hd|xdf|hdf|cmd|m3u"
corename = "PX68k"
manufacturer = "Sharp"
categories = "Emulator"
systemname = "Sharp X68000"
systemid = "sharp_x68000"
database = "Sharp - X68000"
license = ""
permissions = ""
display_version = "0.15+"
supports_no_game = "false"
firmware_count = 3
firmware0_desc = "iplrom.dat (X68000 BIOS)"
firmware0_path = "keropi/iplrom.dat"
firmware0_opt = "false"
firmware1_desc = "cgrom.dat (X68000 BIOS 2)"
firmware1_path = "keropi/cgrom.dat"
firmware1_opt = "false"
firmware2_desc = "iplrom30.dat (X68000 BIOS 3)"
firmware2_path = "keropi/iplrom30.dat"
firmware2_opt = "true"
notes = "[i] Place BIOS files in system/keropi folder.|[i] F12 or Retropad L2 for Emulator Menu.|[i] Define your disks path in system/keropi/config StartDir line."