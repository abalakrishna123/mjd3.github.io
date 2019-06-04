---
title: 'Extending Deep Model Predictive Control with Safety Augmented Value Estimation from Demonstrations'
authors: 'Brijen Thananjeyan*, Ashwin Balakrishna*,  **Ugo Rosolia**, Felix Li, Rowan McAllister, Joseph E. Gonzalez, Sergey Levine, Francesco Borrelli, Ken Goldberg'
venue: 'Conference on Neural Information Processing Systems'
date: 2019-12-08
category: 'submitted'
pdf: '2019-saved.pdf'
teaser: '2019-saved.png'
permalink: /publication/2019-saved
collection: publications
---

Abstract
-------
Reinforcement learning (RL) for robotics is challenging due to the difficulty in hand-engineering a dense cost function, which can lead to unintended behavior, and dynamical uncertainty, which makes it hard to enforce constraints during learning. We address these issues with a new model-based reinforcement learning algorithm, safety augmented value estimation from demonstrations (SAVED), which uses supervision that only identifies task completion and a modest set of suboptimal demonstrations to constrain exploration and learn efficiently while handling complex constraints. We derive iterative improvement guarantees for SAVED under known stochastic nonlinear systems. We then compare SAVED with 3 state-of-the-art model-based and model-free RL algorithms on 6 standard simulation benchmarks involving navigation and manipulation and 2 real-world tasks on the da Vinci surgical robot. Results suggest that SAVED outperforms prior methods in terms of success rate, constraint satisfaction, and sample efficiency, making it feasible to safely learn complex maneuvers directly on a real robot in less than an hour. For tasks on the robot, baselines succeed less than 5% of the time while SAVED has a success rate of over 75% in the first 50 training iterations. For more information, see https://sites.google.com/view/safetyaugmentedvalueestimation/.
