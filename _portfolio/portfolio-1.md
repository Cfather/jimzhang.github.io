---
title: "Provably-Safe, Real-time Planning & Control For Bipedal Robots Using Reachability-Based Trajectory Design"
excerpt: "<img src='../images/random_70.jpg' width='684' height='400'/>"
collection: portfolio
---

Abstract:
To operate robustly in uncertain environments with a finite sensor horizon, bipedal robots must be able to perform receding horizon trajectory planning in concert with rapid control synthesis. 
Unfortunately creating safe, dynamically-feasible trajectories for high-dimensional bipedal robotic systems in real-time is challenging. 
As a result, most existing approaches make an undesirable trade-off between model-fidelity and planning speed. 
To avoid this undesirable tradeoff, this paper describes a method for generating and optimizing over multi-step reference trajectories of a bipedal walking robot which are guaranteed to avoid falls and collisions with obstacles within a receding-horizon framework. 
The robot employs a robust controller to track these trajectories, which provides an ultimate bound on the maximum error of each of the robot's joint angles. 
At runtime, in each receding horizon planning iteration, the proposed method constructs a reachable set of the entire robot and intersects it with obstacles to generate sub-differentiable and provably-conservative collision avoidance constraints on the trajectory parameters. 
This enables trajectory optimization for an arbitrary cost function subject to these constraints. 
In simulation, on a 20 degree-of-freedom bipedal robot Digit, this method consistently outperforms state of the art methods.