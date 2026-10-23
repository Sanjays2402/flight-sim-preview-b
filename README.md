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

## Terms & Disclaimer

By using this project you agree to the following.

- **No warranty.** This software is provided "as is", without warranty of any kind, express or implied, including merchantability, fitness for a particular purpose, and non-infringement.
- **No liability.** To the maximum extent permitted by law, the author and contributors are not liable for any claim, loss, or damage (direct, indirect, incidental, or consequential, including lost data or profits) arising from its use.
- **Your responsibility.** You use it at your own risk and are responsible for complying with the laws that apply to you.
- **Entertainment only.** This simulator is not flight training and is not approved by any aviation authority (FAA, Transport Canada, or DGCA).
- **Third parties.** Names, logos, APIs, and services of others belong to their owners and are used for identification only; no affiliation or endorsement is implied.
- **Your statutory rights.** Nothing here limits rights that cannot be waived by agreement, including under consumer-protection laws in the USA, Canada (including Quebec), and India (Consumer Protection Act, 2019).
- **License.** Use, copying, and distribution are governed by the [LICENSE](LICENSE) file; if anything here conflicts with it, the license controls.
