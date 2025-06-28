# Verbarex Engine

Verbarex Engine is a lightweight, in-browser 3D game engine and editor built with modern web technologies. It provides a familiar and intuitive interface for creating and manipulating 3D scenes directly in your web browser. The engine features a real-time editor with a classic layout, including a scene hierarchy, an asset browser, and a detailed inspector panel for manipulating object properties.

This project demonstrates the power of JavaScript libraries like Three.js and Cannon.js to create interactive 3D experiences on the web. It's a great starting point for anyone interested in web-based game development, 3D rendering, and physics simulations.

![Verbarex Engine Screenshot] [img]https://i.imgur.com/fBVyQhW.png[/img]

---

## ✨ Features

* **Interactive 3D Viewport:** A real-time rendering canvas where you can view and interact with your scene.
* **Editor & Play Mode:**
    * **Editor Mode:** A full suite of tools for scene creation. Use the free-fly camera to navigate, and select and manipulate objects.
    * **Play Mode:** Instantly switch to a first-person perspective to test and play your scene, with physics-based interactions.
* **Scene Hierarchy:** A tree view that displays all objects in the scene, allowing for easy selection and organization.
* **Inspector Panel:** View and edit the properties (Transform: position, rotation, scale) of any selected object in real-time.
* **Transformation Gizmos:** Standard move, rotate, and scale tools to precisely manipulate objects in the 3D space. Keyboard shortcuts (`W`, `E`, `R`) are available for quick tool switching.
* **Physics Simulation:** Powered by Cannon.js, the engine supports rigid body dynamics, gravity, and basic collisions. You can pick up and throw objects in Play Mode.
* **Asset Browser:** A mock-up panel for organizing project assets like models, textures, and materials.
* **Modern UI:** A clean, dark-themed, and responsive user interface built with Tailwind CSS.

---

## 🛠️ Technologies Used

* **Rendering:** [**Three.js**](https://threejs.org/) - A powerful and comprehensive 3D library for creating and displaying animated 3D computer graphics in a web browser.
* **Physics:** [**Cannon.js**](https://github.com/schteppe/cannon.js) - A lightweight and capable 3D physics engine for the web.
* **Styling:** [**Tailwind CSS**](https://tailwindcss.com/) - A utility-first CSS framework for rapidly building custom user interfaces.
* **Language:** **HTML5 / CSS3 / JavaScript (ES6+)**

---

## 🚀 How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/verbarex-engine.git](https://github.com/your-username/verbarex-engine.git)
    ```
2.  **Open `index.html`:**
    * Simply open the `index.html` file in a modern web browser (like Chrome, Firefox, or Edge). There are no build steps required as all dependencies are loaded via CDNs.

### Editor Controls

* **Select Object:** Click on an object in the viewport or in the Scene Hierarchy.
* **Activate Fly Camera:** Click on an empty area in the viewport.
* **Fly Camera Movement:**
    * **Move:** `W`, `A`, `S`, `D`
    * **Fly Up/Down:** `E`, `Q`
    * **Look:** Move the `MOUSE`
* **Exit Fly Camera:** Press `ESC`.
* **Transform Tools:**
    * **Move:** `W`
    * **Rotate:** `E`
    * **Scale:** `R`

### Play Mode Controls

* **Enter/Exit Play Mode:** Click the **Play/Stop** button or press `Ctrl + P`.
* **Movement:** `W`, `A`, `S`, `D`
* **Jump:** `SPACE`
* **Look:** Move the `MOUSE`
* **Interact:**
    * **Pick Up Object:** `Left Click` on a nearby throwable object.
    * **Throw Object:** `Left Click` again while holding an object.
* **Exit Play Mode:** Press `ESC`.
