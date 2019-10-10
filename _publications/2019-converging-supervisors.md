---
title: 'On-Policy Robot Imitation Learning from a Converging Supervisor'
authors: 'Ashwin Balakrishna*, Brijen Thananjeyan*, Jonathan Lee, Felix Li, Arsh Zahed, Joseph E. Gonzalez, Ken Goldberg'
venue: 'Conference on Robot Learning (CoRL) - Oral Presentation'
date: 2019-10-30
category: 'accepted'
pdf: '2019-converging-supervisors.pdf'
teaser: '2019-converging-supervisors.png'
permalink: /publication/2019-converging-supervisors
collection: publications
---

Abstract
-------
Existing on-policy imitation learning algorithms, such as DAgger, assume access to a fixed supervisor. However, there are many settings where the supervisor may evolve during policy learning, such as a human performing a novel task or an improving algorithmic controller. We formalize imitation learning from a “converging supervisor” and provide sublinear static and dynamic regret guarantees against the best policy in hindsight with labels from the converged supervisor, even when labels during learning are only from intermediate supervisors. We then show that this framework is closely connected to a class of reinforcement learning (RL) algorithms known as dual policy iteration (DPI), which alternate between training a reactive learner with imitation learning and a model-based supervisor with data from the learner. Experiments suggest that when this framework is applied with the state-of-the-art deep model-based RL algorithm PETS as an improving supervisor, it outperforms deep RL baselines on continuous control tasks and provides up to an 80-fold speedup in policy evaluation.
