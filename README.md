# cabin-in-the-woods

A simple 3D web application built with Three.js that lets you explore a cabin interior in first-person view.

## Features
- First-person movement with WASD keys
- Mouse look (click to lock cursor)
- Collision detection with objects
- Flashlight lighting
- Loads 3D models from GitHub repository

## Deployment to GitHub Pages
1. Ensure your repository is public.
2. Go to repository Settings > Pages.
3. Set source to "Deploy from a branch" and select "main" branch.
4. The site will be available at `https://ixlisgood.github.io/cabin-in-the-woods/`.

## Local Development
1. Ensure you have a local web server.
2. Run the server in the project directory:
   ```
   python3 -m http.server 8000
   ```
3. Open `http://localhost:8000` in your browser.
4. Click anywhere to lock the mouse and start exploring.

## Assets
- `couch.obj`: 3D model of a couch
- `cabin.glb`: 3D model of the cabin

Assets must be committed to the repository for the app to load them properly.