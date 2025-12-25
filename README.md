# eq_SEImgConverter (Space Engineers Image → Monospace)

SEImgConverter turns images into **monospace text strings** you can paste into **Space Engineers LCD panels** (Text & Images).  
It includes a live preview, crop box, dithering, multi-panel output (e.g. 1 panel, 3 panels, 3x2, etc.) and an update system.

> **Language note:** The app UI supports **English since v0.9.0** (German is still available).

---

## Where do I get the program?
Download the program [Here](https://github.com/Nerzors/seimgconverter/releases) :)

## Preview
[Youtube Video Preview #000](https://youtu.be/VIy1W16Ep-I)

<img src="https://app.eternal-quill.space/se/imgconv/update_0.12.0.png" width="640" />
<p float="left">
  <img src="https://app.eternal-quill.space/se/imgconv/update_0.12.0_1.png" width="320" />
  <img src="https://app.eternal-quill.space/se/imgconv/update_0.12.0_2.png" width="320" />
</p>
<p float="left">
  <img src="https://eternal-quill.space/se/imgconv/preview_1.png" width="180" />
  <img src="https://app.eternal-quill.space/se/imgconv/update_0.10.0_2.png" width="180" />
  <img src="https://app.eternal-quill.space/se/imgconv/update_0.11.0.png" width="180" />
</p>
---

## Features
- Library (Project Storage): Save conversions including settings, panel layout, and a thumbnail.
- Convert images to **monospace text** for Space Engineers LCDs
- **Panel presets** (foundation for multiple LCD block types & sizes)
- **178×178** default panel mapping (classic LCD/Text Panel style)
- **Multi-panel layouts** (Cols × Rows) to split one image across multiple LCDs
- **Dithering modes** (e.g. Floyd–Steinberg, Bayer, Atkinson, …)
- **Crop box** with mask + rule-of-thirds grid
- **Pan / Zoom** + optional **Live Preview**
- **Grid overlay** to visualize panel splits
- **Copy per panel** + **Export panels as .txt files**
- **Auto update check** (with update dialog + ignore option)

---

## How to use (in Space Engineers)

1. Load a Images per Button or Drag and Drop
2. Convert (choose layout, dithering, crop/zoom if needed).
3. Copy the output string for the panel you want.
4. In Space Engineers:
   - LCD → **Content:** `Text and Images`
   - **Font:** `Monospace`
   - Paste text
   - Set **Font Size** (commonly around `0.1` for Corner-LCD `0.4`, depending on your LCD size)

Tip: For best results, use **Crop + Zoom ~0.9–1.2** and a dithering mode.

---

## Updates

The app can check for updates on startup and will show a dialog if a newer version is available.  
(You can disable auto-update checks in the Settings.)

---
## Roadmap (planned)

- ~~Full **English UI**~~ ✔️ (since v0.9.0)
- ~~More dithering options / fine tuning~~ ✔️ (since v0.11.0)
- ~~Rotate / flip tools~~ (since v0.12.0)
- ~~Better preview tools (guides, positioning, zoom controls)~~ (since v0.12.0)
- ~~Verified presets for more LCD block types (Corner / Curved / Sci-Fi, etc.)~~ ✔️ (since v0.9.0)

---

## Credits

Developed by **Nerzors.DE**  
Project page: **Eternal-Quill**
