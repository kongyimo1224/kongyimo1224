<h1 align="center">Hi, I'm Yimo Kong 👋</h1>
<p align="center">
  <b>C++ / Graphics / Game Engine Programmer</b><br/>
  BSc (Hons) Computer Science in Real-Time Interactive Simulation · SIT × DigiPen Singapore
</p>

---

I build real-time systems: custom engines, renderers, editor tooling and game AI.
Most of my work is in **C++ and OpenGL**, with side trips into Unity, Unreal Engine and WebGL.

🎯 Looking for a **12-month internship (May 2027 – Apr 2028)** in game engine, graphics or C++ systems programming.

## ⭐ Featured work

### Bloody Good Curry — custom C++ 2D engine, editor & shipped game
`C++` `OpenGL` `ImGui` `FMOD` `Emscripten` · 7-person team · Sep 2025 – Apr 2026

<!-- assets/bgc.gif : 5–10 s gameplay clip + 3 s of the editor gizmo -->

- Primary author of the **render system**: game/editor viewports, camera, screen-to-world picking, multi-pass draw orchestration.
- **GPU-instanced sprite batching** → draw calls down **38% (250 → 156 per frame)** in the densest level.
- Fixed-timestep main loop, per-frame CPU profiler with in-game HUD.
- ImGui editor tools: transform gizmo with undo/redo, editor camera, sprite-sheet animation editor.
- Shipped as a Windows build and a WebAssembly browser build.

### Real-Time Rendering Portfolio
`C++` `OpenGL` `GLSL`

<!-- assets/rendering-grid.png : 3x3 grid of screenshots, one per technique -->

| Technique | Highlights |
|---|---|
| Deferred shading | G-buffer, normal mapping, many lights |
| Environment mapping | HDR cube maps, reflection & refraction |
| Ray casting / ray tracing | Shader-based scene intersection |
| Stylised | NPR toon shading, portal rendering, fog |
| CPU rasterizer | Barycentric rasterization, depth buffer, culling, per-pixel lighting, OBJ loading |

### Spatial Acceleration Structures
`C++`

- Top-down **BVH** and **SAH-sweep KD-tree** with closest-hit ray traversal, instrumented against brute force.

### CS Autobattler — tactical squad autobattler · [repo](https://github.com/elvisshengjie/CsAutobattler)
`Unity` `C#` · Jun 2026 – present · lead contributor

<!-- assets/autobattler.gif : squad executing a tactic -->

- Squad AI for sensing, target selection, role positioning and rotations.
- Influence maps, A* on a height-field grid, position reservations, high-ground cover scoring.
- TFT-style shop, unit merging and a 7-round roguelike campaign.

### ChargedUp — EV journey planner for industry client Upsight
## 🧭 Tech Lead · leading an 8-person team
`TypeScript` `Next.js` `Babylon.js` `MapLibre GL` · Sep 2026 – present

- Own architecture, milestone delivery and client communication for a 6-milestone industry engagement.
- Custom Babylon.js 3D city renderer sharing MapLibre GL's WebGL context: vector-tile streaming, Web Worker mesh building, spatial batching, culling, adaptive LOD.
- Explainable charger-ranking engine; 200+ automated tests; CI on Windows & Linux; Docker + Jenkins deployment.

### 借光成庭 “Borrowing Light” — Tsinghua University School of Architecture × miHoYo competition
`Unreal Engine` `Blender` `Revit` · 2026

- Explorable Chinese courtyard house built around borrowed light: day–night lighting through the open courtyard and an interactive well.

## 🛠️ Tech

**Languages** · C++ · C · C# · Python · TypeScript · GLSL · SQL<br/>
**Graphics & engines** · OpenGL · GLFW/GLM · ImGui · Unreal Engine · Unity · Babylon.js · Blender<br/>
**Tools** · Git · CMake · Visual Studio · Linux/WSL · Docker · GitHub Actions · Jenkins

## 📫 Contact

📧 kongyimoo@gmail.com · 📍 Singapore · 🗣️ English, Mandarin
