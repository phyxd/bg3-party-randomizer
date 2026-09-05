# BG3 Party Randomizer and companion

- [Party randomizer](https://phyxd.github.io/bg3-party-randomizer/)
- [Bhaal Till You Fall companion](https://phyxd.github.io/bg3-party-randomizer/companion/)
- [Printable party guide](https://phyxd.github.io/bg3-party-randomizer/companion/party-guide.html)

Companion UI release 3.0.0, September 5, 2026. This repository contains generated deployment assets. The source project remains the local Baldur's Gate project; regenerate assets from the canonical guides and app sources before replacing them here.

The release passed 39 local automated tests, point-buy checks for 202 builds, desktop/mobile browser checks, import recovery, offline reload and exact item variant selection. That validates application behavior, not every BG3 mod mechanic.

Browser data is local to each device and origin. Export JSON in Save before moving between files, URLs or devices. Import it in the hosted companion. Open online once to initialize offline support; browser caches are not backups. Exact installed PS5 mods and mechanics still need in-game verification.

GitHub Pages deploys main from the repository root. Keep companion/index.html, manifest.webmanifest and sw.js together. The service worker is scoped to the companion folder.

The 3.0.0 interface adds a session-focused Camp, character workspaces, current-level combat guidance, searchable Armory, streamlined Loot, chapter navigation and a dedicated Save screen. Desktop sidebar and phone bottom navigation share the same saved-data format as 2.2.0. Browser checks cover all six sections at phone and tablet widths, desktop editing, draft/filter retention, import validation and offline reload.

