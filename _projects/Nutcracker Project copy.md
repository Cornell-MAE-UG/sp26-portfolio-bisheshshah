---
layout: project
title: Additional Question 2
description: Homework Question
technologies: Textbook
image: /assets/images/Nutcracker.jpg
---

Problem Statement & Objective (Find):
Design a 3D CAD model of a traditional nutcracker soldier figurine using only primitive solid bodies, suitable for 3D printing or further modification in Autodesk Fusion 360.2. 

Constraints & Input Parameters (Given): 
Geometry limited to cylinders, spheres, and rectangular extrusions
Model must stand upright on a flat base
Target height ~17 cm (decorative figurine scale)
No overhangs exceeding 45° from vertical
Static model (no moving jaw mechanism)
Built along the Z-axis from Z=0, centred at X=0, Y=0
All units in centimetres

Approach:
The model was built bottom-up in anatomical order, base, legs, pelvis, torso, belt, chest, arms, hands, neck, head, facial features, hat. Each part is a named primitive solid, mirrored symmetrically about the XZ plane where applicable. Cylinders approximate the lathe-turned wooden forms of real nutcrackers; the head and hands are spheres; arms are simplified rectangular boxes. The Fusion 360 Python API was used to script every body parametrically, making the model easy to rescale.

Discussion on Usability:
The primitive-body approach keeps the model clean, watertight, and 3D-print-ready with no non-manifold geometry. Each body can be edited or deleted independently. Limitations include simplified box arms (vs. rounded), no functional jaw mechanism, and minimal facial detail. To finalise for printing, all bodies should be merged using Modify → Combine → Join in Fusion 360.
