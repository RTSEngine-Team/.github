# Real-Time Strategy Simulation Engine (RTSEngine)

A real-time strategy (RTS) engine built on a custom Entity–Component–System (ECS) architecture.  
Designed for large-scale unit simulation, deterministic updates, and modern rendering pipelines.

---

### Why RTSEngine is unique:
- Capable of simulating 40k–60k active units with collisions and combat at 60 FPS.
- Built for deterministic large-scale RTS battles.
- Aimed at creating a new kind of RTS experience: true epic-scale battles combined with RTS gameplay depth.

---

### Watch some footage here [(YouTube)](https://youtu.be/l-pexSYvleE?si=tXjArMBU887Saiqw)
![Capture](https://github.com/user-attachments/assets/c5b7057b-5918-494f-b3f3-87cb6583c802)
![capture2](https://github.com/user-attachments/assets/a525bf71-8a62-46c7-84f3-6d753ff57cdd)
![capture3](https://github.com/user-attachments/assets/05cd0861-aa51-4fcd-a54d-72040bfa5e47)

---

## Overview

This project explores how to scale RTS mechanics to tens of thousands of units while preserving responsiveness and visual clarity.  
It is part of our research into simulation-heavy game architectures.

Core goals:
- **Scalability**: handle tens of thousands of active entities.
- **Determinism**: fixed-step updates for consistent replays/network sync.
- **Performance**: parallel simulation and GPU-driven rendering.
- **Flexibility**: extensible ECS design for future mechanics.

---

## Technology

| Category      | Technology                                     |
| ------------- | ---------------------------------------------- |
| Language      | C# (.NET)                                      |
| Framework     | MonoGame                                       |
| Architecture  | Custom ECS                                     |
| Rendering     | GPU instancing + 2D overlays                   |

---

## Current Focus

- Extending formation & combat mechanics  
- Experimenting with advanced pathfinding approaches (flow fields, PBD collisions)
- Improve ECS architecture
- Expanding rendering/animation pipeline
- Simple networking demo
- Demo of RTS game loop with massive battles

---

## Licensing

This readme is provided for **demonstration and informational purposes only**.  

No part of this software may be used, copied, or distributed without explicit permission.  

All rights reserved © 2025 RTSEngine.  

---

## Acknowledgments

Original engine concept and prototype by [Harry Bridgen](https://github.com/harrybridgen).  
Further development maintained by the RTSEngine team.
