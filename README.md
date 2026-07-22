# Scanline — QR Code Generator

A clean, browser-based QR code generator. Type a link or text, customize the colors, optionally drop in a logo, and download a ready-to-use QR code — all without leaving the page.

## Live Demo

*(Link will be added here once GitHub Pages is enabled.)*

## Features

- **Instant Generation** — Paste any text or URL and generate a QR code immediately.
- **Custom Colors** — Choose both the QR code color and background color.
- **Logo Embedding** — Optionally overlay a logo in the center of the QR code, automatically padded for scannability.
- **One-Click Download** — Export the result as a PNG.
- **Fully Client-Side** — No backend, no server, no data ever leaves the browser.

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | Custom CSS (no framework) |
| Logic | Vanilla JavaScript |
| QR Generation | [qrcodejs](https://github.com/davidshimjs/qrcodejs) |
| Fonts | JetBrains Mono, Inter |

## How It Works

The QR code is generated entirely in the browser using the `qrcodejs` library, then redrawn onto an HTML canvas so custom colors and an optional logo overlay can be applied. The final image is exported directly from the canvas as a downloadable PNG — no server round-trip involved.

## Running Locally

This is a single static HTML file with no build step or dependencies to install.

1. Clone the repository:
   ```bash
   git clone https://github.com/nayab-gull-it/qr-code-generator.git
   ```
2. Open `index.html` directly in any browser.

That's it — no server required.

## Author

Built by Nayab Gull.
