# ALTERED — Perception Filter Lab

A browser-based camera artwork with five fictional altered-perception presets: Drunk, Cannabis, Stimulant, Psychedelic, and Overdose / blackout. These are artistic interpretations, not medically accurate simulations.

## Run locally

No build or installation is required. From this folder, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://localhost:8000. Camera access requires localhost or HTTPS, a browser with WebGL, and camera permission.

## Use

- Start with the procedural night-scene demo, enable your camera, or load a local photo.
- Select a preset and adjust filter strength and color shift.
- Toggle Show original to compare; Back to sober resets the effect.
- Disable Animated distortion to freeze the motion.

## Implementation

- `index.html`: accessible interface and artwork context.
- `style.css`: responsive styling; Google Fonts fall back to system fonts.
- `app.js`: WebGL fragment shader, canvas-generated scene, temporal frame accumulation, local camera and image input.

Camera frames and selected photos stay in the browser. No recording, analytics, image uploads, API keys, or backend services are included. This repository contains only the current ALTERED source, with no reference video, historical media, or Sites credentials.

## Live site

https://third-place-doorway.risengrebe2.chatgpt.site/
