# EAN‑13 Barcode Generator (Static Web App)

A zero‑dependency, client‑side EAN‑13 generator that exports high‑resolution PNG or print‑ready SVG.

## Deploy (pick one)

### GitHub Pages
1. Create a new repo and add the files in this folder.
2. Push to `main`. In repo settings → Pages → Source: **Deploy from a branch**, branch **main**, folder **/** (root).
3. Your app will be live at `https://<your-username>.github.io/<repo>/`.

### Netlify
Drag & drop the folder onto https://app.netlify.com/drop or connect the repo. Build command: _none_. Publish directory: root.

### Vercel
`vercel deploy` with project root pointing to this folder. Framework preset: **Other**.

## Use
- Enter 12 digits (auto‑computes check digit) or 13 digits (validates).
- Adjust module width (resolution), bar height, quiet zone, and text size.
- Export PNG or SVG.

## Notes
- Minimum quiet zone is 11 modules each side for EAN‑13.
- Prefer SVG for print workflows.
- Everything runs locally in the browser; no data leaves the device.
