# ☕ Cozy Desk & Cyber Terminal Suite

A curated collection of vibe-coded experiments: a cozy coffee shop desk utility designed for deep work, paired with a retro CRT cyberpunk terminal simulator. Zero external assets, zero audio file dependencies, 100% self-contained.

---

## 🗂️ Included Projects

| Project | File(s) | Description |
|---|---|---|
| **Cozy Corner Desk** | `cozy_desk.html` | Pomodoro timer disguised as a steaming coffee mug, generative Web Audio ambient soundboard, dynamic mood palettes, and a persistent focus journal. |
| **NEO-SHADOW OS (Web)** | `index.html` | Browser-based retro CRT terminal with scanlines, synthesized audio effects, mini-games, and mainframe breach sequences. |
| **GEBOTERM (CLI)** | `cyber_terminal.py` | Python command-line retro terminal with typewriter streaming, animated packet streams, and interactive memory-locking games via `rich`. |

---

## ☕ 1. Cozy Corner Desk (`cozy_desk.html`)

An aesthetic focus dashboard built to transform your browser into a rainy coffee shop corner.

### Key Features
- **Steaming Mug Pomodoro**: Click the ceramic mug to control the session. Coffee level smoothly drops as focus time passes and refills on breaks. CSS physics power the animated rising steam.
- **Modes**:
  - `Deep Focus`: 25 minutes
  - `Short Sip`: 5 minutes
  - `Rest & Refill`: 15 minutes
- **Procedural Soundboard (Web Audio API)**:
  - 🌧️ **Rainy Window**: Pink noise shaped by dual resonant filters.
  - 📻 **Vinyl Crackle**: Highpass noise with random impulse micro-pops.
  - ☕ **Café Murmur**: LFO-modulated formant bandpass chatter.
  - 🕰️ **Clock Ticks**: Alternating triangle wave pulses.
  - 🍃 **Brown Wind**: Low-frequency atmospheric swells.
- **Mood Reflection Journal**:
  - Live word count and tag selector (`#DeepWork`, `#Reading`, `#Code`).
  - Saves your daily entries directly to browser `localStorage`.
  - Palette selector (`Honey`, `Slate`, `Mocha`, `Moss`, `Dusk`) that dynamically recalculates ambient desk lighting and window tints.
- **Interactive Desk Lamp**: Clickable lamp with a warm radial lighting cone.

### Quick Start
Open `cozy_desk.html` in any browser:
```bash
# Double-click cozy_desk.html, or serve locally:
python -m http.server 8000