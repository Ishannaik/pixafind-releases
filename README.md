<p align="center">
  <img src="assets/logo.png" alt="PixaFind" width="320">
</p>

<h3 align="center">Search your files by what's <em>in</em> them — not their names.</h3>

<p align="center">
  AI-powered local file search for Windows. Runs <strong>100% on your machine</strong>.<br>
  No cloud. No API keys. No telemetry. Your files never leave your computer.
</p>

<p align="center">
  <a href="https://github.com/Ishannaik/pixafind-releases/releases/latest"><img src="https://img.shields.io/github/v/release/Ishannaik/pixafind-releases?label=download&color=60cdff&style=for-the-badge" alt="Download"></a>
  &nbsp;
  <a href="https://pixafind.com"><img src="https://img.shields.io/badge/pixafind.com-visit-1a1a1a?style=for-the-badge" alt="Website"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Windows%2010%2F11-0078D4.svg" alt="Platform: Windows">
  <img src="https://img.shields.io/badge/built%20with-Tauri%202-FFC131.svg" alt="Built with Tauri 2">
  <img src="https://img.shields.io/badge/privacy-100%25%20offline-2ea043.svg" alt="100% offline">
</p>

<sub align="center">Formerly "Local AI Search" — renamed to PixaFind with v0.4.0.</sub>

---

## Why PixaFind

You took 8,000 photos last year. You remember one — a sunset by a lake. You don't remember the filename, the folder, or the date.

**You shouldn't have to.**

PixaFind indexes your files by **what's actually in them**. Type `"sunset over a lake with mountains"` and the photo surfaces. Type `"the spreadsheet about Q3 budget"` and the doc surfaces. Everything — the AI models, the vector index, the search — runs **on your machine**.

---

## What it does

| | Feature | What it means in practice |
|---|---|---|
| 🖼 | **Semantic image search** | Describe a photo in plain English; SigLIP2 finds it. "Cat in a sunbeam" works. So does "blurry photo of a whiteboard." |
| 🔍 | **Find visually similar** | Click any photo → DINOv3 surfaces visually similar shots across your whole library |
| 📄 | **Text, PDF & Office search** | `.pdf`, `.docx`, `.pptx`, `.md`, `.txt`, code — ~30 file types. Hybrid semantic + keyword (BM25) ranking. |
| ⚡ | **Spotlight overlay** | A global hotkey opens a floating search bar from any app |
| 🚀 | **Uses your GPU** | CUDA / DirectML auto-detected for fast indexing. CPU fallback always works. |
| 🔌 | **100% offline** | Zero network calls. Zero telemetry. Air-gap friendly. |
| 💾 | **Incremental indexing** | Hash-based change detection re-indexes only what changed |
| 🪶 | **5 MB native shell** | Built on Tauri 2, not Electron — a real native window, not a Chrome tab |

---

## Pricing

PixaFind has a **free tier** to get started, with Pro plans that unlock unlimited folders, faster indexing, and priority features.

<p align="center">
  <a href="https://pixafind.com"><strong>→ See plans &amp; pricing at pixafind.com</strong></a>
</p>

---

## Download &amp; install

1. Grab the latest **`.msi`** installer from the [**Releases**](https://github.com/Ishannaik/pixafind-releases/releases/latest) page (or from [pixafind.com](https://pixafind.com)).
2. Run it. PixaFind downloads its AI models on first launch (~500 MB, one time).
3. Point it at a folder and start searching.

Updates are delivered automatically through the in-app updater.

### Requirements
- Windows 10 / 11 (64-bit)
- 4 GB RAM minimum, 8 GB recommended
- ~500 MB free disk (app + models), plus index storage that scales with your library

---

## Your privacy is the product

PixaFind makes **zero network calls** for search. The models run locally, the index lives on your disk, and nothing about your files — not names, not contents, not thumbnails — is ever uploaded. There is no account required to search, and no telemetry.

---

<p align="center">
  <sub>PixaFind is commercial software. © 2026 <a href="https://pixafind.com">PixaLabs</a>. All rights reserved.<br>
  This repository hosts installer downloads and update artifacts only — the application source is private.</sub>
</p>
