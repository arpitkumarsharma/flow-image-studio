# Flow Image Studio – Bulk Edition

A static, browser-based image utility for personal use.

## Features
- Upload up to 100 JPG, PNG, or WebP images at once.
- Preview selected images.
- Batch brightness/contrast adjustment, resizing, and format conversion.
- Download all processed images in one ZIP file.
- Prompt helper for requesting a newly generated replacement image from an image generator.
- Processing happens locally in your browser; the images are not uploaded by this page.

## Run locally
Open `index.html` in a modern browser. An internet connection is needed to load JSZip from its CDN for ZIP downloads.

## Deploy on GitHub Pages
1. Upload `index.html` and `README.md` to the repository root.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
4. Open `https://YOUR-USERNAME.github.io/flow-image-studio/`.

## Important limitation
This tool does not remove, hide, or alter Google Flow or other provenance watermarks. The prompt helper is for creating a new, original replacement image in a separate image-generation service; it does not guarantee identical reproduction. AI generation requires that separate service and is not performed by this static website.
