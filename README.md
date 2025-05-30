# 3D Wormhole Visualization

This project is a 3D wormhole visualization created using [Three.js](https://threejs.org/). It utilizes a parametric spline-based geometry to simulate the visual effect of traveling through a wormhole.

## 🚀 Demo

Open `index.html` in a modern browser that supports ES modules. No build step is required.

## 🧰 Technologies Used

- **Three.js**: For rendering the 3D scene.
- **JavaScript Modules (ES6)**: Modularized code for structure and maintainability.
- **HTML5**: For the minimal page structure.

## 📁 Project Structure

```
├── index.html # Entry point, loads index.js as a module
├── index.js # Main script initializing scene, camera, renderer, lights, and geometry
└── spline.js # Contains the SplineTubeGeometry class used to generate wormhole mesh
```

## 📸 Features

- A smooth camera animation down a spline curve
- Dynamic tube geometry using `SplineTubeGeometry`
- Configurable material properties (color, shininess)
- Responsive rendering with aspect-ratio correction

## 🧪 How to Run

1. Clone this repository or download the files.
2. Open `index.html` in any modern browser (e.g., Chrome, Firefox).
3. Use the mouse to explore the animation. The camera will automatically follow the wormhole spline.

## ⚙️ Customization

You can modify `index.js` to:

- Change the spline path
- Adjust camera speed and movement
- Alter lighting and material settings

## 📝 Credits

- Three.js examples and documentation
- Inspiration from spline and tube geometry demos

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
