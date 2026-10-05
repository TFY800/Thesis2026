---
project_outline: "[[00-project/01-project-outline]]"
---

<!-- 3xl -->
# Investigation of Optimal Path Planning and Formation Changes in Drone Swarms

Author: Tao Fuyuan  
Neptun: GF9EDC  
Supervisor: Professor Oláh Gábor  
Project ID: 2026-OG-03  
Semester 1 — Presentation 1

[Project outline](01-project-outline.md)

---

## Problem

- A drone swarm needs to move from one formation to another.
- Target assignment: decide which drone goes to each target position.
- Path planning: keep drones a safe distance apart and within motion limits.
- Compare completion time, total path length, and planning time.
- Also check minimum separation and whether the run succeeds.

My main question: Is this the core problem I should focus on?

---

## Target users

- Students: watch formation changes and learn how planning works.
- Researchers: try different methods under the same conditions.
- These are the users I have in mind.
- I still need to confirm who the main users should be.

---

## Planned scope

- I plan to start with a 3D simulation.
- Set drone count, start and target formations, and planning method.
- Set speed, acceleration, and safe-distance limits.
- Assign targets, show movement, check safety, and compare results.
- Leave hardware, real communication, GPS errors, wind, and batteries out.

I will discuss this scope and a possible two-method comparison with my supervisor.

---

## Initial user journeys

1. Choose drone count and the start and target formations.
2. Set motion limits and safe distance; choose a planning method.
3. Run the simulation and watch the drones move.
4. Check run status and results; if it fails, review the reason and retry.
5. Run another method with the same settings and compare.

---

## Next steps

- Ask my supervisor whether I am focusing on the right problem.
- Confirm the main users, first-version scope, and user journeys.
- Choose test scenarios and agree on objectives and how to judge results.
- Update the project outline and specification after our discussion.
