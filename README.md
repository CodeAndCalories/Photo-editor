[README.md](https://github.com/user-attachments/files/25463697/README.md)
# ✦ LUMIX — Social Photo Editor

> A free, browser-based photo editor built for Instagram, TikTok, and social content creators.  
> No app. No account. No AI fluff. Just real editing tools that run entirely in your browser.

![LUMIX Editor](https://img.shields.io/badge/built%20with-HTML%20%2B%20Canvas-ff3c6e?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-00e5c5?style=flat-square)
![Zero dependencies](https://img.shields.io/badge/dependencies-zero-ffb830?style=flat-square)
![GitHub Pages ready](https://img.shields.io/badge/GitHub%20Pages-ready-blueviolet?style=flat-square)

---

## 🔥 Live Demo

👉 **[Try it now →](https://CodeAndCalories.github.io/lumix-editor)**

---

## What It Does

LUMIX is a single-file HTML photo editor designed specifically for social media formats. Upload a photo, apply presets and adjustments, add text or stickers, and export — all without leaving your browser.

No backend. No uploads to any server. Your photos never leave your device.

---

## Features

### 🎨 Editing Tools
- **14 real-time adjustments** — brightness, contrast, saturation, vibrance, temperature, tint, highlights, shadows, exposure, hue, clarity, grain, vignette, fade
- **8 one-click presets** — NOIR, CHROME, GOLDEN, FILM, MATTE, ARCTIC, EMBER, VELVET
- **Live RGB histogram** — see exactly what you're doing to your image
- **Before/after compare** — hold spacebar to instantly compare original vs edited

### 📐 Social Formats
| Format | Ratio | Best For |
|--------|-------|----------|
| Square | 1:1 | Instagram feed |
| Portrait | 4:5 | Instagram feed (tall) |
| Story | 9:16 | Instagram / TikTok stories |
| Landscape | 16:9 | YouTube thumbnails / Twitter |
| Cinematic | 2.39:1 | Cinematic look |
| Original | — | Keep native dimensions |

### ✍️ Text & Stickers
- Add custom text overlays with font, size, color, and position controls
- 16 free stickers / emoji overlays placed directly on your photo
- Full X/Y positioning

### 🖼️ Frames
- Thin border, thick white border, drop shadow frame
- More coming in PRO

### 💾 Export
- One-click JPG export at 95% quality
- Free exports include a small watermark (removable with PRO)

---

## Getting Started

LUMIX is a single HTML file — no build step, no dependencies, no server needed.

```bash
# Clone the repo
git clone https://github.com/CodeAndCalories/lumix-editor.git

# Open in your browser
open lumix-editor.html
```

Or just [download the HTML file](lumix-editor.html) directly and open it locally.

---

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to your `main` branch, root folder
4. Your editor is live at `https://yourusername.github.io/lumix-editor`

That's it. One file. Zero config.

---

## Monetization Model

LUMIX is built with a freemium model in mind:

| Feature | Free | PRO |
|---------|------|-----|
| All 14 adjustments | ✅ | ✅ |
| 4 presets | ✅ | ✅ |
| 50+ presets | ❌ | ✅ |
| All frames | ❌ | ✅ |
| 200+ stickers | ❌ | ✅ |
| No watermark on export | ❌ | ✅ |
| 4K export | ❌ | ✅ |
| Batch editing | ❌ | ✅ |

**Revenue streams:**
- 💳 PRO subscriptions ($4.99/mo or $29.99/yr) via the built-in upgrade modal
- 📢 Ad banner slots in the sidebar (swap in Google AdSense or any ad network)

---

## Tech Stack

- **Pure HTML + CSS + JavaScript** — zero frameworks, zero dependencies
- **Canvas API** — all pixel manipulation runs client-side in real time
- **Google Fonts** — Bebas Neue, DM Sans, Space Mono

The entire editor is a single `.html` file.

---

## Roadmap

- [ ] PRO payment integration (Stripe / Lemon Squeezy)
- [ ] Google AdSense ad slots
- [ ] Crop & rotate tools
- [ ] More presets and LUT support
- [ ] Batch export (multiple photos at once)
- [ ] Mobile touch support improvements
- [ ] PWA / installable app

---

## Contributing

Pull requests are welcome. For major changes, open an issue first.

```bash
git checkout -b feature/your-idea
git commit -m "Add: your idea"
git push origin feature/your-idea
```

---

## License

MIT — free to use, modify, and deploy. Attribution appreciated but not required.

---

<div align="center">
  <sub>Made with ☕ by <a href="https://github.com/CodeAndCalories">CodeAndCalories</a></sub>
</div>
