# 🚂 FlexxRail – Game-Engine für industrielle Simulationen

**Version:** Early Preview 0.1  
**Entwickler:** FlexxVision NGO  
**Codeumfang:** >250.000 Zeilen aus 45 Jahren Entwicklung

---

## 🧭 Projektübersicht

FlexxRail ist ein Demonstrator für unsere OpenGL-basierte Industrial Vision Engine.  
Ziel: Die Leistungsfähigkeit unserer Bildverarbeitungssoftware in komplexen 3D-Szenarien sichtbar machen – mit dynamisch generiertem Terrain, Gleisstrecken, fahrenden Lokomotiven und Lua-Scripting.

---

## 🌍 Hauptfunktionen

- 🗺️ **Perlin-Terrain mit JetColor-Höhendarstellung**  
  Visualisierung über Shader & VBOs mit fünf Höhentexturen und Radar-Farbverläufen

- 🛤️ **Spline-Line Editor für Gleisverläufe**  
  Dynamische Gleisgenerierung mit 16-Punkte-Regelwerk und Echtzeit-Rendering

- 🚆 **Lokomotiv-Simulation mit Anhängern**  
  Grundlage für wirtschaftliche Szenarien (Kohle, Öl, Metall)

- 🧮 **Chunk-System & Frustum-Culling**  
  Optimiertes LOD-Management für hohe Frameraten (400–1000 FPS)

- 🌳 **Flora & Fauna via Geometrie-Shader** *(in Entwicklung)*  
  Terrain-basierte Umweltobjekte für visuelle Tiefe

- 🧵 **Lua-Scripting mit Debugger & Haltepunkten**  
  Echtzeit-Skripting zur Laufzeit mit Admin-Funktionen und Objektsteuerung

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

![FlexxRail Terrain](https://www.flexxvision.de/images/flexxrail_terrain.jpg)  
*Dynamisch generiertes Perlin-Terrain mit JetColor-Höhendarstellung*

![Spline Editor](https://www.flexxvision.de/images/flexxrail_spline_editor.jpg)  
*Spline-Line Editor zur Gleisverlegung*

![Lua Debugger](https://www.flexxvision.de/images/flexxrail_lua_debugger.jpg)  
*Lua-Scripting mit Haltepunkten und Echtzeitsteuerung*

*(Falls die Bilder nicht angezeigt werden, bitte sicherstellen, dass die URLs direkt auf `.jpg` oder `.png`-Dateien verweisen und öffentlich zugänglich sind.)*

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
