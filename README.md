# grain

A small standalone tool that turns any image into dithered pixels, ASCII or
braille. Drop in an image, pick a mode, and export. Everything runs in the
browser — nothing is uploaded.

## run it

No build step, nothing to install.

1. **Just open the file** — clone or download the repo, then open `index.html`
   in any browser.
2. **Or serve the folder** — if you'd rather use a local server:

   ```bash
   git clone https://github.com/7orde/grain.git
   cd grain
   python -m http.server
   ```

   then open the printed URL (usually http://localhost:8000).

## use it

Drop in an image (or paste, or click **sample**), pick a mode, and adjust the
sliders to taste.

Modes: `floyd–steinberg`, `atkinson`, `bayer` (dithering) and `ascii`, `braille`
(text).

Shortcuts: `1–5` switch modes, `i` inverts, hold `o` to see the original, scroll
to zoom, drag to pan. Export a PNG at 2×/4×/8×, or copy the text.

Nothing leaves your browser — there's no server and no upload.
