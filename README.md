# Masters-Thesis-Videos
UAV Videos

## Overview

This project develops a Mixed-Integer Linear Programming (MILP) framework for safe and wind-aware trajectory planning of multi-drone systems operating in urban environments.
The system enables collision-free navigation under realistic wind disturbances, including gusts and spatially varying wind fields influenced by surrounding buildings.

---

## Hardware Validation (Crazyflie Nano-Quadrotor)

The proposed MILP-generated trajectories were validated experimentally using a Crazyflie nano-quadrotor.
The drone executed precomputed position setpoints in open-loop flight, demonstrating qualitative agreement with the simulated trajectories.

Two experimental scales were evaluated:
- Small-scale workspace: 2.0 × 1.8 × 1.3 m  
- Large-scale workspace: 15.0 × 4.0 × 1.6 m  
These experiments confirm that the simulated wind-aware planning framework produces physically consistent trajectories that can be executed on real UAV hardware.
