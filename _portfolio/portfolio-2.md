---
title: "Safe, Optimal, Real-time Trajectory Planning
with a Parallel Constrained Bernstein Algorithm"
excerpt: "<img src='../images/pcba-demo.png' width="590" height="600">"
collection: portfolio
---

Abstract:
To move while using new sensor information, mobile robots use receding-horizon planning, executing a short plan while computing a new one.
A plan should have dynamic feasibility (obeying a robot's dynamics and avoiding obstacles), liveness (planning frequently enough to complete tasks), and optimality (minimizing, e.g., distance to a goal).
Reachability-based Trajectory Design (RTD) is a method to generate provably dynamically-feasible plans in real time by solving a polynomial optimization program (POP) in each planning iteration.
However, RTD uses a derivative-based solver, which may converge to local minima that impact liveness and optimality.
This paper proposes a Parallel Constrained Bernstein Algorithm (PCBA) branch-and-bound method to optimally solve RTD's POP at runtime; the resulting optimal planner is called RTD-star.
The specific contributions of this paper are: the PCBA implementation; proofs of PCBA's bounded time and memory usage; a comparison of PCBA to state-of-the-art solvers; and a demonstration of PCBA/RTD-star on hardware.
RTD* shows better optimality and liveness than RTD in dozens of environments with random obstacles.

The video demo of this paper can be found [here](https://www.youtube.com/watch?v=YcH4WAzqPFY)
