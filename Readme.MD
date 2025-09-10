# FlexxRail – Game Engine for Industrial Simulations
Visit the MainPage of FlexxRail (https://www.flexxvision.de/flexxrail.html)

**Version:** Early Preview 0.1  
**Developer:** FlexxVision  
**Codebase:** >250,000 lines from 45 years of development

---

![Splash Screen](https://www.flexxvision.de/media/images/splash-large.jpg)  
*Startup screen with terrain visualization*

## Project Overview

FlexxRail is a demonstrator for our OpenGL-based Industrial Vision Engine.  
Goal: To showcase the capabilities of our image processing software in complex 3D scenarios – featuring dynamically generated terrain, railway tracks, moving locomotives, and Lua scripting.

At the core is a vast 3D terrain generated via Perlin noise and rendered using shaders and VBOs. With five elevation textures and gradients from the JetColor color space, we visualize topography similar to radar imaging.

---

## ⚙️ Key Features

- Perlin terrain with JetColor elevation visualization  
- Spline-line editor for track layout  
- Locomotive simulation with wagons  
- Chunk system & frustum culling  
- Flora & fauna via geometry shaders *(in development)*  
- Lua scripting with debugger & breakpoints  

---

## 🎮 Keyboard Controls

| Action | Key |
|--------|-----|
| Camera along track | F2 |
| Locomotive tracking | F3 |
| Optimize track | O |
| Delete track | Backspace |
| Delete dot | Delete |
| Open Lua debugger | F11 |
| Toggle breakpoint | F9 |
| Resume execution | F5 |
| Movement | W A S D / Arrow keys |
| Change view direction | Middle mouse button |
| Activate radar | Move mouse |
| Move radar | SHIFT + Left click |
| Zoom radar | CTRL + Mouse wheel |

---

## Project Structure

- `/Engine` – Rendering & logic  
- `/LuaScripts` – Sample scripts & admin functions  
- `/Assets` – Textures, meshes, shaders  
- `/Docs` – Documentation & key mappings  
- `/User` – User management (Admin0–Admin3)

---

## 🖥️ Installation & Download

[Download FlexxRailSetup.msi](https://www.flexxvision.de/flexxrail.html#download)  
**System:** Windows 64-bit  
**Note:** Run as administrator or install outside system directories to ensure settings are saved.

---

## 📸 Screenshots

![Theme coal Ore](https://www.flexxvision.de/media/images/theme-large.jpg)  
*Theme: Coal Ore*

![Theme flora fauna](https://www.flexxvision.de/media/images/theme2-large.jpg)  
*Theme: Flora & Fauna*

![TrackEdit](https://www.flexxvision.de/media/images/terraintrackrendered-large.jpg)  
*Track line editor*

![Lua Debugger](https://www.flexxvision.de/media/images/terrainlua-large.jpg)  
*Lua scripting with breakpoints and real-time control*

![Locomotive & Terrain](https://www.flexxvision.de/media/images/lokfollow-large.jpg)  
*Locomotive simulation on dynamic terrain*

---

## Get Involved

We welcome feedback, ideas, and contributors – whether for code, design, or documentation.

---

## 🔗 More Information

[Official project page with documentation & details](https://www.flexxvision.de/flexxrail.html)  
[Contact form for inquiries or collaborations](https://www.flexxvision.de/kontakt.html)

---

© 2025 FlexxVision – OpenGL Industrial Vision Engine





