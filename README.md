# VOID — 3D Visualizer & Light Testing Environment

**VOID** is a high-performance, browser-based utility designed for the rapid previewing and lighting calibration of 3D models. Built specifically for developers working within the **Three.js** ecosystem, VOID eliminates the friction of opening heavy DCC software like Blender or spinning up local development servers just to verify model integrity, scale, and material response.

---

### ✦ Core Functionality

The platform provides a "dark-room" environment to stress-test **PBR (Physically Based Rendering)** materials under various lighting conditions before they are integrated into a production codebase.

* **Instant Interaction:** Full drag-and-drop support for `.GLB` and `.GLTF` files.
* **Zero-Latency Rendering:** Real-time feedback powered by Three.js `r128`.
* **Dynamic Lighting Suite:** Integrated controls for Ambient, Key, and Fill lights with HEX color support.
* **Cinematic Presets:** One-click application of *Studio*, *Neon*, and *Golden Hour* lighting profiles.
* **Post-Processing:** Built-in ACES Filmic tone mapping and exposure control for high-fidelity visualization.

---

### 🛠 Technical Specifications

| Feature | Implementation |
| :--- | :--- |
| **Engine** | Three.js (WebGL 2.0) |
| **Loader** | GLTFLoader with auto-center and normalization |
| **Controls** | OrbitControls (Damping enabled) |
| **Shadows** | PCF Soft Shadow Maps |
| **Environment** | PMREM Generated IBL (Image Based Lighting) |
| **Security** | 100% Client-side (Files never leave the browser) |

---

###  Usage Guide

1.  **Load:** Drop your model directly onto the hero viewport or use the file picker ring.
2.  **Navigate:** * **Rotate:** Left Click + Drag
    * **Zoom:** Scroll Wheel
    * **Pan:** Right Click + Drag
3.  **Calibrate:** Access the **Lighting Panel** (bottom-right) to adjust intensities and colors.
4.  **Validate:** Ensure the model's scale and normals are correct before exporting for production.

---

###  Design Philosophy

VOID utilizes a **Minimalist Brutalist** aesthetic. By using a high-contrast palette (**#d4ff00** accent on **#080808** background) and a monospaced typographic hierarchy, the interface stays out of the way of the creative process while maintaining a professional, technical feel.

---
## 👤 Author
### Harshit Bhatt (Cykikz)

"Built because opening Blender every time is overkill. This is a quick sanity check in the browser."

No rights reserved. This project is open-source and intended for the developer community.
