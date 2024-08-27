---
title: "Age-of-Updates optimization for UAV-assisted networks"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'The paper discusses unmanned aerial vehicles (UAVs) to collect and relay data from IoT devices to the network, focusing on scenarios where timely data updates are crucial.'
date: 2022-12-4
venue: 'IEEE Global Communications Conference'
paperurl: 'http://academicpages.github.io/files/paper4.pdf'
citation: 'Ndiaye, M. N., Bergou, E. H., Ghogho, M., & El Hammouti, H. (2022, December). Age-of-Updates optimization for UAV-assisted networks. In <i>GLOBECOM 2022-2022 IEEE Global Communications Conference</i> (pp. 450-455). IEEE.'
---

Unmanned aerial vehicles (UAVs) have been proposed as a promising technology to collect data from IoT devices and relay it to the network. In this work, we are interested in scenarios where the data is updated periodically, and the collected updates are time-sensitive. In particular, the data updates may lose their value if they are not collected and analyzed timely. To maximize the data freshness, we optimize a new performance metric, namely the Age-of-Updates (AoU). Our objective is to carefully schedule the UAVs hovering positions and the users’ association so that the AoU is minimized. Unlike existing works where the association parameters are considered as binary variables, we assume that devices send their updates according to a probability distribution. As a consequence, instead of optimizing a deterministic objective function, the objective function is replaced by an expectation over the probability distribution. The expected AoU is therefore
optimized under quality of service and energy constraints. The original problem being non-convex, we propose an equivalent convex optimization that we solve using an interior-point method. Our simulation results show the performance of the proposed approach against a binary association.
