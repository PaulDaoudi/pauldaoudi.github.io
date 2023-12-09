---
title: "A Trust Region Approach for Few-Shot Simulation-to-Reality Reinforcement Learning"
collection: publications
permalink: /publication/2024-10-01-sim-to-real
excerpt: 'Building on Trust-Region algorithms, this paper proposes a new agent for the Few-Shot Off-Dynamics setting, outperforming the current algorithms in numerous benchmarks.'
date: 2024-10-01
venue: 'Proceedings of the 22nd International Conference on Autonomous Agents and Multiagent Systems (AAMAS 2023)'
---

Simulation-to-Reality Reinforcement Learning (Sim-to-Real RL) seeks to use simulations to minimize the need for extensive real-world interactions. Specifically, in the few-shot off-dynamics setting, the goal is to acquire a simulator-based policy despite a dynamics mismatch that can be effectively transferred to the real-world using only a handful of real-world transitions. In this context, conventional RL agents tend to exploit simulation inaccuracies resulting in policies that excel in the simulator but underperform in the real environment. To address this challenge, we introduce a novel approach that incorporates a penalty to constrain the trajectories induced by the simulator-trained policy inspired by recent advances in Imitation Learning and Trust Region based RL algorithms. We evaluate our method across various environments representing diverse Sim-to-Real conditions, where access to the real environment is extremely limited. These experiments include high-dimensional systems relevant to real-world applications. Across most tested scenarios, our proposed method demonstrates performance improvements compared to existing baselines.


[Download paper here](http://academicpages.github.io/files/RLLG.pdf)

Recommended citation: Paul Daoudi, Bogdan Robu, Christophe Prieur, Merwan Barlier, Ludovic Dos Santos. (2024). "A Trust Region Approach for Few-Shot Simulation-to-Reality Reinforcement Learning" <i>ArXiv preprint</i>. 1(5).