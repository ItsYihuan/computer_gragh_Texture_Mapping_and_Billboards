# 🚁 OpenGL Helicopter Simulation

This is a C/OpenGL-based interactive 3D simulation of a helicopter, supporting camera control, dynamic lighting, texture switching, fog effects, and more.

> ✅ No build needed — just download the `.exe` and `.dll`, and run!

---

## 🎮 Demo Overview

An interactive 3D environment that allows you to:
- Move and rotate a helicopter in space
- Dynamically control camera angles, lighting sources, and fog
- Apply texture mapping and material changes
- Observe transformations and shading in real-time

---

## 🧱 How to Run

1. Download the repository or ZIP.
2. Go to the `bin/` folder.
3. Run `helicopter.exe` (Make sure the accompanying `.dll` files are present in the same directory).
4. Use keyboard inputs to control movement, lighting, and effects.

---

## 🎛️ Controls

### 🚁 Helicopter Movement
| Key | Action |
|-----|--------|
| `f` | Move forward |
| `b` | Move backward |
| `u` | Move upward |
| `d` | Move downward (stops at ground level) |
| `r` | Rotate clockwise |
| `R` | Rotate counterclockwise |
| `t` | Tilt up |
| `T` | Tilt down |
| `v` | Turn direction |
| `s` | Takeoff |
| `l` | Land |

---

### 🧭 Viewpoint Controls
| Key | Action |
|-----|--------|
| `y / Y` | Pan up/down |
| `h / H` | Pan left/right |
| `n / N` | Zoom in/out |
| `a / A` | Pitch left/right |
| `z / Z` | Yaw left/right |
| `q / Q` | Roll left/right |
| `1`     | Cycle camera view (multiview mode) |

---

### 🌙 Light Position Control
| Key | Action |
|-----|--------|
| `w` | Rotate moon light |
| `k / K` | Move spotlight forward/backward |

---

### 🎨 Light Color Toggle
| Key | Light Type |
|-----|-------------|
| `x` | Directional light color (Red → Blue → Green → White) |
| `e` | Point light color (Red → Blue → Green → White) |
| `p` | Spotlight color (Red → Blue → Green → White) |

---

### 💡 Light On/Off
| Key | Light Type |
|-----|------------|
| `5` | Toggle directional light |
| `6` | Toggle point light |
| `7` | Toggle spotlight |

---

### 🔆 Light Intensity & Properties
| Key | Action |
|-----|--------|
| `m / M` | Increase/decrease spotlight intensity |
| `g / G` | Increase/decrease directional light intensity |
| `i / I` | Increase/decrease point light intensity |
| `o / O` | Change spotlight exponent |
| `8 / 9` | Adjust spotlight angle |
| `Space` | Toggle shading model |

---

### 🧱 Texture Mapping
| Key | Action |
|-----|--------|
| `2` | Change ground texture |
| `3` | Pause billboard movement |
| `[` / `]` | Toggle texture mapping on/off |

---

### 🌫 Fog Effect
| Key | Action |
|-----|--------|
| `.` | Toggle fog |
| `;` | Change fog mode (Linear → Exp → Exp2) |
| `=` | Change fog color (Yellow → Blue → Red) |
| `- / +` | Decrease/increase fog density |

## 🛠 Tech Stack
- C 
- OpenGL
- GLUT (FreeGLUT or similar)
