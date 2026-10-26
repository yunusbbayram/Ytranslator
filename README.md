<p align="center">
  <a href="README.md"><strong>🇬🇧 English</strong></a> &bull;
  <a href="README_TR.md">🇹🇷 Türkçe</a>
</p>

# Ytranslator v1.4 - Ultra-Fast & Intelligent Windows Translation Assistant

<p align="center">
  <img src="https://raw.githubusercontent.com/yunusbbayram/Ytranslator/main/logo.png" alt="Ytranslator Logo" width="100" />
</p>

<p align="center">
  <strong>Ultra-Fast, Clipboard-Protected, 7 Display Modes & AI-Powered Desktop Translation Assistant for Windows 10 and 11</strong>
</p>

<p align="center">
  <a href="https://github.com/yunusbbayram/Ytranslator/releases/latest"><img src="https://img.shields.io/github/v/release/yunusbbayram/Ytranslator?color=38bdf8&label=Release&logo=github" alt="GitHub Release"></a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(64--bit)-0078d4?logo=windows" alt="Platform">
  <img src="https://img.shields.io/badge/Languages-93%20Supported-34d399" alt="93 Languages">
  <img src="https://img.shields.io/badge/Memory%20Usage-~50%20MB-blue" alt="RAM Usage">
  <img src="https://img.shields.io/badge/License-Free%20%26%20Open%20Source-purple" alt="License">
</p>

---

