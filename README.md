# 2D Multi-Agent Flocking Simulations

This repository contains Python-based simulations of multi-agent swarm behavior. It is designed to serve as a helpful, accessible starting point for individuals and students who are just beginning to explore multi-agent systems (MAS) and swarm robotics. The project explores boid flocking dynamics, starting from fundamental decentralized rules and extending into advanced control strategies and environmental interactions. 

The simulations are built using `NumPy` for efficient vector mathematics and `Matplotlib` for 2D animation.

## Current State
* **Base Flocking Model (`01_base_flocking.ipynb`)**: Implements the classic Reynolds flocking algorithm. The autonomous agents (boids) navigate a 2D environment governed by three core kinematic rules:
  * **Separation:** Steering to avoid crowding local flockmates.
  * **Alignment:** Steering towards the average heading of local flockmates.
  * **Cohesion:** Steering to move toward the average position of local flockmates.

## Project Roadmap
This repository is an ongoing exploration of swarm robotics. Planned updates include:

- [ ] **Improved Controller Integration** (Upcoming)
- [ ] **Leader-Follower Dynamics**
- [ ] **Obstacle Avoidance Behavior**

## Setup
To run the simulations locally, ensure you have Jupyter Notebook or JupyterLab installed along with the following dependencies:
```bash
pip install numpy matplotlib ipython
