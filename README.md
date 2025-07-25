# Voxel Explorer

Voxel Explorer is a simple 3D voxel world demo built with [Three.js](https://threejs.org/). It allows you to explore, add, and remove blocks in a Minecraft-like environment directly in your browser.

![Voxel Explorer Screenshot](rendertest.png)

## Features
- 3D voxel world rendered with Three.js
- Move freely in all directions (WASD + Space/Shift)
- Mouse look with pointer lock
- Add (right-click) and remove (left-click) cubes
- Custom outline with thick edges and diagonal crosses highlights the selected cube
- Real-time camera coordinates display
- Uses a local PNG texture for cubes

## Controls
- **W/A/S/D**: Move forward/left/backward/right
- **Space**: Move up
- **Shift**: Move down
- **Mouse**: Look around (after clicking in the window to lock pointer)
- **Left Click**: Remove the highlighted cube
- **Right Click**: Add a cube adjacent to the highlighted face

## Getting Started

1. **Clone or download this repository.**
2. Ensure `index.html` and `rendertest.png` are in the same directory.
3. Open `index.html` in your web browser (no server required).

> **Note:** For best results, use a modern browser (Chrome, Firefox, Edge, Safari). If you run into CORS issues with the texture, try running a simple local server (e.g., `python3 -m http.server`).

## Dependencies
- [Three.js](https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js) (loaded via CDN)

## License
This project is for educational and demonstration purposes.
