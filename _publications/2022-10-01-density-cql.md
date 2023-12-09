---
title: "Density Estimation for Conservative Q-Learning"
collection: publications
permalink: /publication/2022-10-01-density-cql
excerpt: 'Study the Offline Reinforcement Learning setting, and introduce Density Conservative Q-Learning (D- CQL).'
date: 2022-10-01
venue: 'Generalizable Policy Learning in the Physical World Workshop (ICLR 2022)'
---

Offline Reinforcement Learning algorithms aim at learning the best policy from a batch of data without interacting with the environment. Within this setting, one difficulty is to correctly assess the value of state-action pairs that are far from the dataset. Indeed, the lack of information may provoke an overestimation of the value function, leading to non-desirable behaviors. A compromise between enhancing the behaviour policy's performance and staying close to it must be found. To alleviate this issue, most existing approaches introduce a regularization term to favor state-action pairs from the dataset. In this paper, we refine this idea by estimating the density of these state-action pairs to distinguish neighbourhoods. The resulting regularization guides the policy toward meaningful unseen regions, improving the learning process. We hence introduce Density Conservative Q-Learning (D-CQL), a offline-RL algorithm with strong theoretical guarantees that carefully penalizes the value function based on the amount of information collected in the state-action space. The performance of our approach is outlined on many classical benchmark in offline-RL.

[Download paper here](http://pauldaoudi.github.io/files/DCQL.pdf)

Recommended citation: Paul Daoudi, Ludovic Dos Santos, Merwan Barlier, Aladin Virmaux. (2022). "Density Estimation for Conservative Q-Learning" <i>Generalizable Policy Learning in the Physical World Workshop (ICLR 2022)</i>. 1(2)
