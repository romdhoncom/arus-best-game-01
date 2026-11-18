# Arus

Arus is an original 2D arcade game: steer a paper boat down a procedurally generated river at dusk, collect fireflies for score, dodge rocks, survive as the river speeds up. 3 lives, levels, pause/restart, menu and game-over screens, local best score.

## Files
- game/index.html — entry page, canvas, status line.
- game/src/main.js — boot, fixed-step loop, screens (title/play/paused/game over), shot staging.
- game/src/world.js — rules and state: boat, falling rocks and fireflies, spawning, collisions, score, lives, level.
- game/src/config.js — tuning numbers and dusk-river palette.
- game/src/render.js — drawing only: river field, boat, rocks, fireflies, HUD and panels.
- game/src/input.js — keyboard and pointer input.
- game/src/random.js — seeded random (mulberry32), same seed gives the same game.
- game/src/shots.js — screenshot scenes: start, play and end, staged by a simple autopilot.
