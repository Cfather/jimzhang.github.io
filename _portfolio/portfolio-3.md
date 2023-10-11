---
title: "Reachable Sets for Safe, Real-Time Manipulator Trajectory Design"
excerpt: "<img src="../images/armtd-demo.png" width="500" height="280"/>"
collection: portfolio
---

Abstract:
For robotic arms to operate in arbitrary environments, especially near people, it is critical to certify the safety of their motion planning algorithms.
However, there is often a trade-off between safety and real-time performance; one can either carefully design safe plans, or rapidly generate potentially-unsafe plans.
This work presents a receding-horizon, real-time trajectory planner with safety guarantees, called ARMTD (Autonomous Reachability-based Manipulator Trajectory Design).
The method first computes (offline) a reachable set of parameterized trajectories for each joint of an arm.
Each trajectory includes a fail-safe maneuver (braking to a stop).
At runtime, in each receding-horizon planning iteration, ARMTD constructs a parameterized reachable set of the full arm in workspace and intersects it with obstacles to generate sub-differentiable, provably-conservative collision-avoidance constraints on the trajectory parameters.
ARMTD then performs trajectory optimization over the parameters, subject to these constraints.
On a 6 degree-of-freedom arm, ARMTD outperforms CHOMP in simulation, never crashes, and completes a variety of real-time planning tasks on hardware.

The video demo of this paper can be found [here](https://www.youtube.com/watch?v=ySnux2owlAA&t=2s)
