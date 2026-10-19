---
project_outline: "[[00-project/01-project-outline]]"
---

<!-- @slide Cover -->
<!-- @slide-theme stone orange gray -->
<!-- @set-align center -->
<!-- @set-width 90% -->
<!-- @set-gap 2 -->

<!-- @space -->

# Investigation of Optimal Path Planning and Formation Changes in Drone Swarms

<!-- @gap 2 -->

Author: Tao Fuyuan  
Neptun: GF9EDC  
Supervisor: Professor Oláh Gábor  
Project ID: 2026-OG-03

Semester 1 — Presentation 1

<!-- @space -->

---

<!-- @slide Problem -->
<!-- @slide-theme stone orange gray -->
<!-- @set-align left -->
<!-- @set-width 90% -->
<!-- @set-gap 2 -->

## Problem

Move a group of drones from one formation to another.

- **Target assignment:** decide which drone goes to each target position.
- **Path planning:** plan routes and timing to avoid collisions.

If drones each choose the closest target, two may choose the same position. Each target must be assigned only once.

- What does **“best”** mean: shortest paths or shortest completion time?
- How should we choose the paths?

---

<!-- @slide Target users -->
<!-- @slide-theme stone orange gray -->
<!-- @set-align left -->
<!-- @set-width 90% -->
<!-- @set-gap 2 -->

## Target users

<!-- @space -->
<!-- @columns 2 5 -->

### Drone show planners

- Test formation changes.
- Check whether drones move safely.

<!-- @col-break -->

### Students studying drone swarms

- Test target assignment and path planning methods.
- Compare the results of different methods.

<!-- @columns -->

<!-- @space -->

---

<!-- @slide Planned scope -->
<!-- @slide-theme stone orange gray -->
<!-- @set-align left -->
<!-- @set-width 90% -->
<!-- @set-gap 2 -->

## Planned scope

### Included

- Build a **3D simulation**.
- Implement an algorithm for **target assignment and path planning**.

**Algorithm requirements**

- Minimize the time needed to complete the formation change.
- Respect drone speed and acceleration limits.
- Avoid collisions.

<!-- @gap 1 -->
<!-- @scale 85% -->
**Outside the scope**  
Real drone hardware, communication, GPS errors, wind, and battery limits.

---

<!-- @slide Initial user journeys -->
<!-- @slide-theme stone orange gray -->
<!-- @set-align left -->
<!-- @set-width 90% -->
<!-- @set-gap 2 -->

## Initial user journeys

<!-- @space -->

1. Choose the number of drones.

2. Choose the starting formation and target formation.

3. Run the simulation and watch the planned movement.

4. Check completion time and whether any collisions occur.

<!-- @space -->

---

<!-- @slide Next steps -->
<!-- @slide-theme stone orange gray -->
<!-- @set-align left -->
<!-- @set-width 90% -->
<!-- @set-gap 2 -->

## Next steps

<!-- @space -->

- Choose an algorithm for **target assignment and path planning**.

- Choose test scenarios and define how to evaluate the results.

- Update the project outline and specification.

<!-- @space -->
