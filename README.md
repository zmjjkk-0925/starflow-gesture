# Starflow Gesture

An interactive 3D purple particle field controlled by hand gestures. Pinch to attract particles, move your hand to pull the field, and release to send particles flying toward the camera.

## Live site

https://zmjjkk-0925.github.io/starflow-gesture/

## Features

- MediaPipe hand tracking with local model and WASM assets
- Three.js particle rendering with depth, glow, and perspective
- Pinch attraction and three-dimensional release burst
- Responsive performance settings for phones and computers
- Installable PWA with offline asset caching
- Pointer and touch fallback when camera access is unavailable

## Local preview

Camera access requires HTTPS or localhost. Serve this directory with any static HTTP server, then open the local URL in a modern browser.

See [DEPLOY.md](DEPLOY.md) for deployment details and browser requirements.
