<div align="center">
  <img src="docs/icon.png" alt="Video Editor Icon" width="128" />
  
  <h1 align="center">Video Editor by Fest</h1>

<p align="center">
  <strong>A professional desktop application built to automate the most tedious parts of editing short-form vertical content (Shorts, Reels, TikToks). Everything runs 100% locally and offline on your machine. No cloud subscriptions, no API keys, and complete data privacy.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue?style=flat-square" alt="Version" />
  <img src="https://img.shields.io/badge/platform-Windows-0078D6?style=flat-square&logo=windows" alt="Platform" />
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="License" />
</p>

## ✨ Core Features

- **Offline AI Auto-Captions:** Uses OpenAI's Whisper neural network to transcribe audio into mathematically synced typography animations instantly.
- **Smart Auto-Cut:** Leverages native `FFmpeg` waveform analysis to instantly detect and remove dead air and silent pauses from raw footage.
- **Non-Linear Editing (NLE) Interface:** A custom timeline manager to manually extend, trim, or remove clips with frame-perfect precision.
- **Hardware-Accelerated Rendering:** Mathematically draws and exports the final 9:16 composition as a crisp H.264 MP4.
- **CSV Workflow:** Import hundreds of custom text layers instantly via CSV.

---

![Video Editor by Fest - Interface](docs/Screenshot.png)

---

## 🚀 Download & Installation

You do not need to install Node.js or any developer tools to use this application.

1. Navigate to the **[Releases](../../releases)** tab on the right side of this GitHub repository.
2. Download the latest `Video-Editor-by-Fest-Setup.exe` file.
3. Run the installer.
4. Launch the application from your desktop or start menu!

_Note: Because this application processes AI audio transcription and video rendering locally, it is recommended to run this on a machine with a capable multi-core processor and dedicated graphics for the fastest export times._

## 🛠️ Tech Stack (Under the Hood)

For developers interested in the architecture:

- **Frontend UI:** React, Tailwind CSS, TypeScript
- **Backend Core:** Electron (Node.js), IPC Bridge
- **Media Engines:** Remotion, FFmpeg
- **Machine Learning:** Transformers.js (Whisper-tiny)

## License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">
  Built with care by <strong>Fest</strong>
</p>
