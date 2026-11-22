# Air Racer 🏎️ — Hands-Free 3D Traffic Runner

Air Racer is an immersive, browser-based 3D highway traffic runner game played entirely hands-free through your webcam! Powered by **Three.js** for high-speed 3D rendering and **MediaPipe Hands** for real-time gesture recognition running client-side.

## 🚀 Live Demo

Play it live right in your browser:  
👉 **[https://noteforstudy1-tech.github.io/air-racer/](https://noteforstudy1-tech.github.io/air-racer/)**

> **Note**: For the best webcam tracking experience, ensure good lighting and allow camera permissions when prompted. Google Chrome or Microsoft Edge recommended.

---

## 🎮 How to Play & Controls

Air Racer supports three modes:
1. **Camera Drive** (Hands-free AI gesture control)
2. **Keyboard Drive** (Arrow keys / WASD)
3. **Demo Drive** (Watch AI autopilot)

### 🖐️ Hand Gesture Controls (Camera Mode)

Drive by positioning both hands in view of the camera:

| Gesture | Action | Description |
| :--- | :--- | :--- |
| **Left Open + Right Fist** | **Steer Left** | Steer your vehicle left between traffic lanes |
| **Left Fist + Right Open** | **Steer Right** | Steer your vehicle right between traffic lanes |
| **Both Fists** | **Brake** | Slow down to avoid sudden pileups |
| **Both Pinch** | **Boost** | Consume boost meter for supersonic speed |
| **Pinch (Either Hand) & Hold 1s** | **Pause / Resume / Restart** | Quick menu pause or instant restart after crash |

### ⌨️ Keyboard Controls

If you prefer playing with a keyboard or don't have a webcam handy:
- **Left Arrow / A**: Steer Left
- **Right Arrow / D**: Steer Right
- **Down Arrow / S**: Brake
- **Up Arrow / W / Space**: Boost
- **P / Esc**: Pause / Resume

---

## ✨ Features

- **Real-Time Hand Tracking**: Uses Google MediaPipe Hands running locally in your browser via WebAssembly and WebGL/GPU acceleration.
- **3D Highway Experience**: Dynamic Three.js scene with neon-lit retrofuturistic cityscapes, multiple highway lanes, and traffic cars.
- **Interactive HUD & Radar**: Live speedometer, score & distance tracker, rear/overhead radar, and gesture indicator chip.
- **Procedural Audio & Synthesizer**: Built-in sound effects, engine hum, radio stations, and crash audio using the Web Audio API.
- **Zero Dependencies / Client-Only**: Pure static single-page application — no servers, installation, or sign-up needed.

---

## 🛠 Local Setup

To run locally, clone the repository and open `index.html` in your browser (or serve with any static HTTP server):

```bash
git clone https://github.com/noteforstudy1-tech/air-racer.git
cd air-racer
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your web browser.

---

## 📜 Credits & License

- **Three.js**: [mrdoob/three.js](https://github.com/mrdoob/three.js) (MIT License)
- **MediaPipe Hands**: [Google LLC](https://developers.google.com/mediapipe) (Apache 2.0 License)
