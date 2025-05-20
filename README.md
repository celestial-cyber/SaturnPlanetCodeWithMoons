# SaturnPlanetCodeWithMoons
This project is a 3D interactive visualization of Saturn, its iconic ring system, and its moons, built using [Three.js](https://threejs.org/)

# 🌌 Saturn Visualization using Three.js
This project is a 3D interactive visualization of Saturn, its iconic ring system, and its moons, built using [Three.js](https://threejs.org/). It features:

- A realistic Saturn model with axial tilt
- Seven layered rings (D, C, B, A, F, G, E) with varying opacity and color
- Multiple moons orbiting Saturn with different speeds and sizes
- A starry background to simulate the outer space environment
- Smooth camera controls using OrbitControls

## 🚀 Live Demo
You can view the live demo by opening the `index.html` file in any modern browser (e.g., Chrome, Firefox, Edge).
> Note: This project uses ES module imports from a CDN, so if you're opening it from your local system, you may need to use a local server (e.g., with VS Code Live Server or Python's HTTP server).

## 📁 Project Structure
📦 saturn-visualization/
├── index.html
└── README.md


## 🛠 Technologies Used
- HTML5 + CSS
- JavaScript (ES6 Modules)
- [Three.js](https://threejs.org/) for 3D rendering
- OrbitControls for interactive camera movement

## 📸 Preview
![Saturn Preview](preview.png) <!-- Optional: Add a screenshot of your visualization -->

## 🧠 Concepts Demonstrated
- Planetary axial tilt and rotation
- Ring geometry creation using `THREE.RingGeometry`
- Orbital motion simulation for moons
- Scene setup and lighting
- Procedural starfield generation

## ⚙️ How to Run
### Option 1: With Live Server (recommended)
1. Clone the repository
2. Open the folder in VS Code
3. Right-click `index.html` and select **"Open with Live Server"**

### Option 2: Using Python HTTP Server

```bash
python3 -m http.server

