# Air Jordan 1 Pixel Collection

250 Air Jordan 1 colorways drawn as 8-bit pixel art by MAUS MAUS, shown on a 3D globe.

- Drag to spin, scroll or pinch to zoom, click a tile to open its card
- **UNFOLD** (or `U`) lays the globe out as the tier board: Ultimate, Legend, Epic, Collaboration, Rare, Special, Common
- Filter by tier from the bottom bar
- **VENDING** (or `V`) opens the Pixel Drop machine: MINT NOW pulls a random pair, weighted by tier (Common 55% · Special 20% · Rare 12% · Collab 7% · Epic 4% · Legend 1.7% · Ultimate 0.3%). Pulls are kept in your browser; the **MINE** filter shows the pairs you've got

Built with [three.js](https://threejs.org). Thumbnails and specs come from the NFT-0034 Figma board.

## Run locally

Open with any static server (textures don't load from `file://`):

```
python3 -m http.server 8000
```

then visit http://localhost:8000.

## Files

- `index.html` — the whole page
- `tiles/tiles-0.png`, `tiles/tiles-1.png` — texture sheets, 152 px thumbnails on a 160 px grid

Artwork © MAUS MAUS.
