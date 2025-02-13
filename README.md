# Overview

This is the base rom source code for the [DASH Randomizer](https://dashrando.github.io/) which
is used to build base rom patches for the higher-level randomizer ([source](https://github.com/dashrando/dashrando.github.io/tree/development))
All SNES code for the randomizer goes here and the randomizer makes data writes.

# Building

Building requires putting your dump of the Super Metroid ROM in the `build/` directory. The vanilla
ROM should be named `supermetroid.sfc`. The build scripts will produce a Recall and a Standard base
rom (.sfc) and patch (.bps).

**Linux**: Run build.sh in a bash shell

**Windows**: Run build.bat

**Mac**: Currently no build script for MacOS, but an asar binary is included in the `bin/` directory.

# Acknowledgements

The DASH Randomizer and base rom would not have been possible without contributions of several
ROM hackers and reverse engineers:

**total**: The base ROM is based on the ROM for total's Super Metroid Randomizer and contains code
originally written for that and the SMZ3 base ROM including the credits code, PLM code, and various
fixes and QOL changes.

**Smiley**: DASH tiles such as the spazer blocks, suit changes for the original DASH Randomizer.

**Personitis**: Max Ammo HUD

**PJBoy**: Super Metroid disassembly

**Kejardon**: Super Metroid disassembly and message box code.
