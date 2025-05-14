# Course Project: 3D Object Modeling in Three-Dimensional Space

## Topic: Modeling an Object in Three-Dimensional Space

**Educational Institution:** NON-PROFIT JOINT STOCK COMPANY "KARAGANDA TECHNICAL UNIVERSITY NAMED AFTER ABYLKAS SAGINOV", Department of Information and Computing Systems

**Discipline:** 3D-Modeling

**Year:** 2025

## Project Description

This repository contains a course project for the "3D-Modeling" discipline. The aim of the project is to develop a three-dimensional model of the "Qazaq Air" airline logo and create a short animated video based on it using Autodesk 3ds Max software.

The final video, approximately 2.5-3 minutes long, includes:
* An animated intro with the logo (approximately 7 seconds long).
* A scene of an airplane flying over a snowy mountain landscape with a snowfall effect.
* A scene of the airplane arriving at a branded airport.

The project demonstrates skills acquired during the course, including modeling, texturing, lighting and camera setup, animation creation, and final visualization (rendering).

## Structure of the Explanatory Note (Main Chapters)

### Introduction
* Relevance of 3D technologies in marketing and branding.
* Project goal: development of a 3D model of the "Qazaq Air" logo and creation of an animated video.
* Relevance, novelty, and practical significance of the project.

### 1. Problem Statement
Decomposition of the goal into the following tasks:
* Construction of 3D models of objects (logo, airplane, environment).
* Texturing of 3D models.
* Application of camera and light source models.
* Scene visualization.
* Scene animation.

### 2. Modeling in 3ds Max
* Overview of modeling techniques in 3ds Max (polygonal, spline, standard primitives, modifiers).
* **Modeling the Tu-154 Airplane:**
    * Using blueprints as references.
    * Modeling the fuselage from a Cylinder primitive with subsequent conversion to Editable Poly and application of TurboSmooth.
    * Modeling wings using Line and Extrude modifier, with Mirror for symmetry.
    * Creating side engines from Tube, Cylinder, Sphere primitives and applying Mirror.
    * Modeling vertical and horizontal stabilizers using Line, Extrude, and Mirror.
    * Creating the central air intake from a Cylinder primitive.
* **Modeling the 3D "Qazaq Air" Logo:**
    * Elements: central sphere (Sphere), rotating ring (Torus), text inscription "Qazaq Air" (TextPlus).
* **Modeling the Environment:**
    * Mountain fly-over scene: a pre-made 3D model of a snowy mountain was used.
    * Airport scene: main terminal with a control tower (with "QAZAQ AIR" inscription), an apron with LowPoly car models, auxiliary buildings, a large passenger terminal with jet bridges and airplane models, helipads, airfield (runways and taxiways), surrounding landscape (farm, hills, road), information billboard. Both custom-modeled elements and pre-made 3D models were used.

### 3. Texturing in 3ds Max
* Overview of texturing tools (Material Editor, Physical Material, Bitmap, UVW Mapping, Multi/Sub-Object).
* **Texturing the Tu-154 Airplane:**
    * Simplified approach: fuselage – yellow color, other elements – blue.
    * Cockpit windows – material with glass properties.
* **Texturing the Logo:**
    * Sphere – Earth planet texture (Bitmap).
    * Ring – solid blue color.
    * "Qazaq Air" inscription (Editable Poly): "Qazaq" – blue, "Air" – yellow.
* **Texturing the Snowy Mountain:** a pre-made texture was used (Bitmap).
* **Texturing the Airport Scene:**
    * Pavement (runways, taxiways, road) – asphalt textures with markings (Bitmap).
    * Surrounding area – grass, wheat field textures (Bitmap).
    * Farm elements (haystack, house, tractor) – pre-made textures, Multi/Sub-Object.
    * Airport buildings – glass, concrete, cladding panels, roofing materials; Multi/Sub-Object.
    * Transport and equipment (cars, helicopters, stairs, airplanes at the terminal) – Bitmap textures, pre-made textures, Qazaq Air livery.
    * Other elements (helipads, billboards) – metal materials, Bitmap.
* **Material Properties:** glass, metal, matte paint.

### 4. Application of Camera and Light Source Models in 3ds Max
* Overview of camera types (Target, Free, Physical Camera) and light sources (Standard, Photometric, Arnold Light, IBL, HDRI).
* Exposure Control (Physical Camera Exposure Control).
* **Lighting and Cameras for the Mountain Fly-over Scene:**
    * Lighting: HDRI map of a snowy landscape (Environment Map).
    * Exposure Control: Physical Camera Exposure Control (EV=9.0, White Balance: Shade 7000K, Image Control adjusted).
    * Camera: Target Camera, target linked to the airplane, FOV=45 degrees.
* **Lighting and Cameras for the Airport Scene:**
    * Lighting: HDRI map of a grassy island with hills (Environment Map).
    * Exposure Control: Physical Camera Exposure Control (EV=6.0, White Balance: Daylight 6500K, Image Control adjusted).
    * Camera: Target Camera, target linked to the airplane, FOV=45 degrees.

### 5. Visualization in 3ds Max
* Overview of the rendering process and render engines (Scanline, ART, Arnold, V-Ray, Corona).
* Visualization setup (Render Setup: resolution, frame range, output format).
* Rendering image sequences.
* **Selected Render Engine: Arnold**.
* **Visualization Parameters for Scenes:**
    * Scene 1 (Logo Animation, 7 sec): Full HD (1920x1080), 30 FPS, 210 frames, Arnold CPU, default settings.
    * Scene 2 (Mountain Fly-over, 30 sec): HD (1280x720), 30 FPS, 900 frames, Arnold CPU/GPU (50/50).
    * Scene 3 (Airport Scene, 1 min): HD (1280x720), 30 FPS, 1800 frames, Arnold GPU (80%)/CPU (20%).

### 6. Animation in 3ds Max
* Overview of 3D animation and its types (keyframe, path, parametric, simulation-based).
* Animation tools in 3ds Max (Time Slider, Auto Key, Set Key, Curve Editor, Controllers, Constraints, Particle Systems).
* **Logo Intro Animation (7 sec, 210 frames, Auto Key):**
    * Sphere: rotation around its axis (0-210 frames, 360 degrees).
    * Ring: scale change (pulsation).
    * "Qazaq Air" text: vertical movement from bottom to top.
    * Airplane: appearance from behind the sphere, fly-by, and exit from the frame.
* **Snowy Mountain Fly-over Animation (30 sec, 900 frames, Auto Key, particle system):**
    * Airplane: flight with turns and banking.
    * Snowfall effect: Snow particle system, linked to the camera.
    * Camera: tracking the airplane, then releasing the target for a wide shot of the mountains.
* **Airport Scene Animation (1 min, 1800 frames, Auto Key, Path Constraint):**
    * Airplane landing: descent, alignment, touchdown, rollout (Auto Key).
    * Airplane taxiing to the terminal: Path Constraint along a spline path.
    * Mobile stairs movement: Path Constraint along a spline path.
    * Camera animation: tracking the airplane, orbiting, then showing the billboard and the control tower with the logo.

### Conclusion
* Successful achievement of the set goal: creation of a 3D logo model and an animated video.
* Demonstration of the application of a wide range of Autodesk 3ds Max capabilities.
* Acquisition and consolidation of practical skills and theoretical knowledge in 3D modeling and animation.

---
