# Messenger · Baby

A tiny clone of [messenger.abeto.co](https://messenger.abeto.co/) — the abeto studio's
interactive 3D voxel-aesthetic landing page.

## Versions

| path | what it is |
|---|---|
| [`/`](./) | Landing page with links to both versions |
| [`/planet/`](./planet/) | **Latest.** Round earth planet + Q版 (chibi) courier characters |
| [`/flat/`](./flat/) | v1. Flat floating island + voxel decorations |

## Tech

- **Three.js 0.160** via ESM CDN
- **MeshLambertMaterial** (no IBL / no PBR, just simple lighting)
- **Single-file HTML** — no build step, no bundler
- **Vercel-ready** — pure static assets, zero config

## Original

- Live: https://messenger.abeto.co/
- Studio: [abeto](https://abeto.co) — "Crafted Interactive Experiences"
- Tech stack of original: Svelte 4 + Three.js (r0.160), Vite, Cloudflare
- No public source or technical docs (GitHub org is private/empty)

## How to run locally

```bash
cd planet   # or: flat
python3 -m http.server 8000
# open http://localhost:8000
```
