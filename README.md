# Pixel Art Studio

### Browser-Based Pixel Art Creation Tool

A lightweight, zero-dependency pixel art editor that runs entirely in the browser. Upload any image and transform it into retro 8-bit pixel art, or create original pixel sprites from scratch -- no installs, no accounts, no backend required.

## About

Pixel Art Studio 是一款零依賴的瀏覽器像素藝術工具，提供圖片像素化轉換與像素編輯器兩種創作模式。適合用於快速產出 8-bit/像素風素材、製作精靈圖（sprite），或作為前端 Canvas 圖像處理的示範專案。

## 📋 Quick Summary

> 🎨 **零依賴、純瀏覽器運行的像素藝術創作工具！** 本專案提供兩大核心功能：🖼️ **8-Bit 轉換器** 可將任何照片即時轉換為復古像素風格圖像，支援調整像素解析度與色彩深度，並內建 CRT 掃描線效果營造懷舊氛圍；✏️ **像素編輯器** 提供自由繪製畫布，搭配網格定位與調色盤工具，讓你從零開始創作精美的像素精靈圖（Sprite）。⚡ 技術上完全使用 HTML5 Canvas API 與原生 JavaScript 實現，搭配 Tailwind CSS CDN 進行樣式處理，**無需任何建置步驟**——直接開啟 HTML 檔案即可使用。🎮 採用 `image-rendering: pixelated` 確保像素邊緣銳利清晰，自訂捲軸樣式與復古等寬字體完善整體視覺體驗。💡 特別適合遊戲開發者製作 Sprite 素材、設計師探索像素風格、或任何想要快速將照片轉為復古風格的創作者。整個專案僅兩個檔案，極致輕量，開箱即用！

---

## 🤔 Why This Exists

Most pixel art tools are either heavyweight desktop applications or SaaS products that require sign-ups and subscriptions. This project takes the opposite approach: open a single HTML file in any modern browser and start creating immediately.

The editor is designed for speed and simplicity. It handles the two core workflows every pixel artist needs -- converting existing images into pixel art, and drawing original sprites -- without the overhead of a full application framework.

---

## 🏗️ Architecture

```
pixel-art-studio/
  8bit.html       -- 8-bit pixel art converter (image-to-pixel-art transformation)
  page.jsx        -- Pixel editor component (original sprite creation)
```

The project is intentionally minimal. Each tool is self-contained with all logic, styling, and rendering handled inline.

---

## 🚀 Features

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

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| Rendering | HTML5 Canvas API |
| Styling | Tailwind CSS (CDN) |
| Logic | Vanilla JavaScript |
| Dependencies | None |

---

## 🏁 Quick Start

```bash
# No build step required. Open directly in a browser:
open 8bit.html
```

That is the entire setup.

---

## 👤 Author

**Huang Akai (Kai)**
Founder @ Universal FAW Labs | Creative Technologist | Ex-Ogilvy | 15+ years experience
