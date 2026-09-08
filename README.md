<div align="center">

  <br />

  # 🛡️ Shield Pro — The Sovereign Academic Study Operating System

  **Engineered for Serious Aspirants & Exam Rankers**  
  *(UPSC CSE, CA Final/Inter, JEE Advanced, NEET-UG, CFA, Gate & Professional Exams)*

  [![Release](https://img.shields.io/badge/Release-V5.01-d4af37?style=for-the-badge&logo=android&logoColor=black)](https://github.com/gsshetty357-gif/shieldpro/releases)
  [![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-3b82f6?style=for-the-badge&logo=android)](https://github.com/gsshetty357-gif/shieldpro)
  [![Architecture](https://img.shields.io/badge/Architecture-Kotlin%20%7C%20Compose%20%7C%20Room-10b981?style=for-the-badge&logo=kotlin)](https://github.com/gsshetty357-gif/shieldpro)
  [![License](https://img.shields.io/badge/License-Proprietary-8b5cf6?style=for-the-badge)](https://github.com/gsshetty357-gif/shieldpro)

  <br />

  ---

  ### *"Transforming chaotic video platforms into a closed, high-precision academic utility."*

  <br />

</div>

## 📌 Executive Overview

**Shield Pro** is an offline-first, distraction-quarantined academic operating system designed for competitive exam rankers. Modern video platforms are weaponized with recommendation algorithms, clickbait feeds, shorts traps, and infinite scrolling loops designed to hijack a student's attention.

**Shield Pro** solves this by establishing a **Zero-Trust Whitelist Sandbox**. It isolates educational channels, blocks all algorithmic traps at the network layer, accelerates lectures with calibrated DSP audio processing, and unifies local offline media with online video playlists in a single high-security vault.

---

## 🏛️ Architect & Engineering Credits

<div align="center">

  ### 👑 **Architected & Engineered by Ganesh Shetty** 👑

  *Conceived, designed, and crafted with uncompromising precision for academic excellence.*

</div>

---

## ⚡ Key System Capabilities & Architectural Systems

### 1. 🛡️ Zero-Trust Whitelist Engine (How It Works)
* **Algorithmic Quarantine:** Home feeds, search bars, trending pages, and "up next" autoplay recommendations are 100% trapped and non-existent.
* **Verified Faculty Isolation:** Accessing an approved channel grants a pure, chronological playlist view of marathon lectures, subject modules, and chapter series—nothing else.
* **Network-Level Anti-Shorts Interception:** Any short-form media link (`/shorts/`) is trapped and permanently blocked before a single frame can render.

### 2. ⚡ Calibrated Audio DSP (250ms Skip Silence Engine)
* **Lecture-Optimized DSP:** Built with `SilenceSkippingAudioProcessor` over a custom Android `DefaultAudioSink`.
* **250ms Acoustic Silence Gate:** Skips dead pauses in lectures while maintaining a 20ms smooth cross-fade window, eliminating audio popping, underruns, or repeated syllables.
* **Intelligent Speech Preservation:** Preserves soft consonants (*P, T, S*) and instructor commentary while trimming non-productive pause time.

### 3. 🎙️ Real-Time Voice Notes & Timestamp Synchronizer
* **Auto-Pause Synchronization:** Starting a voice note automatically dispatches a pause trigger to both local ExoPlayer and YouTube IFrame engines, stopping audio bleed over the microphone.
* **Timestamp Association:** Dictated voice notes are automatically transcribed and bound to the exact playback timestamp (`MM:SS`) for instant revision jump-backs.

### 4. 📁 Dual-Stream Offline & Online Video Vault
* **Unified Workspace:** Seamlessly play offline local MP4/MKV video files alongside whitelisted online YouTube playlists in a single unified subject folder hierarchy.
* **Orphan-Protection Folder Deletion:** Reorganizing or deleting subject sub-folders automatically reassigns lectures to the parent directory—preventing lost study progress or orphaned notes.

### 5. 🔁 A-B Timestamp Segment Repeater
* **Precision Looping:** Set micro-second start (`Point A`) and end (`Point B`) markers to infinitely loop complex lecture derivations or accounting problems until completely mastered.

### 6. ⏱️ Focus Lock Pomodoro Timer & Study Analytics
* **Integrated Pomodoro Engine:** Work-rest cycles with ambient high-tech audio cues.
* **Automated Log Engine:** Tracks and records total focused study seconds per lecture into local SQLite storage for daily productivity analytics.

### 7. 🖼️ Native System Picture-in-Picture (PiP) & Media Controls
* **PiP Float Engine:** Seamlessly transitions into native System PiP mode upon minimizing or switching apps.
* **Remote Actions & Unplug Protection:** Includes playback remote actions and `ACTION_AUDIO_BECOMING_NOISY` listener to automatically pause video when headphones are disconnected.

---

## 🛠️ Technology Stack & Architecture

| Layer | Technology Used |
| :--- | :--- |
| **Language** | 100% Modern Kotlin |
| **UI Framework** | Jetpack Compose (Material Design 3 Glassmorphism) |
| **Local Persistence** | SQLite Room Database with KSP |
| **Media Player Engine** | Jetpack Media3 (ExoPlayer) + Custom AudioSink DSP |
| **Async & Reactive Flow** | Kotlin Coroutines + `StateFlow` + `collectAsStateWithLifecycle` |
| **Web Engine** | Hardware-Accelerated WebView (`LAYER_TYPE_HARDWARE`) + Bi-Directional AndroidBridge |
| **Architecture** | MVVM + Clean Repository Pattern |

---

## 📥 Installation & Setup

### Direct APK Download
You can download the compiled installer directly from GitHub Releases:

* 📦 **Latest Version:** [Shield Pro V5.01 Release](https://github.com/gsshetty357-gif/shieldpro/releases/latest/download/app-release.apk)
* 🔗 **All Releases:** [GitHub Releases Page](https://github.com/gsshetty357-gif/shieldpro/releases)

---

## 📄 License & Disclaimer

Copyright © 2026 **Ganesh Shetty**. All rights reserved.

*Shield Pro is developed as an independent educational productivity utility. All trademarked names and logos belong to their respective owners.*

---

<div align="center">

  **Built with ❤️ for Rankers & Serious Aspirants**

</div>
