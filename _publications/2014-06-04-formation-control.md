---
title: "Distributed Formation Control Without a Global Reference Frame"
collection: publications
permalink: /publication/2014-06-04-formation-control
date: 2014-06-04
venue: 'American Control Conference'
citation: '
@inproceedings{MontijanoEtAlACC14FormationControl,
  author = {E. Montijano and D. Zhou and M. Schwager and C. Sagues}, 
  title = {Distributed Formation Control without a Global Reference Frame},
  booktitle = {Proc. of the American Control Conference (ACC 14)},
  month = {June},
  year = {2014},
  pages = {3862--3867}
}
'

---
This paper presents a decentralized controller to drive a team of agents to reach a desired formation in the absence of a global reference frame. Each agent is able to measure its relative position and orientation with respect to its neighbors. The different orientations imply that the relative positions between pairs of agents are sensed differently for each agent. In order to reach the desired configuration, the agents use two simultaneous consensus controllers, one to control their relative orientations, and another for their relative positions. The convergence to the desired configuration is shown by comparing the system with time-varying orientations with the equivalent approach with fixed rotations, showing that their difference vanishes as time goes to infinity. While the analysis in the paper is performed in a 2-dimensional space with orientations belonging to $\mathcal{SO}(2)$, our approach can be extended to handle 3 dimensions and orientations in $\mathcal{SO}(3)$. Simulation results, as well as hardware experiments with two quadrotor UAVs, corroborate the theoretical findings of the paper.

[Download paper from here](https://web.stanford.edu/~schwager/MyPapers/MontijanoEtAlACC14FormationControl.pdf)

