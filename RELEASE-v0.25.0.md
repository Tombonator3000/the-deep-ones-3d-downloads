# The Deep Ones 0.25 — Abyss Expedition

Public playtest for Windows and Linux (64-bit).

- The final Havdjupet expedition now continues below the trawler, along a visible lifeline to the submerged threshold.
- Walk the seabed, inspect Father's equipment, recover the unique idol, restore the mechanism, and choose whether to seal the passage or keep watch.
- The hard-hat diving rig presents the human descent. A permanently transformed player keeps the Deep One form throughout the same route and ending choices.
- The native underwater treatment adds the adapted trawler and diver, 720 decorative background fish, Norwegian seabed plants, suspended matter, caustics and stronger depth-dependent light. Catchable fish remain separate.
- An interrupted descent recovers safely. Completing the ascent commits the ending and returns play to ordinary fishing; revisits do not duplicate the idol or rewards.
- The field book, campaign, supplied music, 0.24 environment sounds, settings and prior ending progress remain available.

A/D rows or walks, Space fishes or inspects, E begins the descent at the Havdjupet threshold, and Backspace requests an early return underwater. Controls can still be rebound where supported by the settings menu.

Existing 0.24 saves migrate to format 8 on load and retain a version-7 backup. Existing endings and idol ownership are preserved. Saves written by 0.25 require 0.25 or a later compatible version.

The procedural expedition art adapts a user-supplied Antikythera HTML reference into native game assets and code. The source HTML and its Three.js dependency are not distributed. This release does not claim a complete recreation of the reference.

Download the platform archive, extract everything, and start `TheDeepOnes.exe` or `Start-Linux.sh`. No account is required. GitHub's automatic source archives contain only the public download page.

Both platform builds are complete. Scoped native Linux tests passed both diving routes, interrupted returns, saved progress, Continue and ordinary fishing, using staged late-game prerequisites and injected engine input. Windows execution, physical controllers and a human full-campaign playthrough remain unverified. At 1600×900 on Intel ARL, the dive averaged 59.35 fps and fishing/harbour about 60 fps, with one 359 ms dive stall and one 68 ms harbour stall. No stable 60 fps claim is made.

The archives contain compiled runtime files, launch instructions, version information, asset provenance and retained third-party notices for fonts, environment recordings and Linux libdecor. Internal QA reports, authoring source and debug-only output are excluded.
