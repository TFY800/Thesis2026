---
name: TAOFUYUAN
neptun: GF9EDC
id: 2026-ST-03
---

# Multi-Robot Autonomous Task Solving in a Simulated Environment

## My interpretation of the brief

I understand the project as the design and evaluation of autonomous agents that can solve tasks in a simulated environment, either individually or as part of a multi-agent system.

The main challenge is not only movement or path finding, but decision making: an autonomous agent has to interpret the current state of the environment, select an appropriate objective, coordinate its actions with other agents, and react when the situation changes.

I am especially interested in competitive and cooperative multi-agent scenarios, where agents need to make decisions at different levels instead of relying only on simple reactive rules.

## Why I am a good fit for this project

I am particularly interested in game AI, autonomous agents, and decision-making systems.

What interests me most about this project is the possibility of studying how an artificial agent can behave in a more structured and human-like way. Instead of using one decision system for every situation, I would like to investigate a hierarchical architecture in which strategic, tactical, and immediate execution decisions are handled at different levels.

This fits well with the multi-agent and autonomous task-solving focus of the project, while also providing a clear experimental question that can be evaluated against simpler AI approaches.

## Relevant experience and background

I have experience with programming and game development, especially with Unity and gameplay-system design.

In my previous work, I have designed combat systems, character behaviour, skills, user interfaces, and rule-based gameplay mechanics. This has given me experience in breaking complex interactive systems into smaller components and defining clear rules for how different systems communicate with each other.

I am also interested in artificial intelligence and have been studying behaviour trees, utility-based decision making, hierarchical AI architectures, and multi-agent systems.

## Proposed approach

My initial idea is to create a simulated task environment containing multiple autonomous agents and compare different decision-making architectures.

The first implementation would use a conventional reactive or behaviour-tree-based agent as a baseline.

I would then investigate a hierarchical decision-making architecture with three levels:

1. **Strategic layer**  
   Determines the high-level objective of an agent or team, for example controlling an area, protecting a resource, reaching a target, or avoiding a dangerous region.

2. **Tactical layer**  
   Determines how the strategic objective should be achieved. It could assign roles to agents, select routes, identify opportunities, coordinate agents, or decide when the current plan should be changed.

3. **Execution layer**  
   Handles immediate actions such as movement, interaction, avoidance, attack, defence, or other environment-specific actions. A behaviour tree could be used at this level.

An important part of the project would be communication between these layers. For example, the strategic layer may define an objective, while the tactical layer continuously searches for a safe and efficient opportunity to execute it. The execution layer would remain responsible for immediate reactions when unexpected events occur.

The system could then be compared with a simpler single-layer behaviour tree or another decision-making approach.

## Initial plan

1. Define the simulated environment, agent state, observations, actions, goals, and task-completion conditions.
2. Implement a simple baseline agent using reactive rules or a behaviour tree.
3. Define the communication model between strategic, tactical, and execution-level decision making.
4. Implement the hierarchical multi-agent decision architecture.
5. Add cooperative or competitive tasks involving multiple agents.
6. Create reproducible test scenarios with different levels of environmental complexity.
7. Compare the baseline and hierarchical approaches using objective metrics such as task success rate, decision time, resource efficiency, unnecessary actions, and robustness to unexpected events.
8. Analyse whether hierarchical decision making produces more coherent and adaptive agent behaviour.

## Additional information

I would like to build the project in a modular way so that different decision-making methods can be tested in the same simulation environment.

My current research interest is whether hierarchical decision making can make autonomous agents appear more purposeful and human-like without requiring every individual action to be globally optimal.

If the project scope allows it, I would also be interested in evaluating the agents from a user perspective, for example by testing whether participants perceive hierarchical agents as more intelligent, believable, or strategically consistent than agents controlled only by a conventional behaviour tree.