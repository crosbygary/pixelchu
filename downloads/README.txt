Pocket Meadow — original movement test cartridges

Contents: GB/GBC (.gbc), GBA (.gba), NES (.nes), SNES (.sfc).
D-pad: move. A: change appearance while held. Start: return to center.
The GBC cartridge also supports original GB hardware mode.

These are tiny movement tests, not full games or commercial ROMs.
Original code and graphics: Copyright (c) 2026 Pixelchu contributors.
MIT License: see LICENSE.txt. Keep that notice when redistributing.
Standard cartridge recognition signatures are documented in the source.
No commercial BIOS or emulator cores are included.

On iPhone, save a cartridge to Files, open Pixelchu, select My games,
tap Import a game and choose the file. Extract ZIPs in Files first.

Source: pocket-meadow-source.zip. Extract it and run:
  python3 Homebrew/build.py
Building the GBA demo requires macOS with Xcode command-line tools.
The other generators use Python's standard library. Generated files are
written to Pixelchu/Resources/Demos. The original SPC700 upload bootstrap
is generated separately under Pixelchu/Resources; it is not a game.
The GBA demo targets emulators and omits original boot-logo artwork.

Contact: cr0sby_gar@icloud.com
