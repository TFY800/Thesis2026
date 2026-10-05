---
name: Tao Fuyuan
neptun: GF9EDC
id: 2026-OG-03
supervisor: Oláh Gábor
github: https://github.com/TFY800/Thesis2026
github_project: null
---
# Investigation of Optimal Path Planning and Formation Changes in Drone Swarms

**Status:** Proposed outline for Semester 1 — Presentation 1. Problem, users, scope, and success criteria remain to be confirmed with Professor Oláh Gábor. No supervisor feedback or approval is recorded yet. The original brief and accepted application are not available for verification.

## Objectives

- **Problem:** A drone swarm changes from an initial formation to a target formation. Target assignment decides which drone reaches each target position; coordinated path planning determines how the drones move while respecting minimum separation and motion limits.
- **Why investigate it:** Assignment and movement affect one another. A short assignment alone does not establish safe trajectories. A common simulation could help users observe these effects and compare methods under the same conditions.
- **Primary objective (proposed):** Define and later build a 3D simulation for planning, viewing, and evaluating formation changes. “Optimal” in the formal title does not establish that a candidate method is optimal: the objective, constraints, and evidence must first be agreed.
- **Target users / stakeholders (proposed):** Students who want to understand formation changes and planning; researchers who want to compare methods. The primary audience is to be confirmed. The author and supervisor discuss scope and evaluation.
- **Candidate measurable success criteria:** A user can configure and run a scenario, view assigned targets and movement, inspect motion/separation checks and run status, and compare methods using the same scenario. Candidate metrics are completion time, total path length, planning computation time, minimum separation, and run success. Definitions, verification methods, and acceptable limits remain to be agreed.
- **Constraints:** Simulation only in the proposed first version. Keep configuration validation separate from checking trajectories. No technology stack, algorithms, deadlines, or performance thresholds have been approved.

## Scope
### In scope

Proposed Semester-2 MVP:

- Configure drone count, initial and target formations, speed and acceleration limits, minimum safe separation, and a planning method.
- Assign target positions and plan coordinated movement.
- Show a 3D simulation and check separation and motion limits across the movement.
- Show success or failure, reasons, and available result metrics.
- Compare methods using identical scenario settings. At least two strategies are a candidate scope, subject to feasibility and supervisor discussion.

Semester 1 prepares requirements, user journeys, acceptance criteria, and an initial technical proposal. A complete system is not a prerequisite for Presentation 1.

### Out of scope

Proposed exclusions, to be confirmed: physical drones, real communication, GPS errors, wind, and battery modelling. Hardware control is outside the current draft.

## Notes

Discussion questions:

- Is target assignment plus safe formation-change path planning the core problem?
- Should students or researchers be the main users?
- Is the proposed MVP, including method comparison, manageable?
- Do the initial user journeys match the intended use?
- Which scenarios, optimization objective, constraints, and result measures should be used?

Documentation follow-up:

- Obtain the real project brief and check this interpretation against it.
- Obtain the original accepted drone application and preserve it at `00-application.md`.
- Supply or verify the GitHub Projects board URL; `github_project: null` means unknown.
- Record actual consultation feedback and update the [specification](02-specification.md) and [Presentation 1](03-presentation-1.md).
- Obtain `evaluation-1-en`, referenced by the supplied requirements, for the complete assessment rules.
