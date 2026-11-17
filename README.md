# Lumen Player

A smooth, modern video player for **Windows** and **Linux**.

**[⬇ Download the latest version](https://github.com/humidalex1-gif/lumen-player/releases/latest)**

| System | File |
|---|---|
| Windows 10 / 11 | `Lumen-Player-Setup-x.y.z.exe` |
| Linux (any distro) | `Lumen-Player-x.y.z-x86_64.AppImage` |
| Ubuntu / Debian | `Lumen-Player-x.y.z-amd64.deb` |

Installed copies update themselves automatically from these releases (Windows installer and Linux AppImage).

## Features

- Plays MP4, MKV, WebM, MOV, AVI, WMV, FLV, HEVC and more (uses [FFmpeg](https://ffmpeg.org) for older formats)
- **AI subtitles, offline** — generates subtitles on your computer with Whisper; nothing is uploaded
- **Translate subtitles** into Arabic and 15+ languages with Claude (your own API key)
- **Dual subtitles** — two languages on screen at once
- **Clip & reel export** — MP4, 9:16 Reel, 1:1 or GIF with subtitles burned in
- **AI recap, questions and chapters** for what you are watching
- **Series mode** — Up Next countdown, Skip Intro (chapters or automatic audio detection)
- **Library** — your folders sorted into shows and movies
- **Phone remote** — control playback from your phone over Wi-Fi
- Links, live streams and IPTV `.m3u` playlists
- Voice boost / night mode, equalizer, audio delay, picture controls, bookmarks, A-B loop
- Resume where you left off, per-video memory, picture-in-picture, screenshots

## Keyboard

Press `?` inside the app for the full list. Common ones: `Space` play/pause · `←` `→` seek · `F` fullscreen · `C` subtitles · `I` / `O` mark a clip · `Ctrl+E` export · `B` bookmark · `D` sound mode.

## Notes

- The Windows installer is not code-signed yet, so Windows may show "Windows protected your PC". Click **More info → Run anyway**.
- AI subtitles and clip export need FFmpeg (`winget install Gyan.FFmpeg` on Windows, `sudo apt install ffmpeg` on Ubuntu).
