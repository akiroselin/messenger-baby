# Messenger — Baby Version

A minimal reproduction of the 3D voxel-aesthetic from [messenger.abeto.co](https://messenger.abeto.co/),
built as a single self-contained HTML file with Three.js (no build step).

## Quick start

```bash
cd /Users/kirosealin/messenger-baby
python3 -m http.server 8765
# open http://localhost:8765/index.html
```

## What you get

- Floating 3D island with grass top + rocky bottom
- 3×3 grid of voxel block letters spelling **MESSENGER**
- Decorations: 4 pine trees, a small red-roofed house, scattered rocks, drifting clouds
- Yellow **BEGIN** button → triggers a delivery-package drop animation from the sky
- Manual orbit camera (drag to rotate, scroll to zoom)
- Teal background matching the source aesthetic

## Tech (intentionally simple)

- **Three.js 0.160** via ESM CDN + importmap
- **MeshLambertMaterial** (reliable, no IBL needed)
- Pure HTML + ES modules — no Svelte / Vite / bundler
- ~500 lines, single file

## Original project research

- Live at https://messenger.abeto.co/
- Studio: [abeto](https://abeto.co) — "Crafted Interactive Experiences"
- Tech stack of original: Svelte 4 + Three.js (r0.160), Vite, Cloudflare CDN
- GitHub org: [github.com/abeto-co](https://github.com/abeto-co) — **no public repos**
- No public technical documentation or blog write-up

## Files

| file | purpose |
|---|---|
| `index.html` | the whole thing — open this in a browser |
| `README.md` | this file |
