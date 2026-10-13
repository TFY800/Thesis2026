---
project_outline: "[[00-project/01-project-outline]]"
---

<!-- @slide Cover -->

<!-- 3xl -->
# Investigation of Optimal Path Planning and Formation Changes in Drone Swarms

Author: Tao Fuyuan  
Neptun: GF9EDC  
Supervisor: Professor Oláh Gábor  
Project ID: 2026-OG-03  

Semester 1 — Presentation 1

---

<!-- @slide Problem -->

## Problem

- Move a group of drones from one formation to another.
- **Target assignment:** decide which drone goes to each target position.
- **Path planning:** plan routes and timing to avoid collisions.
- Two drones may choose the same closest target. Target positions must not repeat.
- What does **“best”** mean: shortest paths or shortest completion time?
- How should we choose the paths?

---

<!-- @slide Target users -->

## Target users

- **Drone show planners:** test formation changes and check safe movement.
- **Students studying drone swarms:** test and compare target assignment and path planning methods.

---

<!-- @slide Planned scope -->

## Planned scope

- Build a **3D simulation**.
- Implement an algorithm for **target assignment and path planning**.

**Outside the scope:** real drone hardware, communication, GPS errors, wind, and battery limits.

---

<!-- @slide Initial user journeys -->

## Initial user journeys

1. Choose the number of drones.
2. Choose the starting formation and target formation.
3. Run the simulation and watch the planned movement.
4. Check completion time and whether any collisions occur.

---

<!-- @slide Next steps -->

## Next steps

- Choose an algorithm for **target assignment and path planning**.
- Choose test scenarios and define how to evaluate the results.
- Update the project outline and specification.
