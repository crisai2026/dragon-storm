# Dragon Storm

An anime-style browser platformer. A Hero on Planet Raiko absorbs energy from storms, earthquakes and other natural disasters to grow stronger, transform, and save the universe from being erased by the Void.

## Play

- **Online:** https://crisai2026.github.io/dragon-storm/ (once GitHub Pages is enabled)
- **Offline:** download `index.html` and open it in any browser. No install, no dependencies.

Click the game once so it receives your keyboard input.

## Controls

| Key | Action |
| --- | --- |
| ← → | Run |
| Space | Jump (press again in the air to double jump) |
| F | Fly on/off (infinite), ↑ ↓ to move up and down |
| X | Ki blast |
| Hold C | Charge the Storm Cannon beam, release to fire |
| Z | Punch |
| Shift | Dash |
| T / G | Transform / power down |
| P | Pause |
| M | Music on/off |
| Enter or click | Continue text |

On phones and tablets, use the on-screen buttons.

## Levels

1. Raiko Plains: storms and lightning. Boss: Zarkon the Tyrant
2. Quake Canyon: earthquakes and meteors. Boss: Mutagen
3. The Truce: lunch with your rival Vorak
4. Ashfall Ridge: volcanic geysers and a tornado. Boss: Magmora
5. Edge of Erasure: Gorrath, the Titan
6. The Void Arena: Karvon, Void Warrior

## Transformations

Base → Storm Surge → Thunder Fist → Quake God → Master Ultra Instinct

## For developers

- All game design rules are in [`SPEC.md`](SPEC.md).
- The code is split into `Story`, `World`, `Mechanics` and `Music` modules inside `index.html`.
- Every adjustable number (speeds, damage, boss health, points, lives) is in the `CONFIG` block at the top of the script.

All characters are original designs.
