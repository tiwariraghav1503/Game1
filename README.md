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
| Pause (opens the Bosses tab, so you can fight a boss any time) | P | ⏸ button |
| Music / sound effects | M / N | 🎵 / 🔊 buttons |

## What's in it

- 12 wheel levels, each with its own music, plus wheel modifiers (double gems, low gravity, turbo, free tank, boss rush)
- A difficulty drop-down on the title screen: Peaceful, Easy, Hard or Impossible (faster, denser, fewer retries, tougher bosses, bigger rewards)
- Weapon upgrades: the shop's UPGRADES tab levels every weapon you own up to Lv5 (damage, speed, reach, blast, ammo, extra missiles, cheaper power cost). Upgrades are permanent and survive Restore
- Checkpoints inside each level, with retries
- Combos, near-miss bonuses and power-up orbs
- 7 weapons, armor, 10 heroes (including the four bosses as playable characters, up to 4,000 gems), rocket shoes, a battle tank and a battle mech
- Bosses with arena fights, minions and overpowered weapon drops. The shop's BOSSES tab lets you buy each boss weapon outright or fight any boss on purpose, at three difficulty tiers: from the title screen, between levels, or mid-level by pausing (P)
- Daily missions and a daily challenge (same levels for everyone on a given date), with a share button
- Progress is saved in your browser; there's a reset button on the title screen, and it can be undone once

Real-money gem packs are **not** connected: no payment is taken and no gems are added.

## For developers

The whole game is a single file, [`index.html`](index.html): no build step and no dependencies. Open it in a browser to run it.

Pushes to the deploy branch publish it to GitHub Pages through [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml).
