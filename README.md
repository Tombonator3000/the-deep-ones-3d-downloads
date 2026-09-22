# The Deep Ones — public playtest

A Norwegian fishing mystery: familiar waters, strange catches, and your father's field book.

## Download 0.25 — Abyss Expedition

No GitHub account is needed.

- [Windows (64-bit, ZIP)](https://github.com/Tombonator3000/the-deep-ones-3d-downloads/releases/latest/download/TheDeepOnes-Windows.zip)
- [Linux (64-bit, tar.gz)](https://github.com/Tombonator3000/the-deep-ones-3d-downloads/releases/latest/download/TheDeepOnes-Linux.tar.gz)
- [Release notes and checksums](https://github.com/Tombonator3000/the-deep-ones-3d-downloads/releases/latest)

**Windows:** Extract the entire ZIP into a folder, then run `TheDeepOnes.exe`. Keep its data folder and libraries beside it.

**Linux:** Extract the archive, then run `./Start-Linux.sh`. If executable permissions were removed, run `chmod +x Start-Linux.sh TheDeepOnes.x86_64` first.

Use the in-game **How to play** menu for controls. A/D rows the boat and walks the seabed. Space remains the main fishing button and inspects objects during the dive. E begins the descent at the Havdjupet threshold. Backspace returns to the boat during an unfinished dive.

0.25 adds a late-game descent from the expedition trawler to the submerged threshold. Follow the lifeline, inspect Father's equipment, recover the missing idol, seat it in the mechanism, and choose whether to seal the passage or keep watch. A human uses the hard-hat diving rig; a player who permanently became a Deep One keeps that form. Returning to the boat restores ordinary fishing.

The underwater presentation adds the adapted trawler and diver, 720 decorative background fish, Norwegian vegetation, suspended matter, caustics and depth-dependent light. These schools do not replace catchable fish. The procedural work adapts a user-supplied Antikythera reference into native game assets; the original HTML and its external library are not shipped, and full source fidelity is not claimed.

Existing 0.24 saves load through format 8 and receive a version-7 migration backup. Existing endings, idol ownership, field-book progress, settings, supplied music and the 0.24 environment audio remain. Saves written by 0.25 require 0.25 or a later compatible version.

This is a work-in-progress playtest. Both platform builds are complete. Scoped native Linux tests passed both diving routes, interrupted returns, saved progress, Continue and ordinary fishing, using staged late-game prerequisites and injected engine input. Windows execution, physical controllers and a human full-campaign playthrough remain unverified. At 1600×900 on Intel ARL, the dive averaged 59.35 fps and fishing/harbour about 60 fps, with one 359 ms dive stall and one 68 ms harbour stall. No stable frame-rate claim is made.

This repository contains download information only. The game source remains private. GitHub's automatic “Source code” archives contain this page, not the playable game; use the platform downloads above.

The release tagged `v0.24.0` and its assets remain available. Stable latest-download filenames point to the newest public build.
