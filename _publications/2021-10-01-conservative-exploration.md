---
title: "Conservative Exploration for Policy Optimization via Off-Policy Evaluation"
collection: publications
permalink: /publication/2021-10-01-conservative-exploration
excerpt: 'This paper is about conservative exploration, where the learner must at least be able to guarantee its performance is at least as good as a baseline policy.'
date: 2021-10-01
venue: 'ArXiv preprint'
---

A precondition for the deployment of a Reinforcement Learning agent to a real- world system is to provide guarantees on the learning process. While a learning algorithm will eventually converge to a good policy, there are no guarantees on the performance of the exploratory policies. We study the problem of conservative exploration, where the learner must at least be able to guarantee its performance is at least as good as a baseline policy. We propose the first conservative provably efficient model-free algorithm for policy optimization in continuous finite-horizon problems. We leverage importance sampling techniques to counterfactually evalu- ate the conservative condition from the data self-generated by the algorithm. We derive a regret bound and show that (w.h.p.) the conservative constraint is never violated during learning. Finally, we leverage these insights to build a general schema for conservative exploration in DeepRL via off-policy policy evaluation techniques. We show empirically the effectiveness of our methods.

[Download paper here](http://pauldaoudi.github.io/files/Conservative_Exploration.pdf)

Recommended citation: Paul Daoudi, Matthias Formoso, Othman Gaizi, Achraf Aziz, Evrard Garcelon (2021). "Conservative Exploration for Policy Optimization via Off-Policy Evaluation" <i>ArXiv preprint</i>. 1(1).