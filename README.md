# Jalico 3D Furniture Models

Interactive 3D product viewers for Jalico custom furniture, built with Three.js.
Each page runs in the browser with no build step: rotate, zoom, open doors and drawers,
switch finishes (natural birch / dark walnut) and check sizes.

<!-- Add a GIF or screenshot here -->

## Models

| File | Product |
|---|---|
| `models/nightstand.html` | Nightstand |
| `models/cat-litter-cabinet.html` | Cat litter cabinet |
| `models/shoe-bench.html` | Shoe bench |
| `models/entryway-cabinet.html` | Double-sided entryway cabinet |
| `models/wardrobe.html` | Three-door wardrobe |
| `models/vanity-desk.html` | Vanity desk with drawer |
| `models/pet-cabinet.html` | Pet cabinet |
| `models/house.html` | Three-bedroom house |
| `models/oak-nightstand.html` | Oak nightstand |
| `models/oak-storage-bench.html` | Oak storage bench |
| `models/cat-litter-cabinet-zh.html` | 貓砂櫃（中文版） |
| `models/wardrobe-zh.html` | 三門衣櫃（中文版） |

## Contact

The WhatsApp number in the inquiry forms is replaced with `+1 XXX XXX XXXX`.

## Run locally

Open any file in `models/` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Live demo

Enable GitHub Pages (Settings > Pages > Deploy from branch `main`), then visit
`https://<your-username>.github.io/<repo-name>/models/nightstand.html`.

## Tech

- Three.js 0.160 (ES modules from jsDelivr)
- Procedural wood-grain textures
- GLB export for AR ("View in your room")
