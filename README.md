# Efficiency Signal · Booth Demos

Self-contained display assets built for the Efficiency Signal conference booth. Every demo is a single HTML file — no build step, no server, no network calls. Open a file in a browser (or use the live links below) and it runs.

**Live index:** https://cramalamb.github.io/es-booth-demos/

## The demos

| Demo | File | What it does |
|------|------|--------------|
| [Booth Counter](https://cramalamb.github.io/es-booth-demos/attract.html) | `attract.html` | Split-screen attract loop: a rolling dollar odometer of heat-rate losses beside a live drift-detection chart. Press **Enter** to type in a visitor's own numbers for a personalized "your unit" view; press **S** for settings. Config lives in `localStorage` / URL params — nothing a visitor enters is persisted. |
| [Booth Loop](https://cramalamb.github.io/es-booth-demos/monitor-loop.html) | `monitor-loop.html` | Six-scene, ~64-second presentation loop alternating dark control-room scenes with cream print-style panels, with a persistent contact + QR strip. Copy is editable directly in the HTML; per-scene timing via `data-dur` attributes. |
| [Platform Demo](https://cramalamb.github.io/es-booth-demos/demo-black.html) | `demo-black.html` | Self-driving walkthrough of the eSentinel™ digitized-manual workflow — sign-in, spec resolution, performance report — framed on black with the booth contact strip. Embeds `demo-inner.html`, which also runs standalone. |

## Running locally

Clone (or download) and double-click any HTML file. `demo-black.html` expects `demo-inner.html` beside it; everything else is fully standalone. Fonts and graphics are embedded as data URIs.

## Display notes

- Built for a 27″ QD-OLED at 16:9 in a dim booth environment — dark scenes render true black.
- The attract counter and loop are meant to run unattended; the platform demo loops on its own script.

## Data disclaimer

All equipment references are generic or fictional ("Demo Unit 1", "a 1974 Westinghouse surface condenser"). No plant names, unit designations, serial numbers, or drawing numbers appear in any asset.

---

© Efficiency Signal. Shared for demonstration purposes; all rights reserved.
