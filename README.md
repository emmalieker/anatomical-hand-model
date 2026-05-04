# Anatomically Accurate Rigged & Animated Hand Model

<p align="center">
  <img src="assets/renders/turntable.gif" alt="Turntable animation of the rigged hand model" width="480">
</p>

<p align="center">
  <a href="https://www.turbosquid.com/3d-models/human-hand-anatomically-accurate-rigged-and-animated-with-skin-texture-3d-model-2564269">
    <img src="https://img.shields.io/badge/Download_on-TurboSquid-FF6B00?style=for-the-badge" alt="Download on TurboSquid">
  </a>
  <img src="https://img.shields.io/badge/Made_with-Blender_4.5+-E87D0D?style=for-the-badge&logo=blender&logoColor=white" alt="Made with Blender">
  <img src="https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey?style=for-the-badge" alt="License: CC BY-NC 4.0">
</p>

---

A fully rigged and animated human hand model built in Blender with **anatomically correct joint rotation ranges** and **realistic dual-scale skin texturing**. Designed for real-time XR applications, scientific visualization, and motion-capture research.

## Pose Presets

<p align="center">
  <img src="assets/renders/poses_overview.png" alt="All pose presets: OK, neutral, flat, point, fist" width="720">
</p>

Five pose presets created with Sakura Poselib: OK gesture, neutral, flat, point, and fist — each constrained to anatomically plausible joint angles.

## Rigging

The armature consists of 21 bones covering individual finger joints (DIP, PIP, MCP), metacarpals, thumb CMC, and wrist. Joint rotation limits for flexion, extension, abduction, and adduction are constrained per bone to match the physiological range of motion of a human hand, meaning the rig **cannot be posed into physically impossible configurations**.

<p align="center">
  <img src="assets/rig/rig_ok_gesture.png" alt="21-bone FK armature in OK gesture pose" width="400">
  &nbsp;&nbsp;
  <img src="assets/rig/rig_neutral.png" alt="FK armature in neutral pose" width="400">
</p>

## Topology & UV Layout

Clean tri-dominant mesh (5,790 triangles / 3,007 vertices) optimized for real-time rendering and smooth deformation under all poses. Non-overlapping UV unwrap for artifact-free texturing.

<p align="center">
  <img src="assets/wireframe/wireframe_seams.png" alt="Wireframe with UV seams" width="280">
  &nbsp;&nbsp;
  <img src="assets/wireframe/wireframe_overlay.png" alt="Wireframe mesh overlay" width="280">
  &nbsp;&nbsp;
  <img src="assets/uv/uv_layout.png" alt="UV layout — non-overlapping unwrap" width="280">
</p>

## Features

- **21-bone FK armature** with anatomically correct joint limits
- **Realistic skin texture** with dual-scale mixing to counteract tiling
- **Animated** with multiple pose presets (via Sakura Poselib)
- **Clean topology** — 5,790 tris / 3,007 verts, optimized for real-time
- **Proper weight painting** for natural skin deformation across all poses
- **Non-overlapping UV unwrap** for clean texturing
- **No AI-generated content** — fully hand-modeled, hand-rigged, and hand-textured

## Technical Specifications

| Property | Value |
|---|---|
| Polygons | 5,790 tris |
| Vertices | 3,007 |
| Bones | 21 |
| Rigging | Forward Kinematics (FK) |
| Texture | Dual-scale skin mix |
| Native format | `.blend` (Blender 4.5 LTS) |
| Export formats | `.glb` / `.fbx` |

## Compatibility

- **Blender** 4.5+ (native)
- **Unity** (via FBX/GLB import)
- **Unreal Engine** (via FBX/GLB import)
- **WebXR / Three.js** (native GLB support)

## Use Cases

- VR/AR hand interaction & gesture visualization
- Medical and scientific illustration
- Biomechanics & neuroscience research
- Motion capture data visualization
- Game development
- Animation reference & digital twin applications

## Repository Structure

```
├── README.md
├── LICENSE
├── assets/
│   ├── renders/            # Turntable GIF & pose overview
│   ├── rig/                # Armature visualization
│   ├── wireframe/          # Topology & mesh views
│   └── uv/                 # UV layout
├── exports/
│   └── hand_model.glb      # Ready-to-use export
└── blender/
    └── hand_model.blend     # Source Blender file
```

## Getting Started

1. **Quick use:** Download `exports/hand_model.glb` and import into your engine of choice.
2. **Edit the rig:** Open `blender/hand_model.blend` in Blender 4.5+.
3. **Download:** [Get the model on TurboSquid](https://www.turbosquid.com/3d-models/human-hand-anatomically-accurate-rigged-and-animated-with-skin-texture-3d-model-2564269).

## License

This work is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).  
Free for personal and academic use. Attribution required.

**Attribution:**  
> 3D Rigged Hand Model © 2026 Emma L. D. Lieker

## Author

**Emma L. D. Lieker**  
[GitHub](https://github.com/emmalieker) · [TurboSquid](https://www.turbosquid.com/Search/Artists/Do_Neuroscience)