## 📌 Table of Contents
- [About](#-about)
- [Downloads (v1.4)](#-downloads-v14)
- [What's New in v1.4](#-whats-new-in-v14)
- [7 Standard Translation Display Modes](#-7-standard-translation-display-modes)
- [6 Translation Trigger Methods](#-6-translation-trigger-methods)
- [Key Features](#-key-features)
- [Keyboard Shortcuts](#-keyboard-shortcuts)
- [Running from Source & Building](#-running-from-source--building)
- [FAQ](#-frequently-asked-questions-faq)
- [Developer & Contact](#-developer--contact)

---

## 📖 About

**Ytranslator** is a lightweight, responsive desktop translation assistant for Windows designed to eliminate the hassle of switching browser tabs, visiting translation websites, and doing manual copy-pasting.

Whether you are reading a PDF, browsing in Chrome or Edge, drafting a Word document, or playing a game, simply select the text or double-click a word; the translation appears beside your cursor instantly or is spoken aloud naturally.

Built on the minimalist philosophy of *voidtools Everything*, Ytranslator consumes practically zero CPU when idle and maintains a memory footprint of merely ~50 MB RAM.

---

## 📥 Downloads (v1.4)

| Package | Type | Description |
| :--- | :--- | :--- |
| [**Ytranslator_Setup_v1.4.exe**](https://github.com/yunusbbayram/Ytranslator/releases/download/v1.4/Ytranslator_Setup_v1.4.exe) | **Setup Installer** | Inno Setup wizard that automatically detects your Windows display language in 48 languages. Configures Start menu, desktop shortcuts, and auto-start with Windows. |
| [**Ytranslator.exe**](https://github.com/yunusbbayram/Ytranslator/releases/download/v1.4/Ytranslator.exe) | **Portable Edition** | Zero installation, no admin rights required. Portable single-executable file ideal for USB flash drives and restricted systems. |

---

## 🚀 What's New in v1.4

1. **7 Standard Translation Display Modes:** A standardized suite of 7 translation modes across all UI windows (*Popup, Popup + Voice, Popup Minimal, Popup Minimal + Voice, Translation Window, Voice, Voice Play*).
2. **Re-Translate (3rd Translation Card / Back Translation):** A 3rd panel inside the Translation Window that automatically translates the target translation back into your source language, allowing you to instantly verify translation accuracy and nuance.
3. **Smart Two-Way Auto-Switching:** If the selected text matches your target language, Ytranslator automatically translates to your alternative language (e.g., English). If it also matches the alternative language, it intelligently falls back to your Windows system language. You will never see identical source and output text!
4. **Dedicated Modes for Voice: Mode 6 (Voice) vs. Mode 7 (Voice Play):**
   - *Mode 6 (Voice):* Speech begins automatically upon selection; clean interface without redundant play buttons or minimal popups; cancellable instantly via `[✕]` or `Esc`.
   - *Mode 7 (Voice Play):* Speech starts only when you click the active green **Play (▶)** button. Displays an accompanying minimal translation card. The button morphs into a red **Stop (■)** button during playback for instant pause/cancellation. Glows gently in the center of the screen on initial launch and can be pinned anywhere.
5. **Dynamic Reading Timeout:** Floating popups and minimal cards calculate display duration dynamically according to word and character count (ranging from 4s up to 35s), giving you ample time to finish reading long paragraphs.
6. **Strengthened Double-Click Engine:** The low-level mouse hook has been overhauled to eliminate missed detections on consecutive double-clicks, achieving 100% reliable word capture.
7. **Word-Wrap in Translation Window:** Text inputs now wrap words automatically based on window width instead of spawning horizontal scrollbars, providing a clean vertical reading flow.
8. **Reset to Factory Defaults & Confirmation Dialog:** Added a dedicated reset button in Settings with a custom dark-glass confirmation popup that restores settings according to your detected OS language.
9. **100% Complete Localization in 93 Languages:** All tray menus, settings tabs, modes, buttons, tooltip callouts, and the multi-line "About" window are fully translated in 93 languages.
10. **CJK (Chinese, Japanese, Korean) Typography Refinements:** Font weights and typefaces (`Microsoft YaHei`, `PingFang SC`) have been calibrated to eliminate blurry or overly bold Asian glyphs, ensuring crisp, readable typography.

---

## 🎛️ 7 Standard Translation Display Modes

| No | Mode Name | How It Works | Best Use Case |
| :---: | :--- | :--- | :--- |
| **1** | **Popup (Default)** | Elegant floating card beside cursor with copy, TTS, mic, and pin features. | Web reading, skimming news, and fast dictionary lookups. |
| **2** | **Popup + Voice** | Shows the floating popup while simultaneously pronouncing the translation through speakers. | Language learners who want to see the text and hear the natural pronunciation together. |
| **3** | **Popup Minimal** | Ultra-clean card showing only the translated text, equipped with a top-right `[✕]` close button. | Distraction-free reading without visual clutter. |
| **4** | **Popup Minimal + Voice** | Displays the minimal text card while pronouncing the translation simultaneously. | Minimalist aesthetic with audio feedback. |
| **5** | **Translation Window** | Independent dual-panel workbench with dictionary, font resizing, and 3rd panel **Re-Translate** support. | Translating long emails, drafting texts, and deep language study. |
| **6** | **Voice (Normal)** | No large windows! A circular speaker appears beneath the text and speaks the translation instantly. | Listening through headphones without screen disruption. |
| **7** | **Voice Play** | Speaker appears with an active green **Play (▶)** button; clicking it speaks the translation and opens a minimal card. Button morphs to **Stop (■)** during playback. | Controlled playback only when you explicitly want to listen. |

---

## 🎯 6 Translation Trigger Methods

Choose how translations are initiated from Settings or the system tray menu:
1. **Keyless (On Selection / Mouse Up):** Triggers automatically the moment you finish selecting text with the mouse.
2. **Left Double-Click (Word Selection):** Double-clicking any word captures and translates it immediately.
3. **Double Ctrl:** Rapidly press `Ctrl` twice to translate selected text.
4. **Selection + Ctrl:** Hold down `Ctrl` while selecting text.
5. **Selection + Alt:** Hold down `Alt` while selecting text (hardware keyboard scan filter prevents browser menu bar focus loss).
6. **Selection + Shift:** Hold down `Shift` while selecting text.

---

## 🌟 Key Features

### 🖱️ Double Right-Click Context Menu
- Select any word or sentence in Windows and **double right-click** (click right mouse button twice rapidly) to reveal the modern dark-themed Ytranslator menu:
  - 📋 *Copy Text*
  - 🔊 *Voice Translation*
  - ⚡ *Translate in Translation Window*
  - 💬 *Translate in Popup*
  - 🌐 *Target Language Dropdown (16 popular + 90+ total languages)*
- **Respects Windows Native Context Menu:** Single right-click is left 100% untouched for Windows and applications (Copy, Paste, Inspect, etc.).

### 🛡️ Smart Clipboard Protection
- To acquire selected text across different desktop applications, Ytranslator temporarily simulates a copy operation. Before doing so, it backs up your existing clipboard contents (text, images, files) into memory and restores them milliseconds later. Your clipboard is never overwritten or lost.

### 🌐 93 Languages, Native Scripts & Full UI Localization
- Complete support for all **93 languages** powered by Google Translate.
- Languages are displayed in their native alphabets (`العربية`, `Русский`, `简体中文`, `हिन्दी`, `Ελληνικά`, `한국어`, `日本語`, etc.).
- Right-to-Left (RTL) layout is automatically enabled when selecting Arabic, Persian, Hebrew, or Urdu.

### ⚡ 0 Millisecond SHA-256 Cache
- Previously translated words and sentences are cached in memory using SHA-256 hashes. Selecting the same phrase again loads the result in **0.0 ms** without hitting the network, saving data and providing instantaneous feedback.

### ✨ Google Gemini (AI) Integration
- A Gemini API key is **not required**; Google Translate works out-of-the-box with unlimited free usage.
- Optionally enter a free API key from Google AI Studio to unlock contextual and idiomatic AI translations:
  - **Dynamic Model Auto-Discovery:** Automatically discovers latest available models (`gemini-2.5-flash`, `flash-lite`, etc.) on your account.
  - **Zero Thinking Latency (`thinkingBudget = 0`):** Suppresses reasoning delays for near-instant popup rendering.
  - **HTTP 429 Fallback Protection:** Seamlessly falls back to the next Flash model or Google Translate if rate limits are reached.

### 🌐 Chrome and Edge Context Menu Integration
- Includes an unpackaged browser extension in the `chrome_extension/` directory. Enable Developer Mode in `chrome://extensions` and load it to add native right-click Ytranslator submenus connected via local HTTP bridge (`127.0.0.1:49152`).

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Alt + Q` | Translates selected text immediately using the default display mode. |
| `Alt + W` | Toggles the independent Translation Window. |
| `Esc` | Immediately closes all open translation popups/cards and silences playing audio. |

---

## 💻 Running from Source & Building

### Prerequisites
- Python 3.10+ (64-bit Windows)
- Git

### Installation
```powershell
# 1. Clone the repository
git clone https://github.com/yunusbbayram/Ytranslator.git
cd Ytranslator

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch Ytranslator
python main.py
