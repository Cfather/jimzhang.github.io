---
title: "Serving Time: Real-Time, Safe Motion Planning and Control for Manipulation of Unsecured Objects"
excerpt: "<img src='../images/waitr-demo.png' width='552' height='400'/>"
collection: portfolio
---

Abstract:
As robotic systems transition from the industrial sector to our daily lives, a key challenge is achieving safe operation while in close proximity to humans.
Certifiably safe motion planning and control methods are required to deal with model uncertainty and generate new motion plans in real-time to handle arbitrary environments.
This paper proposes Wrench Analysis for Inertial Transport using Reachability (WAITR), a certifiably safe motion planning and control framework for serial link manipulators that manipulate unsecured objects in arbitrary environments.
WAITR uses reachability analysis to construct over-approximations of the contact wrench applied to unsecured objects, which captures uncertainty in the manipulator dynamics, the object dynamics, and contact parameters such as the coefficient of friction.
An optimization problem formulation is presented, which can be solved tractably in real-time in order to generate provably-safe motions for manipulating the unsecured objects.
WAITR implements this in a framework which contains a receding horizon trajectory planner and a low-level robust controller which enable a robotic manipulator to safely operate in real-time to avoid obstacles while manipulating unsecured objects.
The proposed method is demonstrated in simulation and on real hardware.

The video demo of this paper can be found [here](https://youtu.be/-n6SwmylyX4?si=RdTsgVqxesKDfSJx)