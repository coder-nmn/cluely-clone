# Cluely Clone

This repository contains a transparent overlay Electron app for live OpenAI answers. The overlay window stays always on top, hidden from the dock and screen sharing, letting you interact with the assistant while recording or presenting.

## Features

- Transparent overlay window that can be moved around.
- Toggle overlay visibility with a global shortcut (Ctrl+Shift+O).
- Clean UI built with HTML/CSS and controlled via Electron's main and preload scripts.
- Cross platform packaging via electron‑builder.

## Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Run the application in development mode:

   ```bash
   npm start
   ```

3. Build production packages for your OS:

   ```bash
   npm run build
   ```

## File Structure

- `index.html` – The HTML for the overlay UI.
- `main.js` – Electron main process that creates the window and manages events.
- `preload.js` – Preload script bridging between the renderer and main.
- `build.sh` – Shell script to automate build tasks.

## License

This project is currently missing a license. Feel free to add one that suits your use case.
