# New York Landmark Building Flight Experience and Route

<img width="1099" alt="螢幕截圖 2024-08-09 下午4 34 41" src="https://github.com/user-attachments/assets/8f8e3d4e-57cf-43c6-b6c3-52d6a9000b13">

This project creates an interactive 3D visualization of a flight path between two iconic New York City landmarks: the Flatiron Building and the Empire State Building. It uses Cesium for 3D rendering and Google Maps API for route calculation.

### Features:
- 3D visualization of New York City using Google's Photorealistic 3D Tiles
- Calculated walking route between the Flatiron Building and Empire State Building
- Animated camera flight along the route
- Keyboard controls for manual camera movement

### Setup:
1. Replace `GMP_API_KEY` with your actual Google Maps API key in two places:
   - In the `<script>` tag for Google Maps API
   - In the URL for Google's 3D Tiles
2. Open the HTML file in a web browser

### Usage:
- The camera will automatically fly from the Flatiron Building to the Empire State Building
- Use arrow keys to move the camera forward, backward, left, or right
- Use W, S, A, D keys to adjust the camera angle

### Dependencies:
- Cesium.js
- Google Maps JavaScript API

