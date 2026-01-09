<p align="center">
  <img src="https://app.eternal-quill.space/se/imgconv/media/eternal-quill_seimgconverter_logo.sm.png" width="345" alt="SEImgConverter Logo" />
</p>

<h1 align="center">Eternal-Quill: SEImgConverter (Space Engineers Image → Monospace)</h1>

<p align="center" style="text-decoration: none;">
  <a href="https://github.com/Nerzors/seimgconverter/releases" style="text-decoration: none;">
    <img alt="version" src="https://img.shields.io/github/v/release/Nerzors/seimgconverter?display_name=tag&sort=semver&style=flat&label=version" />
  </a>
  <a href="https://github.com/Nerzors/seimgconverter/releases" style="text-decoration: none;">
    <img alt="downloads" src="https://img.shields.io/github/downloads/Nerzors/seimgconverter/total?style=flat&label=total%20downloads" />
  </a>
  <a href="https://github.com/Nerzors/seimgconverter/stargazers" style="text-decoration: none;">
    <img alt="stars" src="https://img.shields.io/github/stars/Nerzors/seimgconverter?style=flat&label=stars" />
  </a>
  <a href="https://github.com/Nerzors/seimgconverter/commits/main" style="text-decoration: none;">
    <img alt="last commit" src="https://img.shields.io/github/last-commit/Nerzors/seimgconverter?style=flat&label=last%20commit" />
  </a>
  <img alt="Tech" src="https://img.shields.io/badge/.NET-WPF-blueviolet" />
</p>

SEImgConverter converts images into **monospace text strings** you can paste into **Space Engineers LCD panels** (`Text and Images`).  
It includes a live preview, crop box, dithering, multi-panel output (e.g. 1 panel, 3 panels, 3x2, etc.) and an update system.

> **Languages:** English + German (since v0.9.0)

---

## Download
Get the latest release here: **https://github.com/Nerzors/seimgconverter/releases**

---

## Preview
YouTube: [Showcase - Preview #000](https://youtu.be/VIy1W16Ep-I) *before update v0.12.0*

<img src="https://app.eternal-quill.space/se/imgconv/update_0.13.0_1.png" width="720" />
<p float="left">
  <img src="https://app.eternal-quill.space/se/imgconv/update_0.12.0_1.png" width="360" />
  <img src="https://app.eternal-quill.space/se/imgconv/update_0.12.0_2.png" width="360" />
</p>
<p float="left">
  <img src="https://eternal-quill.space/se/imgconv/preview_1.png" width="220" />
  <img src="https://app.eternal-quill.space/se/imgconv/update_0.10.0_2.png" width="220" />
  <img src="https://app.eternal-quill.space/se/imgconv/update_0.11.0.png" width="220" />
</p>

---

## Features

### Core
- Convert images to **monospace text** for Space Engineers LCDs
- **Live Preview** with automatic re-convert on relevant setting changes
- **Multi-panel layouts** (Cols × Rows) to split an image across multiple LCDs
- **Panel presets** for different LCD block types & sizes (verified presets included)

### Editor Tools
- **Crop box** with optional mask + rule-of-thirds grid
- **Pan / Zoom**
- **Rotate / Flip** tools + transform state indicator
- **Grid overlay** to visualize panel splits

### Image / Render
- Multiple **dithering modes** (Floyd–Steinberg, Bayer, Atkinson, …)
- Render filters:
  - **Auto Levels**
  - **Contrast**
  - **Gamma**
  - **Blur / Sharpen**
- Right-click on sliders to **reset to default values**

### Workflow
- **Copy per panel** + export as `.txt`
- **Library**: save conversions including settings, layout, thumbnail + optional source
- **Undo / Redo** for editor changes + **History tab**
- Built-in **update checker** (disable in Settings)

---

## How to use (Space Engineers)

1. Load an image (button or drag & drop).
2. Pick a panel preset + layout (Cols/Rows).
3. Adjust crop/zoom, dithering and filters until it looks good.
4. Copy the panel output you need.
5. In Space Engineers:
   - LCD → **Content:** `Text and Images`
   - **Font:** `Monospace`
   - Paste text
   - Adjust **Font Size**  
     (common values: around `0.1` for many panels, `0.4` for some Corner LCDs — depends on block size)

**Tip:** For best results, use **Crop + Zoom ~0.9–1.2** and a dithering mode.

---

## Updates
The app can check for updates on startup and will show a dialog when a newer version is available.  
You can disable auto-checks in **Settings**.

---

## Roadmap
- ✅ English UI (since v0.9.0)
- ✅ Verified presets (since v0.9.0)
- ✅ More dithering modes (since v0.11.0)
- ✅ Rotate / Flip tools (since v0.12.0)
- ✅ [More __Render filters__: *Auto Levels*, *Contrast*, *Gamma*](https://github.com/Nerzors/seimgconverter/issues/11) (since v0.13.0)
- ✅ [**Dither Strength** for fine tuning (in progress)](https://github.com/Nerzors/seimgconverter/issues/12) (since v0.13.0) 
- ✅ [Undo / Redo + History tab (in progress)](https://github.com/Nerzors/seimgconverter/issues/13) (since v0.13.0)
- ✅ [Export Manager improvements (in progress)](https://github.com/Nerzors/seimgconverter/issues/14) (since v0.13.0)
- 🚧 [Fun / Special *__Style Presets__*: *Retro CRT*, *Blueprint*, *Comic*](https://github.com/Nerzors/seimgconverter/issues/15)
- 🌍 ~~[More languages (maybe?)](https://github.com/Nerzors/seimgconverter/issues/16)~~

---

## Credits
Developed by **Nerzors.DE**  
Project page: **Eternal-Quill**

---

License: Nerzors NC-NRD-ND v1.0 (see LICENSE)
