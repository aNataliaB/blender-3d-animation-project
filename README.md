# 3D Mechanical Carousel Animation & Render
![Blender Version](https://img.shields.io/badge/Blender-5.0%2B-orange?logo=blender&logoColor=white)
A comprehensive 3D computer graphics project featuring a complex musical carousel (music box), designed, modeled, animated, and composed entirely by myself using Blender. This project demonstrates advanced hard-surface polygon modeling, mechanical animation, rigid body physics, and high-fidelity rendering.

## Live Video Demonstration
The final high-resolution animation render can be viewed directly in this repository:
**[Watch the Animation Render (`animacja.mp4`)](animacja.mp4)**

## Project Overview & Technical Execution
The primary objective of this project was to execute the full 3D production pipeline, with a heavy emphasis on custom asset creation and mechanical motion mechanics.

### 1. Complete Custom Modeling (The Musical Carousel)
* **Hard-Surface Modeling:** Designed and built the entire musical carousel/music box completely from scratch. This involved creating intricate ornamental details, mechanical gears, structural pillars, and the main rotating pavilion framework.
* **Topology Optimization:** Maintained clean edge loops, optimized polygon distribution, and precise shading smooth groups to ensure flawless subsurface division and reflection behavior.
* **Material & Shader Assignment:** Crafted custom PBR shading networks (specular, roughness, and metallic channels) specifically tuned to give the carousel realistic brass, painted wood, and glossy enamel characteristics.

### 2. Mechanical Animation & Rigid Body Dynamics
* **Rotational Mechanics:** Keyframed the complex, multi-axis mechanical rotation of the carousel to mimic a real-world wind-up music box, ensuring synchronous movement between the base, top canopy, and secondary animated elements.
* **Physics Integration:** Configured active and passive rigid body physics simulations to achieve realistic object weight, collision parameters, and organic physical interactions within the scene.

### 3. Cinematic Camera Rigging & Path Tracking
* **Path Constraints:** Implemented an independent camera rig constrained to a custom Bezier curve to capture sweeping, smooth cinematic angles of the asset.
* **Dynamic Focus:** Utilized tracking constraints mapped directly to the carousel's focal points, paired with real-time Depth-of-Field (DoF) adjustments to isolate the main model and create a professional, photographic blur effect.

### 4. Production Rendering Pipeline (Cycles)
* **Lighting Composition:** Designed a custom studio multi-point light setup (using spot and area lights) to accentuate the complex shapes, curves, and metallic reflections of the modeled carousel.
* **Cycles Optimization:** Fine-tuned the physically-based Cycles engine with strict noise thresholds and adaptive sampling to prevent render fireflies, outputting a crisp 60fps video container (`animacja.mp4`) via the OpenImageDenoise compositor pipeline.

## Repository Structure
* `projekt_wiecej.blend` - The full production file containing packed resources, custom geometry meshes, shader nodes, and the animation timeline.
* `animacja.mp4` - The final high-fidelity video render.

## Asset Credits & External Resources
Every core asset—specifically the entire mechanical carousel model, its animation, lighting, camera rigs, and render settings—was **conceptualized and executed 100% independently by me**. To complete the final environmental presentation, the following background props were utilized:

* **3D Table Model:** Sourced from the internet. [Access Source Link Here](https://sketchfab.com/3d-models/gothic-coffee-table-8d9b4bcb7297458b90fc24df496588ab)
* **Environment Background:** Sourced from the internet. [Access Source Link Here](https://unsplash.com/photos/a-fancy-living-room-with-a-fancy-rug-af3F3ZTaUwA)
