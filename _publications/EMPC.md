---
title: "EMPC-Based Flight Control and Collision-Free Path Planning for a Quadrotor With Unbalanced Payload"
collection: publications
category: manuscripts
permalink: /publication/EMPC
excerpt: 'Explicit model predictive flight control and collision-free path planning for a quadrotor with an unbalanced payload'
date: 2025-06-19
venue: 'IEEE/ASME Transactions on Mechatronics'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/11030654'
citation: 'Xiangyu Zhang, Yi Wang, Bingxian Mu, Se Young Yoon. "EMPC-Based Flight Control and Collision-Free Path Planning for a Quadrotor With Unbalanced Payload." IEEE/ASME Transactions on Mechatronics, 2025. doi:10.1109/TMECH.2025.3572522'
---

In this article, a robust explicit model predictive control (EMPC) flight scheme is investigated for
a quadrotor. MPC is widely recognized for its control effectiveness, but the computational complexity involved in
solving online optimization problems, particularly when applied to fast systems, poses a significant challenge. To enable real-time MPC implementation on quadrotor systems,
we propose a novel dual-layer control architecture integrating EMPC, strategically relocating the computationally
intensive optimization process to offline computation. The
outer loop computes reference roll and pitch angles, while
the inner loop employs an EMPC framework to achieve
fast attitude tracking considering state and actuator constraints. Moreover, integral sliding mode control (ISMC) is
integrated to mitigate the effects of uncertainties, such as
unbalanced payloads. The recursive feasibility is guaranteed for the proposed flight control method if the initial
states are in the feasibility set, and the Lyapunov stability analysis is conducted. In addition, we develop a polynomial trajectory planning algorithm for the quadrotor in
(3-D) space. We employ our previous result, the bidirectional guidance informed trees (BIGIT∗) algorithm, to obtain a sequence of collision-free waypoints, and utilize the
minimum-snap technique to generate a smooth path. Finally, experimental results demonstrate the effectiveness of
the proposed methods.
