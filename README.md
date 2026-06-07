# Realm of Echoes

*Created by Picco Iacopelli*

A full browser-based RPG built in a single HTML file with zero dependencies. Six distinct regions, six Echo Shards to recover, twelve original creatures, and a final boss with a pacifist ending.

## Gameplay

The Echo Stone has shattered into six fragments, each claimed by a different corner of the world. Travel east through six regions — Verdant Wood, Amber Desert, Frost Wastes, Shadowfen, Stone Peaks, and Ember Caldera — defeat or spare the guardian at each shard tower, and face The Unmade at the world's edge.

### Controls

**Desktop:** Arrow keys to move, Enter/Space to interact  
**Mobile:** D-pad buttons to move, ENTER button to interact with villages, shops, and exits

### Battle Actions

- **FIGHT** — Deal physical damage
- **COMMUNE** — Learn about the enemy; unlocks SPARE
- **ECHO BLAST** — Magic attack (costs 4 MP)
- **POTION** — Restore 8 HP (limited supply)
- **SPARE** — Resolve the encounter without fighting (requires COMMUNE first)

### Villages

Each region has a village with a **Merchant** (gear upgrades) and an **Inn** (full HP/MP restore for 12g). Walk into the village area and press the gold ENTER button. Inside, walk to the shop or inn tile and press the button that appears.

### Endings

Spare every creature — including The Unmade — to see the True Ending.

## Regions & Enemies

| Region | Enemies |
|--------|---------|
| 🌿 Verdant Wood | Moss Lurker, Briar Wraith |
| 🏜️ Amber Desert | Dune Crawler, Sand Revenant |
| ❄️ Frost Wastes | Frost Imp, Glacier Wyrm |
| 🌑 Shadowfen | Fen Haunt, Ruin Warden |
| ⛰️ Stone Peaks | Stoneback Brute, Peak Specter |
| 🌋 Ember Caldera | Ember Hound, Lava Golem |

## Technical

- Single HTML file, vanilla JS/CSS, no frameworks, no build step
- Deployable directly to GitHub Pages
- Fully responsive — canvas scales to any screen size via `devicePixelRatio`
- All state in memory; no backend required
- Font: [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P) via Google Fonts

## Definition of Complete

- [x] Six traversable regions with distinct tile rendering
- [x] Twelve original enemies with unique dialogue and spare conditions
- [x] Turn-based battle system with FIGHT / COMMUNE / ECHO BLAST / POTION / SPARE
- [x] XP and leveling system with stat scaling
- [x] Equipment shop (weapon, armor, tome) and inn in each village
- [x] Six shard towers with boosted guardians
- [x] Final boss with pacifist and combat endings
- [x] Mobile-friendly with d-pad controls and interact button
- [x] Responsive canvas scaling for all screen sizes
