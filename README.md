# Pixel Art Studio

### Browser-Based Pixel Art Creation Tool

A lightweight, zero-dependency pixel art editor that runs entirely in the browser. Upload any image and transform it into retro 8-bit pixel art, or create original pixel sprites from scratch -- no installs, no accounts, no backend required.

---

## Why This Exists

Most pixel art tools are either heavyweight desktop applications or SaaS products that require sign-ups and subscriptions. This project takes the opposite approach: open a single HTML file in any modern browser and start creating immediately.

The editor is designed for speed and simplicity. It handles the two core workflows every pixel artist needs -- converting existing images into pixel art, and drawing original sprites -- without the overhead of a full application framework.

---

## Architecture

```
pixel-art-studio/
  8bit.html       -- 8-bit pixel art converter (image-to-pixel-art transformation)
  page.jsx        -- Pixel editor component (original sprite creation)
```

The project is intentionally minimal. Each tool is self-contained with all logic, styling, and rendering handled inline.

---

## Features

**8-Bit Converter** (`8bit.html`)
- Upload any image and convert it to retro pixel art
- Adjustable pixel resolution and color palette depth
- CRT scanline overlay effect for authentic retro feel
- Canvas-based rendering with `image-rendering: pixelated` for crisp edges
- Code preview output for generated pixel data
- Custom scrollbar styling and retro monospace typography

**Pixel Editor** (`page.jsx`)
- Freehand drawing canvas for original sprite creation
- Grid-based pixel placement
- Color selection and palette tools

---

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Rendering | HTML5 Canvas API |
| Styling | Tailwind CSS (CDN) |
| Logic | Vanilla JavaScript |
| Dependencies | None |

---

## Quick Start

```bash
# No build step required. Open directly in a browser:
open 8bit.html
```

That is the entire setup.

---

## Author

**Huang Akai (Kai)**
Founder @ Universal FAW Labs | Creative Technologist | Ex-Ogilvy | 15+ years experience
