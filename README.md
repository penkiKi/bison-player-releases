<p align="right">
  <strong>English</strong> | <a href="./README.zh-CN.md">简体中文</a>
</p>

<div align="center">
  <img src="./pic/icon.png" alt="Bison Player icon" width="128" height="128" />
  <h1>Bison Player</h1>
  <p>A desktop music player built around synchronized lyrics and an immersive listening experience.</p>

  <p>
    <a href="https://v2.tauri.app/"><img src="https://img.shields.io/badge/Tauri-2-24C8DB?logo=tauri&amp;logoColor=white" alt="Tauri 2" /></a>
    <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-19-61DAFB?logo=react&amp;logoColor=111827" alt="React 19" /></a>
    <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&amp;logoColor=white" alt="TypeScript 5" /></a>
    <a href="https://github.com/penkiKi/bison-player-releases/releases/latest"><img src="https://img.shields.io/badge/Platform-Windows-0078D4?logo=windows&amp;logoColor=white" alt="Windows" /></a>
  </p>
</div>

## Preview

| Centered lyrics with compact controls | Expanded playback controls |
| --- | --- |
| ![Centered lyrics with compact controls](./pic/1.png) | ![Centered lyrics with expanded playback controls](./pic/2.png) |

| Background settings | Immersive mode |
| --- | --- |
| ![Background settings](./pic/3.png) | ![Immersive mode](./pic/4.png) |

| My playlists | Dynamic backgrounds and wallpaper library |
| --- | --- |
| ![My playlists](./pic/5.png) | ![Dynamic backgrounds and wallpaper library](./pic/6.png) |

## Features

- **Music discovery**: QR code sign-in, song search, trending searches, and personal playlists.
- **Complete playback controls**: Playback queue, repeat one, repeat all, shuffle, seeking, and volume control.
- **Synchronized lyrics**: Word-by-word timing, single-line or multi-line layouts, translations, romanization, and customizable typography and colors.
- **Desktop lyrics**: A separate always-on-top lyrics window with locking, playback controls, and appearance settings.
- **Immersive mode**: Full-screen lyrics and album-driven colors for a focused listening experience.
- **Dynamic backgrounds**: Album artwork gradients plus downloadable image, video, and web wallpapers.
- **Desktop integration**: System tray controls, single-instance behavior, Windows system media controls, and in-app updates.
- **Keyboard controls**: Space to play or pause, Left/Right to seek by 5 seconds, and Up/Down to adjust volume.

## Download

Download the latest Windows MSI installer from [Releases](https://github.com/penkiKi/bison-player-releases/releases/latest).


## Tech Stack

- [Tauri 2](https://v2.tauri.app/) / Rust
- [React 19](https://react.dev/) / TypeScript / Vite
- [Tailwind CSS 4](https://tailwindcss.com/)
- [Motion](https://motion.dev/) / [GSAP](https://gsap.com/)
- [Three.js](https://threejs.org/) / React Three Fiber
- [Apple Music-like Lyrics](https://github.com/Steve-xmh/applemusic-like-lyrics)

## Acknowledgements

- The Three.js scene and shaders used by the startup animation were adapted from [ykob/sketch-threejs](https://github.com/ykob/sketch-threejs), which is licensed under the MIT License.
- The NetEase Cloud Music API implementation references [2061360308/NeteaseCloudMusic_PythonSDK](https://github.com/2061360308/NeteaseCloudMusic_PythonSDK).
- The QQ Music API implementation references [L-1124/QQMusicApi](https://github.com/L-1124/QQMusicApi).
