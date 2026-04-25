# cabin-in-the-woods

A simple 3D web application built with Three.js that lets you explore a cabin interior in first-person view.

## Features
- First-person movement with WASD keys
- Mouse look (click to lock cursor)
- Collision detection with objects
- Flashlight lighting
- Loads 3D models from GitHub repository

## How to Run
1. Ensure you have a local web server that supports ES modules (e.g., Python's http.server).
2. Run the server in the project directory:
   ```
   python3 -m http.server 8000
   ```
3. Open `http://localhost:8000` in your browser.
4. Click anywhere to lock the mouse and start exploring.

## Assets
- `couch.obj`: 3D model of a couch
- `cabin.glb`: 3D model of the cabin

Assets are loaded from the GitHub repository.