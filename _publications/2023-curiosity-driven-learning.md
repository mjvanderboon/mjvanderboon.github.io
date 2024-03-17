---
title: "Curiosity-Driven Learning of Joint Locomotion and Manipulation Tasks"
collection: publications
permalink: /publication/2023-curiosity-driven-learning
excerpt: 'From my thesis, a follow-up research was conducted on curiosity-based reinforcement learning for robotics and published by the Robotic Systems Lab in Zurich.'
date: 2023-10-01
venue: 'Proceedings of The 7th Conference on Robot Learning'
paperurl: 'https://dl.acm.org/doi/pdf/10.1145/3505284.3532976'
citation: 'Clemens Schwarke, Victor Klemm, Matthijs Van der Boon, Marko Bjelonic, Marco Hutter. (2023). &quot;Curiosity-Driven Learning of Joint Locomotion and Manipulation Tasks</i>. 1(1).'
---
Learning complex locomotion and manipulation tasks presents significant challenges, often requiring extensive engineering of, e.g., reward functions or curricula to provide meaningful feedback to the Reinforcement Learning (RL) algorithm. This paper proposes an intrinsically motivated RL approach to reduce task-specific engineering. The desired task is encoded in a single sparse reward, i.e., a reward of “+1” is given if the task is achieved. Intrinsic motivation enables learning by guiding exploration toward the sparse reward signal. Specifically, we adapt the idea of Random Network Distillation (RND) to the robotics domain to learn holistic motion control policies involving simultaneous locomotion and manipulation. We investigate opening doors as an exemplary task for robotic ap- plications. A second task involving package manipulation from a table to a bin highlights the generalization capabilities of the presented approach. Finally, the resulting RL policies are executed in real-world experiments on a wheeled-legged robot in biped mode. We experienced no failure in our experiments, which consisted of opening push doors (over 15 times in a row) and manipulating packages (over 5 times in a row).
