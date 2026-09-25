# The Deep Ones 0.27 — Sunlit Waters

Public playtest for Windows and Linux (64-bit).

- Water has area-specific colour, new surface light, crest foam and restrained glitter.
- Sky, clouds, rays, golden-hour light and underwater lamp response receive a visual pass.
- Individual fish size and weight now influence the fight; stamina, runs, head shakes and slack-line loss make the encounter more active.
- The rod bends through its length, and the field book records personal bests.
- The complete 0.26 game, eight waters, expedition, story, field guide, music and environmental audio remain available.

A/D rows or walks, Space fishes or inspects, E begins the Havdjupet descent, and Backspace requests an early underwater return. The in-game **How to play** menu explains the current controls.

Save format remains version 8. Existing progress and settings are retained.

Download the platform archive, extract everything, and start `TheDeepOnes.exe` or `Start-Linux.sh`. No account is required. GitHub's automatic source archives contain only the public download page.

The archives include compiled runtime files, launch instructions and third-party notices. The new visual and fishing work adds no third-party assets. Windows execution, physical controllers and a full human campaign remain separate unverified checks.

Unity 6000.3.22f1 imported the project and built both 64-bit players from the same source snapshot. The Linux player passed staged visual checks, a fresh fishing journey with two real catches, release/keep, sale and Continue, and a separate line-motion check. The extracted archive and installed launcher are checked separately.

## Measured Linux scope

At 1600 × 900 on Intel Core Ultra 5 225U / Mesa Intel ARL / OpenGL Core, each sample had 30 seconds of warm-up. The 120-second storm sample averaged 59.99 fps (p95 20.97 ms, maximum 27.60 ms); the 120-second walking deep expedition averaged 59.99 fps (p95 20.98 ms, maximum 29.01 ms). Neither had an interval over 50 ms. The 130-second active fight averaged 59.99 fps (p95 17.18 ms, minimum instantaneous 42.53 fps), with no frame below 30 fps. These scoped tests do not establish stable 60 fps throughout the game or on other hardware.
