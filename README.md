# PixelCraft Studio

PixelCraft Studio is a browser-based image editor built as a single static HTML file.

## Features

- Drag-and-drop image upload
- Crop using exact pixel inputs or direct canvas selection
- Resize with aspect-ratio lock and presets
- Quality adjustment with estimated export size
- AI-powered person/background separation using MediaPipe Selfie Segmentation
- Background colour replacement for passport and ID photos
- Canvas extension with static colours
- Export to PNG, JPEG/JPG, WEBP, and PDF
- HEIF/HEIC input support where the browser can decode it, with graceful export fallback
- Light and dark mode
- Undo and reset support

## Tech stack

- Vanilla JavaScript
- HTML5 Canvas API
- MediaPipe Selfie Segmentation via CDN
- jsPDF via CDN

## Run locally

Open `pixelcraft-studio.html` in a browser.

## Licence

Licensed under the GNU Affero General Public License v3.0.