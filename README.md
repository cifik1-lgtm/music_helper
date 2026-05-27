# Music Helper 🎹

**A browser-based virtual instrument playground — play piano, guitar, violin, drums and more right from your keyboard.**

No plugins. No downloads. No MIDI hardware required. Just open it in your browser and start playing.

---

## 🎵 Features

### 11 Virtual Instruments
Switch between instruments with one click:
- **Piano** — Classic sawtooth wave with fast attack
- **Violin** — Slow attack with slight detune for a natural vibrato effect
- **Guitar** — Warm triangle wave with quick decay
- **Electric Guitar** — Edgy square wave with added detune
- **Bass** — Deep sine wave, automatically plays one octave lower
- **Trumpet** — Brassy square wave with a slow attack
- **Recorder** — Soft triangle wave
- **Keypad** — Short, clean sine pluck
- **Kick Drum** — Frequency-swept sine for a punchy kick
- **Snare Drum** — White noise + tone layered for a realistic crack
- **Hi-Hat** — High-passed white noise for a crisp metallic sound

### 🎹 Play 3 Ways
- **Click or tap** the on-screen piano keys with your mouse or finger
- **Use your physical keyboard** — keys are mapped to notes (A=C4, S=D4, D=E4...)
- **Trigger drums** with Z (Kick), X (Snare), C (Hi-Hat)

### 🎙️ Microphone Input + Visualizer
Connect your microphone and see a live real-time frequency bar visualizer rendered on a canvas.

### 🎛️ Master Volume Control
A smooth slider controls the global volume of all instruments.

---

## 🚀 How to Run

### Option 1: Direct (no server needed)
Just open `templates/index.html` directly in your browser.

### Option 2: Via Flask (recommended)
```bash
git clone https://github.com/cifik1-lgtm/music_helper.git
cd music_helper
pip install flask
python main.py
```
Then open your browser and go to: **http://127.0.0.1:5000**

---

## ⌨️ Keyboard Shortcuts

| Key | Note / Action |
|-----|--------------|
| `A` | C4 |
| `W` | C#4 |
| `S` | D4 |
| `E` | D#4 |
| `D` | E4 |
| `F` | F4 |
| `T` | F#4 |
| `G` | G4 |
| `Y` | G#4 |
| `H` | A4 |
| `U` | A#4 |
| `J` | B4 |
| `K` | C5 |
| `O` | C#5 |
| `L` | D5 |
| `P` | D#5 |
| `;` | E5 |
| `Z` | Kick Drum |
| `X` | Snare Drum |
| `C` | Hi-Hat |

---

## 🛠️ Tech Stack

- **Backend:** Python / Flask (minimal — just serves the HTML)
- **Frontend:** Pure HTML + CSS + Vanilla JavaScript
- **Audio:** Web Audio API (no external libraries, built into all modern browsers)

---

## 📝 License

MIT — Free to use, fork, and extend.
