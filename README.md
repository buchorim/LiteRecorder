# 🎬 LiteRecorder

**Lightweight Screen Recorder for Windows**

A fast, modern screen recording application with system audio capture, drawing tools, and customizable hotkeys.

---

## ✨ Features

- **🖥️ Screen Recording** - Capture your entire screen in high quality
- **🔊 System Audio** - Record system sounds using WASAPI loopback
- **🎤 Microphone** - Record microphone audio or both sources
- **✏️ Drawing Tools** - Annotate while recording (pen, shapes, text, arrows)
- **⌨️ Global Hotkeys** - Control recording with customizable shortcuts
- **🖱️ Click Highlighting** - Visual feedback for mouse clicks
- **⏱️ Countdown Timer** - Configurable delay before recording starts
- **📁 Auto-save** - Automatic file naming with timestamps

---

## 📥 Download

Download the latest version from [Releases](../../releases):

| File | Description |
|------|-------------|
| `LiteRecorder_Setup_x.x.x.exe` | **Recommended** - Full installer with uninstaller |
| `LiteRecorder.exe` | Portable version (no installation required) |

---

## 💻 System Requirements

### Minimum Specifications

| Component | Requirement |
|-----------|-------------|
| **OS** | Windows 10 (64-bit) |
| **CPU** | Intel Core i3 / AMD Ryzen 3 (4 cores) |
| **RAM** | 4 GB |
| **GPU** | Integrated graphics |
| **Disk Space** | 150 MB for installation |
| **Display** | 1280x720 (720p) |
| **Dependencies** | FFmpeg (for video encoding) |

### Recommended Specifications

| Component | Recommendation |
|-----------|----------------|
| **OS** | Windows 11 (64-bit) |
| **CPU** | Intel Core i5 / AMD Ryzen 5 (6+ cores) |
| **RAM** | 8 GB or more |
| **GPU** | Dedicated GPU with hardware encoding (NVENC/QSV) |
| **Disk Space** | SSD with 1+ GB free (for recordings) |
| **Display** | 1920x1080 (1080p) or higher |

> ⚠️ **Note:** Higher resolution/FPS recordings require more CPU/GPU power.

---

## ⚠️ Known Issues

| Issue | Status | Workaround |
|-------|--------|------------|
| Hardware encoder (h264_qsv/nvenc) may fail on some systems | Known | App auto-fallbacks to software encoder (libx264) |
| Hotkeys may conflict with other applications | Known | Change hotkeys in Settings → Hotkeys |
| System audio may not capture on some audio drivers | Known | Try selecting different speaker device |
| High CPU usage at 60 FPS with 4K resolution | Expected | Lower resolution or FPS for older hardware |
| Drawing overlay may flicker on multi-monitor setups | Known | Use single monitor during recording |
| Recordings longer than 2 hours may have sync issues | Known | Split long recordings into shorter sessions |
| Command prompt or command window showing in some areas | Known | Ignore it as it known as this software normal behavior, you may commonly see when accesing audio settings, check system, or evaluating performance, and also when encoding the screen record, if you believe seeing it on other state you can report an issue on this repo.


---

## 🚀 Quick Start

1. Download and run the installer
2. Launch LiteRecorder
3. Configure settings (output folder, quality, hotkeys)
4. Click **Start Recording** or press `F9`
5. Press `F9` again to stop

### Default Hotkeys

| Action | Shortcut |
|--------|----------|
| Start/Stop Recording | `F9` |
| Pause/Resume | `F10` |
| Toggle Drawing | `D` |
| Clear Drawings | `Delete` |

---

## 📸 Screenshots

*Coming soon*

---

## ⚙️ Settings

- **Video:** Resolution, FPS, codec, quality
- **Audio:** System/Microphone/Both/None
- **Output:** Custom save location, filename format
- **Hotkeys:** Customizable keyboard shortcuts
- **General:** Countdown timer, overlay visibility

---

## 📋 Changelog

### v2.1.0 (December 2025)
- Added text annotation tool
- Fixed system audio capture
- Improved hotkey handling
- Added countdown timer
- UI improvements

---

## 🔗 Links

- **Issues:** [Report a bug](../../issues)
- **Releases:** [Download latest](../../releases)

---


**© 2025 Arinara Network. All rights reserved.**
**© 2025 Arinara Network. All rights reserved.**
 All rights reserved.**

