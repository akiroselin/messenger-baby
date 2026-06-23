# Messenger — Planet Baby (v2)

A round-earth chibi version of the [messenger.abeto.co](https://messenger.abeto.co/) reproduction.
Same single-file Three.js approach as v1, but with a spherical planet and Q版 (chibi) characters.

## Quick start

```bash
cd /Users/kirosealin/messenger-baby-planet
python3 -m http.server 8765
# open http://localhost:8765/index.html
```

## What's different from v1

| | v1 (flat island) | v2 (planet) |
|---|---|---|
| Base shape | Floating box island | Round spherical planet (radius 5) |
| Trees | Cone + cylinder (pointy pine) | Chunky trunk + 3 overlapping spheres (round) |
| House | Box + cone roof + door | Box + roof + round window + chimney |
| Characters | None | **Two chibi couriers** (big head, small body, red cap, package) |
| Decorations | Scattered rocks | Scattered rocks + clover-like grass tufts |
| Motion | Island bobs | Planet slowly rotates + couriers bob |
| Camera default | (0, 7, 18) | (0, 8, 22) — pulled back a bit for the sphere |

## The chibi courier

- Head sphere: radius 0.38 (≈1.5× body height — classic chibi 1:2 head-to-body)
- Body cylinder: 0.45 tall
- Red baseball cap (half-sphere + curved brim)
- Tiny black dot eyes + red smile
- Pants + shoes + arms with little skin-colored hands
- Carries a small yellow package with red ribbon

## Files

- `index.html` — the whole app
- `README.md` — this file

## See also

- v1 (flat island version): `/Users/kirosealin/messenger-baby/`
- Original: https://messenger.abeto.co/
