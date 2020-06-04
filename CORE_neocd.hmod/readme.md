-----------------------
Name: Neocd
Creator: Libretro
Category: Libretro RetroArch Cores
-----------------------
![Libretro Cores](https://modmyclassic.com/wp-content/uploads/2020/06/LibRetroNeoCoresSmall.png)

=== Neocd Core for RetroArch ===

Module adds support for Neocd

Available executables and arguments to run Core:
- /bin/neocd <rom> <clover_args>

These cores are automatically built against the latest LibRetro Source code. You can find nightly builds and stable builds [here](https://modmyclassic.com/hmodcores)

Core by Libretro

Libretro 'Neo' Classic platform maintained by [ModMyClassic](https://modmyclassic.com) [Discord](https://modmyclassic.com/discord)

-----------------------

display_name = "SNK - Neo Geo CD (NeoCD)"
authors = "Elta"
supported_extensions = "cue|chd"
corename = "NeoCD"
manufacturer = "SNK"
categories = "Emulator"
systemname = "SNK Neo Geo CD"
database = "SNK - Neo Geo CD"
license = "LGPLv3"
display_version = "2019"
supports_no_game = "false"

# BIOS/Firmware
firmware_count = 12

firmware0_desc = "neocd/neocd_f.rom (Front Loader BIOS)"
firmware0_path = "neocd/neocd_f.rom"
firmware0_opt = "true"

firmware1_desc = "neocd/neocd_sf.rom (Front Loader BIOS (SMKDAN))"
firmware1_path = "neocd/neocd_sf.rom"
firmware1_opt = "true"

firmware2_desc = "neocd/front-sp1.bin (Front Loader BIOS (MAME))"
firmware2_path = "neocd/front-sp1.bin"
firmware2_opt = "true"

firmware3_desc = "neocd/neocd_t.rom (Top Loader BIOS))"
firmware3_path = "neocd/neocd_t.rom"
firmware3_opt = "true"

firmware4_desc = "neocd/neocd_st.rom (Top Loader BIOS (SMKDAN))"
firmware4_path = "neocd/neocd_st.rom"
firmware4_opt = "true"

firmware5_desc = "neocd/top-sp1.bin (Top Loader BIOS (MAME))"
firmware5_path = "neocd/top-sp1.bin"
firmware5_opt = "true"

firmware6_desc = "neocd/neocd_z.rom (CDZ BIOS)"
firmware6_path = "neocd/neocd_z.rom"
firmware6_opt = "true"

firmware7_desc = "neocd/neocd_sz.rom (CDZ BIOS (SMKDAN))"
firmware7_path = "neocd/neocd_sz.rom"
firmware7_opt = "true"

firmware8_desc = "neocd/neocd.bin (CDZ BIOS (MAME))"
firmware8_path = "neocd/neocd.bin"
firmware8_opt = "true"

firmware9_desc = "neocd/ng-lo.rom (Y-ZOOM ROM)"
firmware9_path = "neocd/ng-lo.rom"
firmware9_opt = "true"

firmware10_desc = "neocd/000-lo.lo (Y-ZOOM ROM (MAME))"
firmware10_path = "neocd/000-lo.lo"
firmware10_opt = "true"

firmware11_desc = "neocd/uni-bioscd.rom (Universe BIOS 3.2)"
firmware11_path = "neocd/uni-bioscd.rom"
firmware11_opt = "true"

notes = "(!) neocd/neocd_f.rom (sha1): a5f4a7a627b3083c979f6ebe1fabc5d2df6d083b|(!) neocd/neocd_sf.rom (sha1): c99c44a43bded1bff4570b30b74975601bd3f94e|(!) neocd/front-sp1.bin (sha1): 53bc1f283cdf00fa2efbb79f2e36d4c8038d743a|(!) neocd/neocd_t.rom (sha1): cc92b54a18a8bff6e595aabe8e5c360ba9e62eb5|(!) neocd/neocd_st.rom (sha1): d463b3a322b9674f9e227a21e43898019ce0e642|(!) neocd/top-sp1.bin (sha1): 235f4d1d74364415910f73c10ae5482d90b4274f|(!) neocd/neocd_z.rom (sha1): b0f1c4fa8d4492a04431805f6537138b842b549f|(!) neocd/neocd_sz.rom (sha1): 41ca1c031b844a46387be783ac862c76e65afbb3|(!) neocd/neocd.bin (sha1): 7bb26d1e5d1e930515219cb18bcde5b7b23e2eda|(!) neocd/ng-lo.rom (sha1): 2b1c719531dac9bb503f22644e6e4236b91e7cfc|(!) neocd/000-lo.lo (sha1): 5992277debadeb64d1c1c64b0a92d9293eaf7e4a|(!) neocd/uni-bioscd.rom (sha1): 5158b728e62b391fb69493743dcf7abbc62abc82"