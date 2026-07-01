✋ AI Hand Tracking Particle Visualizer

A real-time interactive visualization that combines MediaPipe Hand Tracking with Three.js to create an AI-powered particle experience controlled entirely by hand gestures.

"Status" (https://img.shields.io/badge/Status-Experimental-success)
"JavaScript" (https://img.shields.io/badge/JavaScript-ES6-yellow)
"Three.js" (https://img.shields.io/badge/Three.js-WebGL-blue)
"MediaPipe" (https://img.shields.io/badge/MediaPipe-AI-orange)

🚀 Overview

This project explores the intersection of Computer Vision, Artificial Intelligence, and 3D Graphics Rendering.

Using your webcam, the application detects hand landmarks in real time using Google MediaPipe Tasks Vision and maps those movements to a dynamic Three.js particle system, creating an interactive AI-driven visual experience.

When a hand is detected:

- ✋ Particle system follows hand movement
- 🟢 Particle color changes dynamically
- ⚡ Motion interpolation creates smooth tracking
- 🎨 Real-time visual feedback enhances interaction

---

✨ Features

- 🎯 Real-time hand tracking using MediaPipe
- 🌐 Browser-based AI inference
- ✨ Interactive 3D particle visualization
- 🎥 Live webcam integration
- ⚡ GPU-accelerated processing
- 🔍 Built-in debug console overlay
- 📱 Lightweight and dependency-free backend
- 🎮 Smooth particle interpolation

---

🛠️ Tech Stack

Technology| Purpose
JavaScript (ES6)| Core logic
Three.js| 3D rendering
MediaPipe Tasks Vision| Hand landmark detection
WebGL| Hardware acceleration
HTML/CSS| User interface

---

🧠 How It Works

Webcam Feed
      ↓
MediaPipe Hand Detection
      ↓
Extract Hand Landmarks
      ↓
Convert Coordinates
      ↓
Three.js Particle System
      ↓
Real-Time Interactive Visualization

The application continuously:

1. Captures frames from the webcam.
2. Runs MediaPipe hand landmark detection.
3. Extracts wrist coordinates.
4. Maps hand positions into 3D space.
5. Animates the particle system smoothly.

---

📸 Current Capabilities

✅ Hand detection

✅ Real-time particle movement

✅ Dynamic color transitions

✅ GPU acceleration

✅ Debug monitoring console

---

🚀 Future Improvements

- 🌌 Particle explosion effects
- 🌀 Gesture-based animations
- 🎵 Audio-reactive particles
- 🤚 Multi-hand support
- 🔥 Particle trails
- 🌈 Dynamic shaders
- 🧩 Gesture recognition system
- 🥽 WebXR/VR support

---

▶️ Running the Project

«This project cannot run using the "file://" protocol.»

Option 1 — VS Code Live Server

Right Click → Open with Live Server

Option 2 — Python HTTP Server

python -m http.server 8000

Then open:

http://localhost:8000

---

📂 Project Structure

project/
│
├── index.html
├── README.md
└── assets/

---

🎯 Learning Outcomes

This project helped explore:

- Computer Vision fundamentals
- MediaPipe Tasks API
- Real-time browser AI
- WebGL rendering
- Three.js scene management
- Animation loops
- Coordinate system mapping
- Interactive visualization techniques

---

📜 License

This project is developed for educational and experimental purposes.

---

⭐ If you found this project interesting, consider giving it a star.
