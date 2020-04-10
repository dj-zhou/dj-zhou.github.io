---
title: "Virtual Rigid Bodies for Coordinated Agile Maneuvering of Teams of Micro Aerial Vehicles"
collection: publications
permalink: /publication/2015-05-25-virtual-rigid-body
# excerpt: ''
date: 2015-05-25
venue: 'IEEE International Conference on Robotics and Automation (ICRA)'
citation: '
@inproceedings{ZhouSchwagerICRA15VirtualRigidBodies,
  author = {D. Zhou and M. Schwager}, 
  title = {Virtual Rigid Bodies for Coordinated Agile Maneuvering of Teams of Micro Aerial Vehicles},
  booktitle = {Proc. of the International Conference on Robotics and Automation (ICRA 15)},
  month = {May},
  year = {2015},
  pages = {1737--1742}
}
'

---
This paper proposes a method for controlling a team of quadrotor micro aerial vehicles to perform agile maneuvers while holding a fixed relative formation, as well as transitioning between a sequence of formations. The objective is to coordinate the quadrotors to fly in intricate interlaced patterns, similarly to an air show demonstration team. The paper proposes a new abstraction, called a Virtual Rigid Body, which allows the quadrotors to hold relative positions while executing agile maneuvers as a group. By planning trajectories for the Virtual Rigid Body in $\mathcal{SE}(3)$, trajectories for each quadrotor are obtained in order to maintain the desired formation during the maneuver. The paper also proposes a method for sequencing a series of Virtual Rigid Body formations, and automatically designing collision free transitions between successive formations, while the team simultaneously executes a trajectory in SE(3). The resulting sequence of formations and transitions gives trajectories that weave intricate designs while avoiding collisions. The method is demonstrated experimentally with three KMel K500 quadrotors flying in a motion capture environment.

[Download paper from here](https://web.stanford.edu/~schwager/MyPapers/ZhouSchwagerICRA15VirtualRigidBodies.pdf)

