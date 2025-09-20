# Spotlite — Spotify-like Demo App (No Framework)
A lightweight, front-end-only music player inspired by Spotify. It uses **vanilla HTML/CSS/JS** with a tiny local audio file so everything works offline.

> Educational demo — not affiliated with Spotify.

## Features
- Responsive layout with sidebar, shelves, and sticky bottom player
- Play/Pause/Next/Prev, seekbar, volume, shuffle & repeat
- Queue management (play now, remove)
- Simple "Like" toggle
- Search filter (client-side)
- Mock playlists & tracks (replaceable)
- No external dependencies (icons via local SVG sprite)
- Works offline out of the box (local sample audio)

## Getting started
1. Unzip the project.
2. Open `index.html` in a modern browser.
3. Double-click a card to start playback, or choose a playlist on the left.

> Tip: You can replace `assets/audio/sample.wav` with your own `.mp3`/`.wav` files and update the `tracks` array in `app.js`.

## Customize content
Open `app.js` and edit the `tracks` and `playlists` arrays. Each track looks like:
```js
{ id: 't1', title: 'Sunset Drive', artist: 'Nova', album: 'Neon Roads', src: 'assets/audio/your-file.mp3', liked: false }
```

## Folder structure
```
spotify-clone/
├── index.html
├── styles.css
├── app.js
├── assets/
│   ├── audio/
│   │   └── sample.wav
│   └── img/
│       └── icons.svg
└── docs/
    ├── README.md
    └── DESIGN.md
```

## Notes
- This project is intentionally minimal and does **not** include authentication, streaming, licensing, or a backend.
- UI and naming are generic (“Spotlite”) and **not** using Spotify trademarks beyond inspiration.
