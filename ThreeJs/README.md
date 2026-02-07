# Learning ** Three.js **

# 🧊 Three.js Hello World

A minimal starter project to render a 3D rotating cube in the browser using [Three.js](https://threejs.org/). This project demonstrates the core pillars of 3D web development: Scenes, Cameras, Renderers, and Animation Loops.

---

## Getting Started

Because this project uses **JavaScript Modules (ESM)** and **Import Maps**, modern browsers require the file to be served over `http://` or `https://` rather than `file://` to avoid CORS security errors.

### 🛠️ Prerequisites
You need a local development server. Choose the one that fits your setup:

* **VS Code:** Install the **Live Server** extension. Right-click `index.html` and select "Open with Live Server."
* **Node.js:** Run `npx serve` in your project folder.
* **Python:** Run `python -m http.server` in your project folder.

---

## 📂 Project Structure
```text
├── index.html   # The main entry point (contains Scene, Camera, and Renderer)
└── README.md    # Project documentation