# 🚂 FlexxRail – Game-Engine für industrielle Simulationen

**Version:** Early Preview 0.1  
**Entwickler:** FlexxVision NGO  
**Codeumfang:** >250.000 Zeilen aus 45 Jahren Entwicklung

---

## 🧭 Projektübersicht

FlexxRail ist ein Demonstrator für unsere OpenGL-basierte Industrial Vision Engine.  
Ziel ist es, die Leistungsfähigkeit unserer Bildverarbeitungssoftware in komplexen 3D-Szenarien sichtbar zu machen – mit dynamisch generiertem Terrain, Gleisstrecken, fahrenden Lokomotiven und Lua-Scripting.

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

## 🖥️ Installation

```bash
Download: FlexxRailSetup.msi  
System: Windows 64 Bit  
Hinweis: Als Administrator ausführen oder außerhalb von Systemverzeichnissen installieren
