# 🎨 Hybrid Air Painter

> A high-performance, browser-based AR drawing board. Hand gestures drive the art; the mouse handles the precision.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Click_Here-blue?style=for-the-badge)](https://your-username.vercel.app/)

Hybrid Air Painter utilizes webcam-based hand tracking to let you draw in mid-air. It features a "Hybrid UI" that offloads complex tool selection to the physical mouse, and a Dual-State Power system to protect your device's CPU/battery when not actively drawing.

---

## ✨ Features

* **🤏 Gesture Drawing**: Powered by Google MediaPipe. Pinch your index finger and thumb together to draw smooth lines in thin air.
* **⚙️ Dual-State Engine**: 
  * **Hard Switch (Sleep Mode):** Completely turns off the camera and AI engine to save CPU and battery.
  * **Soft Switch (Pause Tracking):** Instantly pauses/resumes drawing without turning off the camera, keeping you in the flow.
* **🖌️ Dynamic Brush Controls**: Infinite native color picker and smooth thickness slider. The virtual cursor dynamically scales and changes color to match your current brush.
* **🧽 Smart Eraser**: Use hand gestures to wipe away lines, or **drag your mouse** to create a marquee selection box and click the eraser to delete a precise area.
* **⏪ Canvas Management**: One-click "Undo" for mistakes, and a global "Clear All" button to instantly reset the canvas.
* **🪶 Zero Dependencies**: 100% client-side HTML/JS. No backend, no installation.

---

## 🚀 How to Run

1. Clone this repository or download `index.html`.
2. Open `index.html` in any modern web browser.
3. **Allow camera access** when prompted.
4. Click **"🔌 启动系统 (Start Engine)"** to wake up the camera.
5. Click **"▶️ 开始创作 (Start Drawing)"** to activate hand tracking.
6. Pinch and move your hand to draw! Use your mouse to change tools on the left.

---

## 💡 Best Practices for Flawless Tracking

To overcome the physical limitations of standard webcams, please ensure:
* **Lighting:** Face a light source. **Do not** sit with a bright window behind you.
* **Background:** Use a clean, solid background. Avoid wearing clothes that match your skin tone.
* **Distance:** Keep your hand **0.5m to 1m** away from the camera.
* **Visibility:** Ensure your entire hand (including your wrist) is visible in the frame. Move at a smooth, moderate pace to avoid motion blur.

---

## 🛠️ Tech Stack
* **HTML5 Canvas** (2D Rendering)
* **Google MediaPipe Hands** (Real-time Kinematic Tracking)
* **Vanilla JavaScript** (Zero external UI frameworks).
