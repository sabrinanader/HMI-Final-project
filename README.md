
---

# 🎹 PyQt5 Music Instrument App

This is a multi-instrument desktop application built using **PyQt5**. It allows users to play sounds from a **piano**, **xylophone**, **video game soundboard**, and even includes a **karaoke player**. The app also supports **recording and saving** sequences of notes.

---

## 🚀 Features

* 🎼 **Instruments Supported**:

  * Piano (Do, Ré, Mi, Fa, Sol, La, Si)
  * Xylophone
  * Retro Video Game Soundboard
* 🎤 **Karaoke Player**: Play a background audio track with lyrics displayed.
* 🎧 **Sound Playback** using Qt Multimedia.
* 💾 **Record Mode**: Save the sequence of notes you play to a file.
* 🛠️ **Toolbar**:

  * Open, Save, Quit
  * Switch instruments
  * Change piano octave range (1–3)

---

---

## 🛠 Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/pyqt5-music-app.git
   cd pyqt5-music-app
   ```

2. **Install dependencies**:

   ```bash
   pip install PyQt5
   ```

3. **Directory Structure**:
   Make sure your project folder includes the following:

   ```
   sounds/
   ├── do.wav
   ├── re.wav
   ├── ...
   ├── karaoke.mp3
   ```

   Ensure that all `.wav` and `.mp3` files are properly placed in the `sounds/` directory.

---

## ▶️ Running the App

Run the application with:

```bash
python main.py
```

*(Replace `main.py` with the actual file name of the script.)*

---

## 🎹 Controls

* Click instrument buttons to play notes.
* Use the toolbar to:

  * Switch instruments
  * Start/Stop recording
  * Open a saved note sequence
* Adjust octaves with the spin box (for piano).

---

## 🗂 File Types

* **.txt** — Used to store sequences of notes in plain text, one per line.
* **.mp3** — Used in karaoke mode for background playback.

---

## 🧩 Dependencies

* [PyQt5](https://pypi.org/project/PyQt5/)
* Python 3.7+

---

## 💡 TODO / Improvements

* Add MIDI export
* Visual feedback on notes
* Keyboard mapping for notes
* Volume control

---



---
