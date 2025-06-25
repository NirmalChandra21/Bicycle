# Bicycle Three.js Demo

This repository contains a small demo built with [Three.js](https://threejs.org/) and [Vite](https://vitejs.dev/). It showcases an interactive bicycle model with scroll driven animations.

## Setup

1. Install Node.js (any recent LTS version works) and install dependencies:
   ```bash
   npm install
   ```
2. Start a development server:
   ```bash
   npm run dev
   ```
   The site will be available on the host shown in the terminal.
3. Create a production build:
   ```bash
   npm run build
   ```
   Preview the built site locally with:
   ```bash
   npm run preview
   ```

## Assets

All required static assets live under the **public/** folder. This includes:

- `draco/` – Draco decoder files used by the GLTF loader.
- `fonts/` – font files used in the UI.
- `images/` – images referenced in the page sections.
- `models/` – the `bike-model.glb` file.
- `textures/` – environment map textures.

These files are necessary for the demo to run correctly.

## Interactive Features

- A preloader hides the page until assets are ready.
- A fully modeled bicycle that users can inspect.
- Scroll based animations and a dark/light theme toggle.

Version information is stored in `package.json` (currently `0.0.0`).
