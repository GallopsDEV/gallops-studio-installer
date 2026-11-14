# Gallops Studio

Gallops Studio is a Windows desktop app for creating **lyric videos**. Load a song and its LRC lyrics, add image or video backgrounds, choose an animated lyric style, and export a finished video.

This repository hosts the **official installers**. Download them from the [Releases](../../releases) page.

## Download and install
1. Open the [latest release](../../releases/latest).
2. Under *Assets*, download `GallopsStudio_Setup_X.Y.Z.exe`.
3. Run the installer and follow the steps.
4. Start Gallops Studio and enter your License Key, then click **Activate Online**.

### Requirements
- Windows 10 or 11 (64-bit)
- Internet connection for activation. After that the app works offline and checks again online about every 7 days.
- A valid License Key

### Verify the download (recommended)
Each release lists a SHA-256 checksum. Compare it with your file in PowerShell:
```
Get-FileHash .\GallopsStudio_Setup_X.Y.Z.exe -Algorithm SHA256
```
The installer is not code-signed yet, so Windows SmartScreen may warn you. Only continue if the checksum matches.

## What it does
- **Timeline editor:** multi-track video, overlay, audio, text, and lyrics tracks with crossfades, Ken Burns zoom, keyframes, volume curves, and markers
- **Lyrics:** word-timed LRC, syllable editing, multiple lyrics tracks, 9 animation modes (word pop, typewriter, karaoke bounce, blur focus, glitch, neon flicker, and more)
- **Looks:** audio visualizers, effects (snow, falling hearts, dancing lights), and a built-in style gallery
- **Export:** up to 4K and 1080p vertical (9:16), hardware encoding (QSV, NVENC, AMF), 30-second preview, and SRT / ASS karaoke / LRC subtitle files
- **Projects:** `.gsp` files, auto-save, and shareable `.gsstyle` styles

## Quick start
1. In the Timeline, click **+ Audio Clip(s)…** and choose your song.
2. Click **LRC** in the toolbar and choose the lyrics file.
3. Click **+ Add BG Clip(s)…** and add an image or video.
4. Press `Space` to preview, and adjust the look in the **Style** tab.
5. Choose the resolution and quality in the **Export** tab, then click **Export** in the toolbar.

Press `F1` inside the app for the full searchable Help.

## Updates
The app checks this repository for a newer release a few seconds after it starts. If one exists, a **May bagong version** button appears in the status bar and opens the release page. Nothing is downloaded or installed automatically.

## Third-party software
Gallops Studio includes an **LGPL** build of FFmpeg and uses Qt for Python (PySide6, LGPL), pygame, and OpenCV. License texts are installed with the app and listed in its third-party notices.

## Support
Visit **songerist.com** for questions or support. Please never share your License Key publicly.
