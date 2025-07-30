# Dynamic Aim

**Dynamic Aim** is a powerful, easy-to-use universal aimbot designed for Roblox. Built for performance, precision, and flexibility, it offers robust customization options for both gameplay enhancement and visual feedback. Whether you're looking for a smooth competitive edge or simply wish to tailor your experience, Dynamic Aim delivers a seamless and dynamic solution.

---

## ⚙️ Features

### 🎯 Aimbot System
- Toggleable aimbot functionality
- Adjustable targeting (e.g., `Head`, `Torso`)
- Field of View (FOV) visualization with configurable radius
- Target selection methods:
  - Closest to Mouse
  - Closest to Player
  - Lowest Health
- Range limitation and smoothing for natural movement
- Optional prediction and bullet drop simulation

### 🧍 Character Modifiers
- WalkSpeed and JumpPower adjustments
- Optional NoClip mode
- Gravity control for customized physics

### 🧠 Visual Enhancements
- ESP (Extra Sensory Perception) overlays
- Configurable highlight colors and tracer lines
- Rainbow mode for dynamic effects
- Support for friend filtering and inversion

---

## 🖥️ User Interface

Dynamic Aim comes with an intuitive, minimalistic UI powered by **Nebula Softworks UI Library**, ensuring ease of use without sacrificing functionality.

---

## 🔧 Configuration Example

```lua
local Aimbot = {
    Enabled = true,
    TargetPart = AimbotTargetPart.Head,
    FOVCircle = true,
    FOV = 150,
    Range = 1000,
    Smoothness = 0.5,
    Filtering = AimbotFiltering.ClosestToMouse,
    Prediction = true,
    BulletSpeed = 1500,
    BulletDrop = true,
    BulletDropAmount = 50,
}
