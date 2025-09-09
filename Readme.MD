# 🚂 FlexxRail – Game-Engine für industrielle Simulationen

**Version:** Early Preview 0.1  
**Entwickler:** FlexxVision NGO  
**Codeumfang:** >250.000 Zeilen aus 45 Jahren Entwicklung

---

## 🧭 Projektübersicht

FlexxRail ist ein Demonstrator für unsere OpenGL-basierte Industrial Vision Engine.  
Ziel: Die Leistungsfähigkeit unserer Bildverarbeitungssoftware in komplexen 3D-Szenarien sichtbar machen – mit dynamisch generiertem Terrain, Gleisstrecken, fahrenden Lokomotiven und Lua-Scripting.

Im Zentrum steht ein riesiges 3D-Terrain, das mittels Perlin-Noise generiert und über Shader und VBOs gerendert wird. Mit fünf Höhentexturen und Farbverläufen aus dem JetColor-Farbraum visualisieren wir die Topografie wie in einem Radarbild.

---

## 🌍 Hauptfunktionen

- 🗺️ Perlin-Terrain mit JetColor-Höhendarstellung  
- 🛤️ Spline-Line Editor für Gleisverläufe  
- 🚆 Lokomotiv-Simulation mit Anhängern  
- 🧮 Chunk-System & Frustum-Culling  
- 🌳 Flora & Fauna via Geometrie-Shader *(in Entwicklung)*  
- 🧵 Lua-Scripting mit Debugger & Haltepunkten  

---

## 🎮 Tastaturbelegung & Steuerung

| Aktion | Taste |
|--------|-------|
| Kamera entlang Gleis | F2 |
| Lokomotiv-Tracking | F3 |
| Gleis optimieren | O |
| Gleis löschen | Backspace |
| Dot löschen | Entf |
| Lua-Debugger öffnen | F11 |
| Haltepunkt setzen/löschen | F9 |
| Fortsetzen | F5 |
| Bewegung | W A S D / Pfeiltasten |
| Blickrichtung ändern | Mittlere Maustaste |
| Radar aktivieren | Maus bewegen |
| Radar verschieben | SHIFT + Linksklick |
| Radar zoomen | CTRL + Mausrad |

---

## 📁 Projektstruktur

- `/Engine` – Rendering & Logik  
- `/LuaScripts` – Beispielskripte & Admin-Funktionen  
- `/Assets` – Texturen, Meshes, Shader  
- `/Docs` – Dokumentation & Tastaturbelegung  
- `/User` – User-Verwaltung (Admin0–Admin3)

---

## 🖥️ Installation & Download

👉 [FlexxRailSetup.msi herunterladen](https://www.flexxvision.de/flexxrail.html#download)  
**System:** Windows 64 Bit  
**Hinweis:** Als Administrator ausführen oder außerhalb von Systemverzeichnissen installieren, damit Einstellungen gespeichert werden können.

---

## 📸 Screenshots

![Splash Screen](https://www.flexxvision.de/media/images/splash-large.jpg)  
*Startbildschirm mit Terrain-Visualisierung*

![Gleisverlegung](https://www.flexxvision.de/media/images/flexxrail_tracks.jpg)  
*Spline-Line Editor zur Gleisverlegung*

![Lua Debugger](https://www.flexxvision.de/media/images/flexxrail_lua_debugger.jpg)  
*Lua-Scripting mit Haltepunkten und Echtzeitsteuerung*

![Lokomotive & Terrain](https://www.flexxvision.de/media/images/flexxrail_train.jpg)  
*Lokomotiv-Simulation auf dynamischem Terrain*

---

## 🤝 Mitmachen

Dieses Projekt ist Teil einer gemeinnützigen NGO.  
Wir freuen uns über Feedback, Ideen und Mitentwickler – ob für Code, Design oder Dokumentation.

---

## 🔗 Weitere Informationen

👉 [Offizielle Projektseite mit Dokumentation & Details](https://www.flexxvision.de/flexxrail.html)  
👉 [Kontaktformular für Rückfragen oder Kooperationen](https://www.flexxvision.de/kontakt.html)

---

© 2025 FlexxVision NGO – OpenGL Industrial Vision Engine
