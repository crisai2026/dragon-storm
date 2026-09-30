# Dragon Storm — Specification

## Format
- Single HTML file with JavaScript, no external dependencies, runs in the browser.

## Concept
A fighter inspired by Dragon Ball gets stronger by absorbing energy from storms and earthquakes. The fighter shoots energy blasts and uses martial arts moves, and is trying to save the universe from being erased. Some enemies or bosses are giant monsters, similar to Godzilla. The game combines anime action with the excitement of powerful natural events.

All characters are original designs *inspired by* these references. No copyrighted characters are drawn or named.

## 1. Story
- The player character is a Hero: the best martial artist in the universe.
- The universe is being erased by the Void.
- Rival: Vorak.
- Bosses (original designs, archetypes from user references):
  - Zarkon the Tyrant: conqueror type.
  - Mutagen: absorbs fighters and heals when he hits you.
  - Magmora: regenerates.
  - Gorrath, the Titan: giant kaiju, the pre-final boss.
  - Karvon, Void Warrior: stoic ultimate warrior, the final boss.

## 2. World
- Planet Raiko.
- Levels:
  1. Raiko Plains: storms, lightning. Boss: Zarkon.
  2. Quake Canyon: earthquakes, meteors. Boss: Mutagen.
  3. The Truce: burger restaurant scene with Vorak (the McDonald's scene, drawn generically). **Improvement is pending — needs scoping.**
  4. Ashfall Ridge: volcanic geysers, tornado. Boss: Magmora.
  5. Edge of Erasure: Gorrath (screen-filling).
  6. The Void Arena: Karvon.

## 3. Mechanics
Genre: Run and jump (platformer).

### Original rules
1. **Jumping:** double jump before landing.
2. **Energy blast vs. enemy:** a blast hit destroys a regular enemy instantly. *Bosses are the exception and have health bars (user asked for stronger bosses).*
3. **Storm healing:** walking into a storm gives +25 health.
4. **Scoring:** 50 points per energy blast that hits an enemy (the beam counts as a blast).
5. **Lives:** 3 lives; the game ends when all are gone.

### Added at user request
6. **Ki:** energy power used for blasts and the beam. It refills over time.
7. **Flight:** infinite, no exhaustion (F).
8. **Transformations:** Base → Storm Surge → Thunder Fist → Quake God → Master Ultra Instinct, unlocked by absorbed energy.
9. **Instinct:** automatic dodge (30% in Base, 85% in Master Ultra Instinct), with an automatic counterattack when the attacker is close.
10. **Storm Cannon beam:** a planet-buster beam in the style of the Kamehameha. Hold C to charge, then release to fire. It pierces everything, can't be blocked, and destroys meteors and projectiles.
11. **Speed:** a story stat of 1.2 billion to 9 trillion × the speed of light, shown through afterimages, dash (Shift) and a HUD readout. On-screen speed stays playable.
12. **Natural disasters:** storms, earthquakes, lightning, meteor showers, volcanic geysers, tornado.

### Supporting numbers
All numbers are in the `CONFIG` block of the code (damage, boss HP, disaster timings, form stats, and so on).

## Audio
- Generated chiptune in minor, phrygian, and diminished keys, with sawtooth leads, drums, and a boss theme. No audio files. M mutes it.

## Working rules
- Separate modules: Story, World, Mechanics, Music.
- All adjustable numbers go in `CONFIG`.
- Build step by step; confirm after each step. Check against this file after every change.

## Build progress
- [x] Step 1: movement
- [x] Step 2: ki, flight, transformations, levels
- [x] Step 3: music
- [x] Step 4: fixes for stuck start / touch controls
- [x] Step 5: hero upgrades, new boss lineup, disasters, intimidating music. *Awaiting confirmation.*
- [x] Step 6: published to GitHub.
- [ ] Burger experience: waiting for scope.
