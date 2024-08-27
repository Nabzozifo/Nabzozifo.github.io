---
title: "Age-of-Information in UAV-assisted Networks: a Decentralized Multi-Agent Optimization"
collection: publications
permalink: /publication/2024-4-21-paper-number-1
excerpt: 'This paper optimizes UAV trajectories and IoT device selection to minimize weighted Age-of-Information (AoI) using Mixed-Integer Nonlinear Programming (MINLP). It employs a distributed Multi-Agent Reinforcement Learning (MARL) approach for near-centralized performance with lower communication overhead.'
date: 2024-4-21
venue: '2024 IEEE Wireless Communications and Networking Conference (WCNC)'
paperurl: 'http://Nabzozifo.github.io/files/paper1.pdf'
citation: 'Ndiaye, M. N., Bergou, E. H., & El Hammouti, H. (2024, April). Age-of-Information in UAV-assisted Networks: a Decentralized Multi-Agent Optimization. In 2024 <i>IEEE Wireless Communications and Networking Conference (WCNC)</i> (pp. 1-6). IEEE.).'
---

Unmanned aerial vehicles (UAVs) are a highly promising technology with diverse applications in wireless networks. One of their primary uses is the collection of time-sensitive data from Internet of Things (IoT) devices. In UAV-assisted networks, the Age-of-Information (AoI) serves as a fundamental metric for quantifying data timeliness and freshness. In this work, we are interested in a generalized AoI formulation, where each packet's age is weighted based on its generation time. Our objective is to find the optimal UAVs' trajectories and the subsets of selected devices such that the weighted AoI is minimized. To address this challenge, we formulate the problem as a Mixed-Integer Nonlinear Programming (MINLP), incorporating time and quality of service constraints. To efficiently tackle this complex problem and minimize communication overhead among UAVs, we propose a distributed approach. This approach enables drones to make independent decisions based on locally acquired data. Specifically, we reformulate our problem such that our objective function is easily decomposed into individual rewards. The reformulated problem is solved using a distributed implementation of Multi-Agent Reinforcement Learning (MARL). Our empirical results show that the proposed decentralized approach achieves results that are nearly equivalent to a centralized implementation with a notable reduction in communication overhead.
