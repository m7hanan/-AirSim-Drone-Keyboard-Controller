# 🛸 AirSim Drone Keyboard Controller

A simple Python-based drone controller for **Microsoft AirSim** that allows you to control a simulated multirotor drone using just your keyboard.

---

## 🎯 Features

- Real-time keyboard control (W, A, S, D)
- Altitude adjustment (Z, X)
- Yaw control (Q, E)
- Takeoff and landing functions
- Emergency reset
- Modular code with support for further extension (e.g., reinforcement learning, CV)

---

## 🎮 Controls

| Key | Action              |
|-----|---------------------|
| W   | Move Forward        |
| S   | Move Backward       |
| A   | Move Left           |
| D   | Move Right          |
| Q   | Yaw Left            |
| E   | Yaw Right           |
| Z   | Move Down           |
| X   | Move Up             |
| T   | Takeoff             |
| L   | Land                |
| C   | Reset & Exit        |

---

## 🔧 Requirements

- Python 3.7+
- Microsoft AirSim (setup with Unreal/Unity)
- `pynput` Python package
- `airsim` Python client

Install dependencies:
```bash
pip install airsim pynput
```
demo youtube Link
https://youtu.be/ZrAF0K314kA?si=ivugrZk7QP7h58u5
