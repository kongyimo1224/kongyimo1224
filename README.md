<h1 align="center">Hi, I'm Yimo Kong 👋</h1>
<p align="center">
  <b>C++ / Graphics / Game Engine Programmer</b><br/>
  BSc (Hons) Computer Science in Real-Time Interactive Simulation · SIT × DigiPen Singapore
</p>

---

I build real-time systems: custom engines, renderers, editor tooling and game AI.
Most of my work is in **C++ and OpenGL**, with side trips into Unity, Unreal Engine and WebGL.

🎯 Open to graduate roles from 2028 in real-time simulation, graphics and C++ systems programming.

## ⭐ Featured work

### Bloody Good Curry — custom C++ 2D engine, editor & shipped game · [write-up](https://github.com/kongyimo1224/bloody-good-curry)
`C++` `OpenGL` `ImGui` `FMOD` `Emscripten` · 7-person team · Sep 2025 – Apr 2026

### ▶️ [Play it in your browser](https://bloodygoodcurry.netlify.app/)

<!-- assets/bgc.gif : 5–10 s gameplay clip + 3 s of the editor gizmo -->

- Primary author of the **render system**: game/editor viewports, camera, screen-to-world picking, multi-pass draw orchestration.
- **GPU-instanced sprite batching** → draw calls down **38% (250 → 156 per frame)** in the densest level.
- Fixed-timestep main loop, per-frame CPU profiler with in-game HUD.
- ImGui editor tools: transform gizmo with undo/redo, editor camera, sprite-sheet animation editor.
- Shipped as a Windows build and a WebAssembly/WebGL browser build — [playable online](https://bloodygoodcurry.netlify.app/).

### Flatland Bound — networked co-op puzzle game (solo) · [write-up](https://github.com/kongyimo1224/flatland-bound)
`C11` `OpenGL 3.3` `GLFW` `Cyclone DDS` · Sep – Oct 2026

- Two players see one 3D voxel world from perpendicular sides and can turn it to any angle; physics keeps running mid-turn.
- Client-side prediction with server reconciliation: input latency stays at one frame (17 ms) vs 135–318 ms without it.
- Event-driven, lock-free server (DDS waitsets, C11-atomic SPSC queues) cut idle CPU from 199% to 1.7%.
- Automated test harness drives both clients under emulated latency and packet loss.

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
🧭 **Tech Lead** · leading an 8-person team
`TypeScript` `Next.js` `Babylon.js` `MapLibre GL` · Sep 2026 – present

- Own architecture, milestone delivery and client communication for a 6-milestone industry engagement.
- Custom Babylon.js 3D city renderer sharing MapLibre GL's WebGL context: vector-tile streaming, Web Worker mesh building, spatial batching, culling, adaptive LOD.
- Explainable charger-ranking engine; 200+ automated tests; CI on Windows & Linux; Docker + Jenkins deployment.

### 四水归堂 “Four Waters Return to the Hall” — Tsinghua University School of Architecture × miHoYo competition
`Unreal Engine 5` `C++` `Python` `Blender` · 2026 · team of 3

- First-person puzzle game in a Huizhou courtyard house: ~8,700 lines of UE5 gameplay C++ covering interactions, four water puzzles and an era switch using a SceneCapture reflection and wipe transition.
- Lumen and Nanite lighting and geometry; Python scripts build the levels automatically.

## 🛠️ Tech

**Languages** · C++ · C · C# · Python · TypeScript · GLSL · SQL<br/>
**Graphics & engines** · OpenGL · GLFW/GLM · ImGui · Unreal Engine · Unity · Babylon.js · Blender<br/>
**Tools** · Git · CMake · Visual Studio · Linux/WSL · Docker · GitHub Actions · Jenkins

## 📫 Contact

📧 kongyimoo@gmail.com · 📍 Singapore · 🗣️ English, Mandarin
