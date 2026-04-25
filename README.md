# 🎵 Web Metronome

A full-featured, zero-dependency metronome web app in a single HTML file. Built on the Web Audio API (WAA) for sample-accurate timing. Open `metronome.html` in any modern browser — no build step required.

---

## Features

| Category | Details |
|---|---|
| **Audio engine** | WAA look-ahead scheduler for jitter-free clicks |
| **Visual beat indicator** | Animated dots highlight the current beat in real time |
| **BPM control** | Slider + numeric input, range 20–300 BPM |
| **Time signature** | Beats per measure (2–12) and beat value (4 or 8) |
| **Subdivisions** | None, 8ths, Triplets, 16ths |
| **Accent** | Toggle accent on beat 1 |
| **Tap Tempo** | Tap a button (or press **T**) to detect BPM |
| **Tap-to-Set Time Sig** | Tap beats for one measure; count is auto-detected |
| **Tap-Train Recorder** | Record a rhythm of taps, play it back, export as JSON |
| **Presets** | Save / Load / Delete — persisted in `localStorage` |
| **Export / Import Presets** | Share presets as `.json` files |
| **Keyboard shortcuts** | Full keyboard control (see table below) |
| **Responsive UI** | Dark-themed, mobile-friendly layout |

---

## Quick Start — Run Locally

```bash
# 1. Clone
git clone https://github.com/Apex-Quant-PhD/web-metronome.git
cd web-metronome

# 2. Open directly
#    Double-click metronome.html  — or use a local server:
npx serve .
# or
python -m http.server 8000
```

Then visit `http://localhost:8000/metronome.html` (if using a server) or just open the file.

> **No dependencies, no install, no build.** The entire app lives in one HTML file.

---

## Enable GitHub Pages

1. Go to **Settings > Pages** in your repository.
2. Under **Source**, choose **Deploy from a branch**.
3. Select the `main` branch and `/ (root)` folder. Click **Save**.
4. After ~60 seconds your metronome is live at:

```
https://Apex-Quant-PhD.github.io/web-metronome/metronome.html
```

---

## Keyboard Shortcuts

| Key | Action |
|---|---|
| `Space` | Play / Stop (or add a tap while recording) |
| Up / Down | BPM +/- 1 |
| Shift+Up / Shift+Down | BPM +/- 10 |
| `T` | Tap tempo |
| `G` | Tap time signature |
| `R` | Toggle tap-train recorder |
| `A` | Toggle accent on beat 1 |

> Shortcuts are disabled while a text input is focused so they don't interfere with typing preset names.

---

## Project Structure

```
web-metronome/
  metronome.html      # The app (HTML + CSS + JS, single file)
  README.md
  LICENSE             # MIT
  CONTRIBUTING.md
  CHANGELOG.md
  .gitignore
  icons/
    icon.svg          # Vector icon
    favicon.png       # 32x32 PNG favicon
    icon-512.png      # 512x512 PNG app icon
```

---

## License

[MIT](LICENSE)
