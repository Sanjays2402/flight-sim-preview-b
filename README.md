# Flight Sim — Visuals Preview

A single-file Three.js flight simulator with a focus on cinematic visuals: a dynamic day/night cycle with a sweeping sun arc and shifting sky gradient, procedural mountain terrain generated from inline simplex noise, distance fog that color-matches the horizon, a glittering lake, a small city of blocky towers, four scattered airstrips across a 24 km world, and a cheap-but-tasty lens flare when the sun is in view. Pitch, roll, yaw, throttle, brakes, reset, and a time-of-day toggle from the keyboard. No build step, no external assets, no dependencies beyond Three.js from a CDN.

## Controls

| Key | Action |
| --- | ------ |
| `W` / `S` | Throttle up / down |
| `↑` / `↓` | Pitch |
| `←` / `→` | Roll |
| `A` / `D` | Yaw (rudder) |
| `Space` | Brakes (on ground) |
| `T` | Step time of day forward |
| `P` | Freeze / resume the automatic day cycle |
| `R` | Reset to the KCEN runway |

The day cycle auto-advances slowly while you fly. Press `P` to hold the current light for golden-hour screenshots, then `P` again to resume.
