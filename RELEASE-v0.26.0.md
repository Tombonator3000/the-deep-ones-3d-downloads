# The Deep Ones 0.26 — Refracted Waters

Public playtest for Windows and Linux (64-bit).

- Underwater scene colour now receives restrained, bounded refraction while the surface view and interface remain stable.
- Irregular caustics and directional light shafts respond to scene receivers and fade with depth, weather and night.
- Reduced Motion disables refraction distortion. Reduced Flashes removes chromatic separation and limits caustic intensity.
- Storms form coherent dark masses with directional edge light and distant rain curtains. The cloud field stays anchored in world space and keeps its established one-way drift while the boat moves.
- The complete 0.25 Abyss Expedition, eight waters, campaign, endings, field book, music and environmental audio remain available.

A/D rows or walks, Space fishes or inspects, E begins the Havdjupet descent, and Backspace requests an early underwater return. Controls can still be rebound where supported by the settings menu.

Save format remains version 8. Existing 0.25 progress, endings, idol ownership and settings are retained.

The visual update uses the existing authored assets and native Unity shader pipeline. It adds no new copyrighted source asset. Retained Abyss Expedition models, fonts, music and environmental recordings keep their existing provenance and notices.

Download the platform archive, extract everything, and start `TheDeepOnes.exe` or `Start-Linux.sh`. No account is required. GitHub's automatic source archives contain only the public download page.

Candidate 06 native Linux A/B checks cover fair shallows, accessibility variants, day and night storms, the deep expedition and deep night using staged states and injected engine input. Windows execution, physical controllers and a full human campaign remain unverified. Measured performance and remaining stalls are recorded below. No stable 60 fps claim is made.

The archives contain compiled runtime files, launch instructions, version information, asset provenance and retained third-party notices for fonts, environmental recordings and Linux libdecor. Internal QA reports, authoring source and debug-only output are excluded.

## Measured performance

Storm: 60.00 fps average, p95 20.93 ms, maximum 29.86 ms. Walking deep expedition: 60.00 fps average, p95 20.85 ms, maximum 30.76 ms. Neither 120-second sample had an interval over 50 ms. Both pass the measured 30 fps floor and the stricter zero-hitch check for these samples. Intel Core Ultra 5 225U / Mesa Intel ARL / OpenGL Core, 1600 × 900, 60 fps cap, 30-second warm-up per run. This does not establish stable 60 fps throughout the campaign or on other hardware.
