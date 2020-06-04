-----------------------
Name: Px68k
Creator: Libretro
Category: Libretro RetroArch Cores
-----------------------
![Libretro Cores](https://modmyclassic.com/wp-content/uploads/2020/06/LibRetroNeoCoresSmall.png)

=== Px68k Core for RetroArch ===

Module adds support for Px68k

Available executables and arguments to run Core:
- /bin/px68k <rom> <clover_args>
- /bin/sharp <rom> <clover_args>

These cores are automatically built against the latest LibRetro Source code. You can find nightly builds and stable builds [here](https://modmyclassic.com/hmodcores)

Core by Libretro

Libretro 'Neo' Classic platform maintained by [ModMyClassic](https://modmyclassic.com) [Discord](https://modmyclassic.com/discord)

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
