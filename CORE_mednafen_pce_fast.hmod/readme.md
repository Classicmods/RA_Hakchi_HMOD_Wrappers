-----------------------
Name: Mednafen_pce_fast
Creator: Libretro
Category: Official RetroArch Cores
-----------------------

=== Mednafen_pce_fast Core for RetroArch ===

Module adds support for Mednafen_pce_fast

Available executables and arguments to run Core:
- /bin/pce <rom> <clover_args>
- /bin/pcecd <rom> <clover_args>

Core by Libretro

Libretro Classic platform maintained by [ModMyClassic](https://modmyclassic.com) [Discord](https://discordapp.com/invite/8gygsrw)

-----------------------

display_name = "NEC - PC Engine / CD (Beetle PCE FAST)"
authors = "Mednafen Team"
supported_extensions = "pce|cue|ccd|iso|img|bin|chd"
corename = "Beetle PCE Fast"
manufacturer = "NEC"
categories = "Emulator"
systemname = "PC Engine/PCE-CD"
systemid = "pc_engine"
database = "NEC - PC Engine - TurboGrafx 16|NEC - PC Engine CD - TurboGrafx-CD"
license = "GPLv2"
permissions = ""
display_version = "v0.9.38.7"
supports_no_game = "false"
firmware_count = 4
firmware0_desc = "syscard3.pce (PCE-CD BIOS)"
firmware0_path = "syscard3.pce"
firmware0_opt = "false"
firmware1_desc = "syscard2.pce (PCE-CD BIOS)"
firmware1_path = "syscard2.pce"
firmware1_opt = "true"
firmware2_desc = "syscard1.pce (PCE-CD BIOS)"
firmware2_path = "syscard1.pce"
firmware2_opt = "true"
firmware3_desc = "gexpress.pce (PCE-CD BIOS)"
firmware3_path = "gexpress.pce"
firmware3_opt = "true"
notes = "(!) syscard3.pce (md5): 38179df8f4ac870017db21ebcbf53114|[i] For cue files track type use:|[i] OGG for ogg files|[i] WAVE for wav files|[i] BINARY for iso files"