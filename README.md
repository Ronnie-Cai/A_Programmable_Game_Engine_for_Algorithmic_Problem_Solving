# A Programmable Game Engine for Algorithmic Problem Solving

**Project Type**: System Development / Graphic Design / Web application / Database  
**Number of Students**: 2  
**Supervisor**: Mr. Teng LAM  
**Email**: tlam@um.edu.mo  

## Overview

CodeQuest is a browser-based game system where players do not control characters via keyboard or mouse, but instead write C++ or Python programs that command an in-game agent to solve algorithmic challenges. The system provides a visual grid-based world (e.g., mazes, resource-gathering maps, combat arenas, or puzzle chambers) and exposes a well-documented API. Students write code implementing strategies — pathfinding, state-space search, dynamic programming, game-tree exploration, or heuristic optimization — which the engine executes in a sandboxed environment. The agent's behavior is rendered in real-time, allowing players to observe, debug, and iterate on their algorithms visually. 

## Project Objectives

1. Design and implement a modular game engine capable of loading different "world scenarios" (e.g., maze escape, treasure hunt, NPC combat, automated logistics).
2. Build a secure sandboxed execution environment that can compile and run untrusted C++ and Python user code safely, with resource limits (CPU time, memory, execution steps).
3. Develop a clean, intuitive API exposing percepts (sensor data) and actuators (movement, actions) to the player's program.
4. Create a web-based interface where users write code, submit solutions, and watch visual replays of their agent's execution.
5. Implement a progressive challenge system with levels of increasing algorithmic difficulty, from simple BFS/DFS to adversarial game-tree search and multi-agent coordination.
6. Design a leaderboard and scoring mechanism that evaluates solutions on correctness, efficiency (time/steps), and code elegance.

##  Deliverables
### Software Deliverables
* Game Engine: Fully functional engine with at least 6 distinct challenge scenarios.
* Sandbox System: Secure execution environment supporting both C++ and Python.
* Web Platform: User registration, code editor, submission system, visual replay, and leaderboard.
* API Documentation: Complete reference for the agent API.
* Level Editor: Tool for instructors to design new algorithmic challenges.
### Documentation
* Technical Report: System architecture, security model, and API design.
* User Guide: Tutorial for players on how to write agent programs.
* Instructor Guide: How to create new levels and evaluate student submissions.

## Prerequisites / Recommended Skills
* Strong proficiency in C++ and Python
* Familiarity with Linux system
* Basic knowledge of game development (game loops, rendering, state management)
* Web development (REST APIs, WebSockets, modern JavaScript frameworks)
* Understanding of classical AI algorithms (search, game trees, optimization)

## Expected Outcomes
Upon completion, this project will produce a fully functional educational platform that bridges the gap between theoretical algorithm courses and practical implementation. It can be deployed as a teaching aid for Data Structures & Algorithms, Artificial Intelligence, or Competitive Programming courses, giving students immediate visual feedback on how their code behaves in a dynamic environment.

## References:
- [codecombat](https://codecombat.com/)
- [codecombat in git](https://github.com/codecombat/codecombat)
- [Programiz: Free Online Compilers for Everyday Use](https://www.programiz.com/)
