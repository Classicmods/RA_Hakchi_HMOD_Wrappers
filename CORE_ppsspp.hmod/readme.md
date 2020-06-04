-----------------------
Name: Ppsspp
Creator: Libretro
Category: Libretro RetroArch Cores
-----------------------
![Libretro Cores](https://modmyclassic.com/wp-content/uploads/2020/06/LibRetroNeoCoresSmall.png)

=== Ppsspp Core for RetroArch ===

Module adds support for Ppsspp

Available executables and arguments to run Core:
- /bin/ppsspp <rom> <clover_args>

These cores are automatically built against the latest LibRetro Source code. You can find nightly builds and stable builds [here](https://modmyclassic.com/hmodcores)

Core by Libretro

Libretro 'Neo' Classic platform maintained by [ModMyClassic](https://modmyclassic.com) [Discord](https://modmyclassic.com/discord)

-----------------------

display_name = "Sony - PlayStation Portable (PPSSPP)"
authors = "Henrik Hrydgard"
supported_extensions = "elf|iso|cso|prx|pbp"
corename = "PPSSPP"
manufacturer = "Sony"
categories = "Emulator"
systemname = "PSP"
systemid = "playstation_portable"
database = "Sony - PlayStation Portable"
license = "GPLv2"
permissions = ""
display_version = "Git"
supports_no_game = "false"
firmware_count = 1
firmware0_desc = "ppge_atlas.zim (PPSSPP Data ROM)"
firmware0_path = "PPSSPP/ppge_atlas.zim"
firmware0_opt = "false"
notes = "(!) ppge_atlas.zim (md5): a93fc411c1ce7d001a2a812643c70085|(!) PPSSPP requires the asset files, lang folder, and flash0 folder inside the 'system\PPSSPP' directory.|(!) Check https://docs.libretro.com/library/ppsspp/#bios to find out how to get the assets files."
required_hw_api = "OpenGL Core >= 3.1 | OpenGL ES >= 2.0 | Vulkan >= 1.0 | Direct3D11 >= 11.0"
