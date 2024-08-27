---
title: "Muti-agent proximal policy optimization for data freshness in UAV-assisted networks"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-3
excerpt: 'This paper optimizes UAV scheduling and device association to minimize Age-of-Updates (AoU) for time-sensitive IoT data. Using a probabilistic update model and convex optimization, the approach outperforms binary association methods.'
date: 2023-5-28
venue: '2023 IEEE International Conference on Communications Workshops (ICC Workshops)'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Ndiaye, M. N., Bergou, E. H., & El Hammouti, H. (2023, May). Muti-agent proximal policy optimization for data freshness in UAV-assisted networks. In <i>2023 IEEE International Conference on Communications Workshops (ICC Workshops)</i> (pp. 1920-1925). IEEE.'
---

Unmanned aerial vehicles (UAVs) have been proposed as a promising technology to collect data from IoT devices and relay it to the network. In this work, we are interested in scenarios where the data is updated periodically, and the collected updates are time-sensitive. In particular, the data updates may lose their value if they are not collected and analyzed timely. To maximize the data freshness, we optimize a new performance metric, namely the Age-of-Updates (AoU). Our objective is to carefully schedule the UAVs hovering positions and the users' association so that the AoU is minimized. Unlike existing works where the association parameters are considered as binary variables, we assume that devices send their updates according to a probability distribution. As a consequence, instead of optimizing a deterministic objective function, the objective function is replaced by an expectation over the probability distribution. The expected AoU is therefore optimized under quality of service and energy constraints. The original problem being non-convex, we propose an equivalent convex optimization that we solve using an interior-point method. Our simulation results show the performance of the proposed approach against a binary association.
