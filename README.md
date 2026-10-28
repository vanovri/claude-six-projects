# Claude Six: Interactive Web Simulations and Creative Tools

These are AI-assisted educational browser visualizations and interaction demos. The handwriting studio uses predefined vector glyphs and exports SVG font markup. It does not OCR or train a font from uploaded notes. Wildfire and medical scenes are illustrative models, without calibrated forecasting or clinical validation. Syntax checks do not establish cross-browser compatibility or scientific accuracy.

[![Live Portfolio Page](https://img.shields.io/badge/Portfolio-ardhyanovri.my.id-0f172a?style=flat-square&logo=vercel)](https://ardhyanovri.my.id/projects/claude-six-projects.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-10b981?style=flat-square)](https://opensource.org/licenses/MIT)
[![Zero Dependencies](https://img.shields.io/badge/Runtime-Zero%20Build%20Step%20HTML5%20%2F%20WebGL-f97316?style=flat-square)](#architecture--directory-structure)

Six independent HTML5, WebGL, Canvas and SVG demos inspired by a public showcase. They run in a browser without a build step.

---

## Included Applications

| # | Application | Path | Domain | Highlights |
| :- | :--- | :--- | :--- | :--- |
| **00** | **Master Showcase Hub** | [`index.html`](./index.html) | Multi-App Launcher | Bento overview grid + instant embedded iframe workspace switcher across all 6 apps. |
| **01** | **FireTrace — 3D Wildfire Spread Simulator** | [`projects/01-firetrace/index.html`](./projects/01-firetrace/index.html) | Geospatial & Wildfire Forensics | 3D procedural San Gabriel Mountains terrain (`34.228°N, 118.144°W`), hourly perimeter timeline (`06:00`–`22:00`), wind arrow particles, smoke plumes, VLAT Phos-Chek retardant drops, spot-fire ignition, and 3 synchronized telemetry canvases (Fireline Intensity & Spread, Wind & Gusts, Fuel Moisture & RH). |
| **02** | **Doodle Chess — Notebook Paper Chess** | [`projects/02-doodle-chess/index.html`](./projects/02-doodle-chess/index.html) | Game AI & Sketch UI | Lined notebook paper aesthetic with margin line & binder holes, hand-drawn doodle SVG pieces (*Queen Bee*, *Star Blob Rook*, *Doodle Llama Knight*, *Acorn Bishop*, *Crowned King*, *Spotted Toadstool Pawn*), red crayon selection rings & move indicators, chess move handling (castling, en passant, promotion), algebraic log, and Minimax Alpha-Beta AI. |
| **03** | **Notes → Font (`Harshpreet Hand`)** | [`projects/03-handwriting-font/index.html`](./projects/03-handwriting-font/index.html) | Typography & Vector Pipeline | Interactive preset-glyph studio with a synthetic 120-page grid, staged ink and stroke illustrations, toggleable glyph variations, a live specimen and SVG font markup export. It does not process uploaded notebooks or perform OCR. |
| **04** | **Induction Bench — 3D Magnetic Field Lab** | [`projects/04-magnetic-field/index.html`](./projects/04-magnetic-field/index.html) | Electromagnetism & Physics | Real-time 3D magnetic dipole field lines ($\vec{B}(\vec{r}) = \frac{\mu_0}{4\pi}\left(\frac{3(\vec{m}\cdot\hat{r})\hat{r}}{r^5} - \frac{\vec{m}}{r^3}\right)$), draggable 3D bar magnet + multi-turn solenoid, 4 magnet alloys (`NdFeB N52`, `NdFeB N42`, `SmCo28`, `Ferrite C8`), 4 wire metals (`Cu`, `Ag`, `Al`, `NiCr`), analog zero-center galvanometer needle, dual-trace CRT oscilloscope ($\mathcal{E}(t)$ & $I(t)$), and live Flux Linkage $\Lambda(x)$ curve. |
| **05** | **AngioView — 3D Heart & Fluoroscopy Trainer** | [`projects/05-angioview/index.html`](./projects/05-angioview/index.html) | Medical Imaging & Cardiology | Synchronized dual-viewport trainer pairing a 3D anatomical heart & color-coded coronary tree (`RCA`, `PDA`, `LMCA`, `LAD`, `D1`, `D2`, `S1`, `LCx`, `OM1`) with a real-time simulated X-ray fluoroscopy projection, `LAO/RAO` + `CRA/CAU` sliders, 2D angle pad, 3D C-arm gantry schematic, 6 standard clinical views (*Spider*, *RAO Caudal*, *LAO Cranial*, etc.), contrast dye injection, and LAD stenosis callout. |
| **06** | **20 Coded Poems — Animated Haiku Anthology** | [`projects/06-coded-poems/index.html`](./projects/06-coded-poems/index.html) | Generative Art & Poetry | Anthology of 20 haikus paired with charcoal-sketch procedural HTML5 Canvas animations, opening with the exact 3 poems from the showcase (*Espalier Pear Blossom*, *Dew on a Silk Thread*, *Autumn Ink Feathering*) plus 17 nature haikus, keyboard navigation (`←`/`→`), autoplay mode, and interactive pointer physics. |

---

## Architecture & Directory Structure

```text
claude-six-projects/
├── index.html                           # Master Showcase Hub & Iframe Switcher
├── README.md                            # Documentation & Technical Reference
└── projects/
    ├── 01-firetrace/
    │   └── index.html                   # 3D Wildfire Forensic Spread Simulator
    ├── 02-doodle-chess/
    │   └── index.html                   # Hand-Drawn Notebook Paper Chess + Minimax AI
    ├── 03-handwriting-font/
    │   └── index.html                   # Preset-glyph SVG Font Studio
    ├── 04-magnetic-field/
    │   └── index.html                   # 3D Magnetic Dipole Field & Faraday Induction Lab
    ├── 05-angioview/
    │   └── index.html                   # 3D Coronary Anatomy & X-Ray Fluoroscopy Trainer
    └── 06-coded-poems/
        └── index.html                   # 20 Haiku Poems with Procedural Canvas Animations
```

---

## Quick Start

No build step or package installation is required.

```bash
# Clone the repository
git clone https://github.com/vanovri/claude-six-projects.git
cd claude-six-projects

# Serve locally with Python or Node, or open index.html directly in any modern browser
python -m http.server 8080
```

Then visit `http://localhost:8080` to explore the Master Hub or open any of the six standalone applications under `projects/`.

---

## Author

**Ardhya Novri Ramadhan (`vanovri`)**
- Portfolio: [ardhyanovri.my.id](https://ardhyanovri.my.id)
- GitHub: [@vanovri](https://github.com/vanovri)
- LinkedIn: [linkedin.com/in/dhya](https://www.linkedin.com/in/dhya/)
