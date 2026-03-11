---
layout: project
title: Nutcracker Design / Additional Question 2
description: Below, I have attached my original nut cracker design and additional question 2.
technologies: Pen and Paper
image: /assets/images/additional.jpg
---

From the photo:
1. Problem Statement & Objective (Find)
Design a lever-based nutcracker capable of cracking a macadamia nut using human grip strength, determining the necessary dimensions to make this feasible.

2. Constraints & Input Parameters (Given)

Macadamia nut radius: r = 0.01 m (1 cm)
Force required to crack a macadamia nut: F_N = 2220 N
Maximum human grip strength: F_A = 500 N (applied at each handle)

3. Approach
Taking the moment about pivot point A and summing moments to zero: the nut sits 1 cm from the pivot (y = 1 cm, constrained by nut size), and solving gives handle length x₂ = 2 cm with total arm length ~6.88 cm. This satisfies the moment balance: 2220×1 = 500×x₁ + 500×x₂.

4. Diagram
(See attached sketch — lever nutcracker with pivot A, nut positioned 1 cm from pivot, handles extending ~6.88 cm total)

5. Discussion on Usability
The design is usable since applying 500 N of grip force on each handle generates sufficient mechanical advantage to crack the nut. For the linear actuator modification (part c), replacing the grip with a heavy-duty linear actuator at y = 30 cm allows the same 500 N output force requirement while accommodating the actuator's stroke length.
