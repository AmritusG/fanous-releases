# Changelog

## 1.1.1 — 2026-10-11

- Fanous FX: no hitch the first time a clip use is switched on (every shader it needs is prepared when the effect loads).
- Fanous FX, Pattern ▸ Input: the smoke, the lightning that crawls over the lantern and the fireflies now follow the
  video's holes. Before, they saw a stand-in pattern: smoke left a lantern even where the clip made it solid.
- The release zip is checked to hold both builds, Fanous and Fanous FX.
- Your saved clips are unchanged: no parameter was added, renamed or changed.

## 1.1.0 — 2026-10-11

- **New: Fanous FX**, an effect version of Fanous that uses the clip it sits on (group **Input**): the clip as the
  lantern's stained glass (Window / Mosaic / Per Face) and so in the light it throws; as the light's own picture
  (Sphere / Cube / Front); on the room's surfaces; as the pattern that pierces the plates (Pattern ▸ Input); coloured
  into the smoke; and as the background. Each has its own amount, so they combine.
- A playing clip never rebuilds the lantern's light, except with Pattern ▸ Input, which follows the clip by design.
- Smoother Hankin star patterns while you turn **Truncate** on symmetric solids such as the Cube.
- Your saved Fanous clips are unchanged: every existing parameter keeps its name, range and default.

## 1.0.0 — 2026-10-11

First release.

- A pierced lantern: 27 polyhedra (morph, truncate, bevel, spike) or your own model (.glb / .gltf / .fbx / .obj),
  cut by 27 patterns, with optional coloured glass.
- One or two lights, placed inside, outside or anywhere, or used as a sun. They throw the pattern onto the floor, walls,
  ceiling and the lantern's own plates, with a penumbra that follows the bulb size, and as beams through haze and smoke.
- A camera that can stand inside the lantern; a room in plaster, concrete, zellige or wood; Light Only mode for
  layering.
- Motion, beat and audio reactivity, camera poses and cuts, smoke, fire, lightning, fireflies, bloom.
- Universal (Apple Silicon + Intel), macOS 11 or later, Resolume Arena / Avenue 7 or later.
