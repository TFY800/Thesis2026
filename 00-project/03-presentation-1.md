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

[Project outline](01-project-outline.md)

<!-- @note -->
> Hello everyone. I'm Tao Fuyuan.
>
> My project is called “Investigation of Optimal Path Planning and Formation Changes in Drone Swarms.” My supervisor is Professor Oláh Gábor.

---

<!-- @slide Problem -->

## Problem

- Move a group of drones from one formation to another.
- **Target assignment:** decide which drone goes to each target position.
- **Path planning:** plan routes and timing to avoid collisions.
- Two drones may choose the same closest target. Target positions must not repeat.
- What does **“best”** mean: shortest paths or shortest completion time?
- How should we choose the paths?

<!-- @note -->
> The basic idea is to move a group of drones from one formation to another.
>
> There are two main questions. First, which drone should go to each target position? This is called target assignment. Second, how can the drones move to those positions safely? This is the path planning problem.
>
> For example, if two drones need to change positions and fly directly towards each other at the same height, they could collide. So we need to plan both their routes and when they move to avoid collisions.
>
> But the difficult part is how to make a good target assignment.
>
> Should we simply send each drone to its closest target? If each drone chooses independently, two drones might choose the same target position. So we need to make sure that each target position is assigned to only one drone.
>
> The second difficulty is understanding what “best” means. Does it mean taking the shortest paths, or completing the formation change in the shortest time?
>
> And based on that, how should we choose the paths?

---

<!-- @slide Target users -->

## Target users

- **Drone show planners:** test formation changes and check safe movement.
- **Students studying drone swarms:** test and compare target assignment and path planning methods.

I still need to confirm which group should be the main focus.

<!-- @note -->
> The main users I have in mind are drone show planners.
>
> In a drone light show, drones need to move from one shape to another. The planners could use the simulation to test these formation changes and check whether the drones can move safely.
>
> Another group is students studying drone swarms. They could use it to test and compare different target assignment and path planning methods.
>
> I still need to discuss with my supervisor which group should be the main focus.

---

<!-- @slide Planned scope -->

## Planned scope

- Build a **3D simulation**.
- Implement an algorithm for **target assignment and path planning**.
- Let users choose the drone count, starting formation, and target formation.
- Run the simulation and show the formation change.

**Outside the scope:** real drone hardware, communication, GPS errors, wind, and battery limits.

Is this a reasonable scope? Should I add or leave out anything?

<!-- @note -->
> I plan to build a 3D simulation.
>
> I also plan to implement an algorithm for target assignment and path planning.
>
> Users can choose the number of drones, the starting formation, and the target formation. Then they can start the simulation and watch the drones move from one formation to another.
>
> Real drone hardware, communication, GPS errors, wind, and battery limits are outside the scope.
>
> Does this sound like a reasonable scope for my project? Is there anything I should add or leave out?

---

<!-- @slide Initial user journeys -->

## Initial user journeys

1. Choose the number of drones.
2. Choose the starting formation and target formation.
3. Run the simulation and watch the planned movement.
4. Check completion time and whether any collisions occur.

<!-- @note -->
> First, the user chooses the number of drones and the starting and target formations.
>
> Then they run the simulation. The algorithm plans the formation change, and the user can watch the drones move.
>
> Finally, they check how long the formation change takes and whether any collisions occur.

---

<!-- @slide Next steps -->

## Next steps

- Choose an algorithm for **target assignment and path planning**.
- Discuss the target users and planned scope with my supervisor.
- Choose test scenarios and agree on how to judge the results.
- Update the project outline and specification after our discussion.

<!-- @note -->
> My next step is to choose a suitable algorithm for target assignment and path planning.
>
> I will also discuss the target users and planned scope with my supervisor.
>
> We also need to choose test scenarios and agree on how to judge the results.
>
> After that, I'll update the project outline and specification.
>
> Thank you.

