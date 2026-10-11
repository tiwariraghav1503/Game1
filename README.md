# 🎡 Wheel Runner

An infinite runner where a prize wheel picks your level.

## ▶ Play it

**https://tiwariraghav1503.github.io/Game1/**

Works in any modern browser, on desktop or phone (landscape is best on phones).

## How to play

Spin the wheel to pick a level, then run, jump and shoot. Collect 💎 diamonds, spend them in the shop, and beat a boss every 10 levels.

| Action | Keys | Touch |
| --- | --- | --- |
| Jump (hold in the air for rocket shoes) | Space / ↑ / W | tap the top of the screen |
| Slide | ↓ / S | hold the bottom of the screen |
| Attack | F / X / Z | FIRE |
| Switch weapon | Q or 1–9, 0, - | SWAP |
| Dash (boss perk) | E / Shift | DASH |
| Battle tank | T | TANK |
| Battle mech (switch its weapon: Q / 1–3) | V | MECH |
| Astronaut jetpack | G or pinch | pinch with two fingers |
| Switch hero (title and crash screens) | H, [ ], ← → | ◀ ▶ buttons |
| Music / sound effects | M / N | 🎵 / 🔊 buttons |

## What's in it

- 12 wheel levels, each with its own music, plus wheel modifiers (double gems, low gravity, lights out, boss rush and more)
- Checkpoints inside each level, with retries
- Combos, near-miss bonuses and power-up orbs
- 7 weapons, armor, 6 heroes, rocket shoes, a battle tank and a battle mech
- Bosses with arena fights, minions and overpowered weapon drops
- Daily missions and a daily challenge (same levels for everyone on a given date), with a share button
- Progress is saved in your browser; there's a reset button on the title screen, and it can be undone once

Real-money gem packs are **not** connected: no payment is taken and no gems are added.

## For developers

The whole game is a single file, [`index.html`](index.html): no build step and no dependencies. Open it in a browser to run it.

Pushes to the deploy branch publish it to GitHub Pages through [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml).
