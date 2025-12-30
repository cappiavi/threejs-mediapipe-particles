# 3D Interactive Particle System (Three.js + MediaPipe Hands)

Live Project: https://3ds-cappiavi.engr-khert.workers.dev/

This project is a single-file 3D interactive particle experience built with **Three.js** and **MediaPipe Hands**. It renders thousands of lightweight particles that dynamically form different 3D shapes while responding in real time to hand gestures detected via webcam.

## Author
**Khert Laguna Garde**  
GitHub: **cappiavi**

## Key Features

### Visuals
- Renders **up to 20,000 particles**
- Shapes supported:
  - Sphere
  - Heart
  - Cube
  - Spiral
- **Additive blending** for a glowing effect
- **Dark theme** environment

### Gesture-Based Interaction (via MediaPipe Hands)
- **Open Hand → Repel Mode**  
  Particles are pushed away from your hand
- **Closed Fist → Attract Mode**  
  Particles are pulled toward the center
- When no interaction occurs, particles **smoothly return** to their original positions using velocity + damping physics

### UI Controls
Built-in settings panel provides:
- Slider for **particle count**
- Slider for **force strength**
- Slider for **interaction radius**
- Buttons to **switch between shapes**

### Tech Stack
- **Three.js (ES Modules)**
- **MediaPipe Hands via CDN**
- Pure JavaScript — no build tools required
- Single-file implementation for simplicity

### Physics System
Each particle:
- Stores an original shape position
- Has velocity & damping
- Moves organically in response to forces
- Restores when interaction stops

---

This project demonstrates advanced WebGL rendering, real-time computer vision input, and physics-based animation — all inside a clean, minimal single-file setup.
