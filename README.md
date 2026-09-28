Конечно. Вот **полный `README.md` целиком**, включая заголовок, эмодзи, выделения, бейджи, разделы и весь текст — можно **сразу копировать одним блоком**:

````markdown
# 🎧 SoundDeck

> **A simple, modern and free soundboard for Windows.**

[![Platform](https://img.shields.io/badge/platform-Windows-0078D6?style=flat-square&logo=windows)](https://www.microsoft.com/windows)
[![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python)](https://www.python.org/)
[![Qt](https://img.shields.io/badge/UI-PySide6-41CD52?style=flat-square&logo=qt)](https://doc.qt.io/qtforpython/)
[![Status](https://img.shields.io/badge/status-In%20Development-orange?style=flat-square)](#-project-status)
[![License](https://img.shields.io/badge/license-TBD-lightgrey?style=flat-square)](#-license)

**SoundDeck** is a lightweight desktop soundboard for Windows designed for quickly playing sounds, assigning hotkeys, organizing sound libraries and controlling audio from one simple interface.

The goal is simple:

> 🎯 **Make playing sounds fast, simple and accessible.**

No unnecessary complexity.  
No subscription required for the core application.  
No overloaded interface.

---

## ✨ Features

### 🔊 Soundboard

- ▶️ Play sounds instantly
- ⏹️ Stop playback
- 🔁 Loop sounds
- 🎚️ Individual sound volume
- 🔊 Master volume
- ⚡ Real-time volume control
- 📊 Playback progress
- 🔢 Playback counter
- 🕘 Recently played sounds
- ⭐ Favorites

### 📚 Sound Library

Organize your sounds in one place.

- 📂 Categories
- 🔎 Search
- ↕️ Sorting
- ⭐ Favorites
- 🕘 Recent sounds
- 🖱️ Drag & Drop importing
- 📥 Import multiple sounds
- 🗑️ Remove sounds
- ✏️ Rename sounds
- 🏷️ Assign categories

### ⌨️ Global Hotkeys

Assign a keyboard shortcut to any sound and trigger it while using another application.

Example:

```text
F1 → Vine Boom
F2 → Bruh
F3 → Explosion
F4 → Minecraft Hit
````

Perfect for:

* 🎮 Gaming
* 💬 Discord
* 🎙️ Voice chat
* 📹 Streaming
* 🎬 Content creation
* 😂 Memes and reactions

---

## 🎙️ Audio Recording

SoundDeck includes built-in audio recording.

Record audio directly from your microphone and instantly add the recording to your sound library.

Planned recording improvements include:

* 🎙️ Microphone recording
* ✂️ Quick trimming
* 🔊 Automatic normalization
* 💾 Automatic library import
* 🎚️ Recording device selection

---

## 🎛️ Audio Controls

SoundDeck is designed to provide fast control over every sound.

### Master Volume

Control the volume of all SoundDeck playback.

### Per-Sound Volume

Every sound can have its own volume level.

### Real-Time Control

Volume changes are applied while audio is playing without restarting the sound.

### Loop

Keep a sound playing continuously until it is stopped.

---

## 🎨 Themes & Customization

SoundDeck includes customizable interface settings.

### 🌓 Built-in Themes

* 🌑 Dark
* 🖤 Dim
* ☀️ Light
* ⚫ High Contrast

### 🎨 Appearance Settings

Customize:

* Accent color
* UI density
* Sidebar width
* Interface scale
* Playback controls
* Library display
* Categories
* Statistics

The goal is to keep the interface simple while still giving users control over how SoundDeck looks and behaves.

---

## 🖥️ Interface

SoundDeck focuses on a **minimal and practical interface**.

Instead of filling the application with large cards, gradients and unnecessary borders, the interface uses:

* clean typography
* subtle separators
* compact controls
* simple navigation
* minimal borders
* small corner radiuses
* clear spacing
* lightweight hover states

The sound list remains the main part of the application.

```text
┌──────────────────────────────────────────────────────┐
│ SoundDeck                         Search       + Add  │
├──────────────────────────────────────────────────────┤
│                                                      │
│ ▶ Vine Boom          Memes       F2        124 plays │
│ ──────────────────────────────────────────────────── │
│ ▶ Bruh               Memes       F3         87 plays │
│ ──────────────────────────────────────────────────── │
│ ▶ Explosion          Games       F4         52 plays │
│ ──────────────────────────────────────────────────── │
│ ▶ Minecraft Hit      Games       F5         31 plays │
│                                                      │
├──────────────────────────────────────────────────────┤
│ ▶ Vine Boom                              0:02 / 0:04 │
│ ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ │
│ Volume ──────────────────────── 80%          ■ Stop  │
└──────────────────────────────────────────────────────┘
```

---

## 🎵 Supported Audio Formats

SoundDeck supports common audio formats:

* `.WAV`
* `.MP3`
* `.OGG`
* `.FLAC`
* `.AIFF`

More formats may be added in future releases.

---

## 🚀 Planned Features

SoundDeck is still under active development.

The following features are planned:

### 🎚️ Advanced Audio

* 🌊 Waveform editor
* ✂️ Audio trimming
* 🎚️ Fade in / Fade out
* 🐌 Playback speed
* 🎵 Pitch control
* 🔊 Normalization
* 🔄 Reverse playback
* 🎛️ Audio effects
* 🔁 Advanced looping

### 📦 Sound Packs

Create and share complete sound collections.

```text
My Sound Pack
├── Memes
│   ├── Bruh.wav
│   ├── VineBoom.wav
│   └── Laugh.wav
│
├── Games
│   ├── Explosion.wav
│   └── Minecraft.wav
│
└── Music
    └── Intro.wav
```

Planned functionality:

* 📦 Create sound packs
* 📥 Import packs
* 📤 Export packs
* 🖼️ Pack artwork
* 📝 Pack descriptions
* 🔄 Pack updates
* 📚 Pack library

---

## 🎛️ Mixer

A dedicated mixer is planned for controlling multiple audio sources.

Example:

```text
Microphone     ████████████████ 100%
SoundDeck      ███████████      75%
Music          █████            30%
Effects        ████████         50%
```

Future mixer features:

* 🎙️ Microphone volume
* 🔊 SoundDeck volume
* 🎵 Music volume
* 🎚️ Separate channels
* 🔇 Mute
* 🎛️ Per-channel volume
* 📉 Audio ducking

---

## 🎙️ Discord & Gaming

One of the main long-term goals of SoundDeck is reliable integration with games and voice chat applications.

Planned features include:

* 🎙️ Virtual microphone
* 🎮 Game audio routing
* 💬 Discord support
* 🎤 Push-to-Talk
* ⚡ Auto PTT
* 📉 Voice ducking
* 🎚️ Microphone mixing
* 🔊 Separate monitoring volume

Example:

```text
You press F3

        ↓

SoundDeck plays the sound

        ↓

SoundDeck sends the sound
to the virtual microphone

        ↓

Discord / Game receives it
as microphone audio
```

---

## 📋 Queue

Queue multiple sounds and play them sequentially.

Example:

```text
1. Bruh
2. Vine Boom
3. Explosion
4. Laugh
5. Music
```

Planned controls:

* ▶️ Play queue
* ⏸️ Pause
* ⏭️ Next
* ⏮️ Previous
* 🗑️ Clear queue
* 🔀 Shuffle
* 🔁 Repeat

---

## 🧩 Profiles

Create different configurations for different situations.

Examples:

```text
🎮 Gaming
💬 Discord
📹 Streaming
🎙️ Voice Chat
😂 Memes
```

Each profile can have its own:

* sounds
* hotkeys
* volume
* categories
* mixer configuration
* playback settings

---

## ⚙️ Settings

SoundDeck aims to provide detailed customization without making the application complicated.

Settings will include:

### 🎨 Appearance

* Theme
* Accent color
* UI density
* Sidebar width
* Interface scale
* Animations

### 🔊 Playback

* Output device
* Master volume
* Default sound volume
* Loop behavior
* Queue behavior

### ⌨️ Hotkeys

* Global hotkeys
* Hotkey conflicts
* Modifier keys
* Push-to-Talk
* Auto PTT

### 📚 Library

* Default sound folder
* Categories
* Sorting
* Favorites
* Recent sounds
* Import behavior

---

## 🖥️ Requirements

SoundDeck currently targets:

* 🪟 **Windows 10**
* 🪟 **Windows 11**
* 🐍 **Python 3.11+**
* 🐍 **Python 3.12+ recommended**

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/SoundDeck.git
cd SoundDeck
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it:

```powershell
.venv\Scripts\activate
```

Install dependencies:

```powershell
python -m pip install -r requirements.txt --index-url https://pypi.org/simple
```

Run SoundDeck:

```powershell
python main.py
```

### ⚡ Windows Quick Start

You can also use:

```text
run.bat
```

The launcher script will prepare the environment and start SoundDeck.

---

## 🛠️ Technology

SoundDeck is built with:

* 🐍 **Python**
* 🖼️ **PySide6 / Qt**
* 🎵 **sounddevice**
* 🔊 **soundfile**
* ⌨️ **keyboard**
* 🔢 **NumPy**
* 🗄️ **SQLite**

SoundDeck is designed as a native desktop application.

It does **not** use:

* ❌ Electron
* ❌ Browser UI
* ❌ Web-based desktop framework

---

## 📁 Project Structure

```text
SoundDeck/
│
├── app/
│   ├── audio/
│   ├── core/
│   ├── hotkeys/
│   ├── library/
│   ├── recorder/
│   ├── settings/
│   └── ui/
│
├── data/
│
├── main.py
├── requirements.txt
├── run.bat
└── README.md
```

The architecture is designed to keep audio processing, UI, settings and library management separated.

---

## 🔐 Privacy

SoundDeck is designed around local-first functionality.

Your sound library and application settings are stored locally on your computer.

No account is required for the core application.

---

## 💡 Philosophy

SoundDeck is built around three simple principles:

### 🧹 Simple

The interface should be understandable immediately.

### ⚡ Fast

A sound should be playable with a click or a hotkey.

### 🆓 Free

The core SoundDeck experience should remain free.

---

## 🐛 Bug Reports

Found a bug?

Please open an **Issue** and include:

* Windows version
* Python version
* SoundDeck version
* Steps to reproduce the problem
* Error message
* Console output
* Screenshots or videos if possible

---

## 🤝 Contributing

Contributions are welcome!

You can help with:

* 🐛 Bug fixes
* ✨ New features
* 🎨 UI improvements
* 🎵 Audio processing
* 🧪 Testing
* 📖 Documentation
* 🌍 Translations

Before submitting a large change, please open an Issue to discuss the idea.

---

## 📜 License

The project license will be finalized before the first stable release.

---

## ⭐ Support the Project

If you like SoundDeck:

⭐ Star the repository
🐛 Report bugs
💡 Suggest features
🔧 Contribute code
📢 Share the project

Every contribution helps!
