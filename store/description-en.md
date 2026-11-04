# Gravity Flip — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Run, flip gravity, survive. Tap to flip between floor and ceiling: dodge neon
spikes and blocks, pass laser gates in the marked gravity, grab gears.
Endless mode plus 12 handcrafted levels.

(189 characters — verified ≤ 200)

## Details

- Genre: Arcade / Runner / Skill
- Controls: One button — tap / click / Space to flip gravity. M toggles sound.
- Modes: Endless run (speed ramps up, checkpoints every 500m, 3 lives) and
  12 handcrafted levels with unlock progression.
- Mechanics: momentum-preserving gravity flip, surface-snap landing,
  laser gates that only pass the gravity state shown by their ↓/↑ arrow,
  gears (+1 score) placed in precise-flip positions.
- Features: best score & furthest level saved locally, mute toggle,
  neon blue/orange theme that switches with gravity state, particle trail,
  flip screen-tilt effect, responsive canvas (landscape-friendly).
- Tech: single-file HTML5, procedural canvas graphics, WebAudio synthesized
  sound (flip whoosh / gear chime / death / checkpoint). No external assets,
  no frameworks, no tracking. Works offline once loaded.

## Tags

runner, arcade, gravity, reflex, one-button, neon, endless, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop wired (+happytime)
- [x] Responsive canvas, landscape-friendly, touch + keyboard input
- [x] No external links inside gameplay, no analytics
- [ ] Cover art 16:9 and screenshots (add before submitting)

## GameDistribution
- Upload `gravity-flip-gd.zip` (contains index.html only).
- GD SDK auto-detects loading/playing on gamedistribution / gd.games domains.

## itch.io
- Upload `gravity-flip-itch.zip`, mark "This file will be playable in browser",
  entry file: index.html, kind: html, viewport: full frame (auto-detected).
- Pricing: $0 (donations optional).
