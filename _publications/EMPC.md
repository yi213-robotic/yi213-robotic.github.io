---
title: "EMPC-Based Flight Control and Collision-Free Path Planning for a Quadrotor With Unbalanced Payload"
collection: publications
category: Journals
permalink: /publication/EMPC
excerpt: 'A new optimal sampling-based motion planner (state-of-the-art)'
date: 2025-06-19
venue: 'IEEE/ASME Transactions on Mechatronics'
paperurl: '[http://academicpages.github.io/files/paper3.pdf](https://ieeexplore.ieee.org/abstract/document/11030654)'
citation: '@ARTICLE{11030654,
  author={Zhang, Xiangyu and Wang, Yi and Mu, Bingxian and Yoon, Se Young},
  journal={IEEE/ASME Transactions on Mechatronics}, 
  title={EMPC-Based Flight Control and Collision-Free Path Planning for a Quadrotor With Unbalanced Payload}, 
  year={2025},
  volume={},
  number={},
  pages={1-10},
  keywords={Quadrotors;Path planning;Uncertainty;Optimization;Attitude control;Real-time systems;Propellers;Three-dimensional displays;Trajectory;Tracking loops;3-D path planning;bidirectional guidance informed trees (BIGIT*);explicit model predictive control (EMPC);integral sliding mode control (ISMC);minimum snap trajectory generation;quadrotor},
  doi={10.1109/TMECH.2025.3572522}}
'
---

This paper introduces Bidirectional Lazy Informed Trees (BLIT*), the first algorithm to incorporate anytime incremental lazy bidirectional heuristic search (Bi-HS) into batch-wise sampling-based motion planning (Bw-SBMP). BLIT* operates on batches of informed states (states that can potentially improve the cost of the incumbent solution) structured as an implicit random geometric graph (RGG). The computational cost of collision detection is mitigated via {\em a new lazy edge-evaluation strategy} by focusing  on states near obstacles. Experimental results, especially in high dimensions, show that BLIT* outperforms existing Bw-SBMP planners by efficiently finding an initial solution and effectively improving the quality as more computational resources are available.
