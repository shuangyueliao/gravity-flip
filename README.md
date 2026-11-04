# Gravity Flip

One-button neon gravity runner. Tap / click / Space to flip gravity between the
floor and the ceiling — dodge spikes and floating blocks, pass laser gates only
in the gravity state their arrow marks (↓ floor / ↑ ceiling), and grab gears
placed in precise-flip spots.

**Play:** https://shuangyueliao.github.io/gravity-flip/

## Modes

- **Endless Run** — procedurally streamed obstacles (deterministic per run),
  speed ramps up, checkpoint every 500m, 3 lives, best gear score saved.
- **Level Mode** — 12 handcrafted levels of rising speed and density; clearing
  a level unlocks the next. Furthest progress is saved.

## Features

- Gravity-flip physics with preserved momentum and surface-snap landing
- Laser gates that only pass the marked gravity state
- Neon dual-tone visuals: blue for normal gravity, orange for flipped
- Flip screen-tilt effect, particle trail, run-cycle animation
- All graphics drawn on canvas, all sound synthesized with WebAudio —
  zero external assets, single HTML file, works offline once loaded
- Touch + mouse + keyboard input, responsive canvas (landscape-friendly)
- Mute toggle, best score / level progress in localStorage
- Portal SDKs load only on matching domains (CrazyGames / GameDistribution)

## Tech

Vanilla JavaScript, Canvas 2D, WebAudio. No frameworks, no build step,
no tracking. `index.html` is the whole game (~42 KB).
