# Flow Image Studio

A static, browser-based batch image utility for personal use. It supports up to 100 JPG/PNG/WebP files per batch, resizing, brightness/contrast adjustments, format conversion, and ZIP export.

## Run locally
Open `index.html` in a modern browser. ZIP export loads JSZip from cdnjs, so an internet connection is needed for that feature.

## Publish with GitHub Pages
1. Create a new public GitHub repository, for example `flow-image-studio`.
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main**, folder **/(root)**, then click **Save**.
6. Wait for GitHub Pages to publish; open the URL shown on the Pages settings screen.

Processing runs locally in the browser; image files are not sent to a server. The app does not remove or conceal Google Flow or other provenance watermarks.
