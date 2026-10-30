# ️ Simple 3D DevBoard Designer

A lightweight, browser-based 3D PCB layout tool built with Three.js and vanilla JavaScript. No heavy CAD software, no installations just open the HTML file and start designing.
## Features

-   **Real-time 3D Visualization:** Drag, drop, and rotate components on a realistic PCB with soft shadows and procedural copper traces.
-   **Interactive Component Library:** 12+ components including MCUs, LEDs, pin headers, buzzers, and sensors.
-   **Smart Grid Snapping:** Components automatically snap to a 5mm grid for perfect alignment.
-   **Dynamic Properties Panel:** Adjust board dimensions, component colors, and rotation in real-time.
-   **Import/Export:** Save your designs as JSON and reload them later.
-   **Zero Dependencies:** Runs entirely in the browser. No Node.js, no build steps, no frameworks.

## How to Run

You do not need to install anything. Simply follow these steps:

1.  Clone this repository:
    ```bash
    git clone https://github.com/christiansamuelbakti-a11y/SIMPLE-3D-DEVBOARD-DESIGNER.git
    ```
2.  Open the project folder and double-click `index.html`.
3.  The designer will open in your default web browser.

> **💡 Tip:** For the best experience, use Chrome, Firefox, or Edge. If you are developing locally, consider using the "Live Server" extension in VS Code to avoid CORS issues when loading textures.

## Controls

| Action | Control |
| :--- | :--- |
| Place Component | Left Click on Board |
| Select Component | Left Click on Component |
| Rotate Camera | Right Click + Drag |
| Pan View | Middle Click + Drag |
| Zoom | Scroll Wheel |
| Undo | Ctrl + Z |
| Reset View | R Key |

## Tech Stack

-   **Three.js (r128):** For 3D rendering, raycasting, and scene management.
-   **Vanilla JavaScript:** State management, UI logic, and JSON serialization.
-   **CSS Grid & Flexbox:** For the responsive, app-like interface layout.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you have ideas for new components, better snapping logic, or UI improvements.
