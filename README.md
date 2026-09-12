# Starflow Gesture

An interactive 3D purple particle field controlled by one or two hands. Pinch with one hand to attract particles and release to send them toward the camera. With two hands, move your palms together to gather the field or apart to expand it in three dimensions.

## Live site

https://zmjjkk-0925.github.io/starflow-gesture/

## Features

- MediaPipe one-hand and two-hand tracking with local model and WASM assets
- Three.js particle rendering with depth, glow, and perspective
- One-hand pinch attraction and three-dimensional release burst
- Two-hand gather and expansion control based on palm distance
- Switchable particle palettes: violet, aurora aqua, ember, and glacier blue
- Switchable gather forms: nebula, sphere, ring, heart, and spiral
- Strongly differentiated diffusion modes: radial starburst, rotating vortex, forward depth fountain, and travelling ripple shockwave
- Responsive performance settings for phones and computers
- Installable PWA with offline asset caching
- Pointer and touch fallback when camera access is unavailable

## Local preview

Camera access requires HTTPS or localhost. Serve this directory with any static HTTP server, then open the local URL in a modern browser.

See [DEPLOY.md](DEPLOY.md) for deployment details and browser requirements.
