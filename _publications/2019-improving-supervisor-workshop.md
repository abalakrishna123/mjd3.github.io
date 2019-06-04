---
title: 'On-Policy Imitation Learning from an Improving Supervisor'
authors: 'Ashwin Balakrishna*, Brijen Thananjeyan*,  Jonathan Lee, Arsh Zahed, Felix Li, Joseph E. Gonzalez, Ken Goldberg'
venue: 'Real World Sequential Decision Making Workshop at the International Conference on Machine Learning (ICML)'
date: 2019-06-14
category: 'published'
pdf: '2019-improving-supervisor-workshop.pdf'
teaser: '2019-improving-supervisor-workshop-new.png'
permalink: /publication/2019-improving-supervisor-workshop
collection: publications
---

Abstract
-------
Most on-policy imitation algorithms, such as DAgger, are designed for learning with a fixed supervisor. However, there are many settings in which the supervisor improves during policy learning, such as when the supervisor is a human performing a novel task or an improving algorithmic controller. We consider learning from an “improving supervisor” and derive a bound on the static-regret of online gradient descent when a converging supervisor policy is used. We present an on-policy imitation learning algorithm, Follow the Improving Teacher (FIT), which uses a deep model-based reinforcement learning (deepMBRL) algorithm to provide the sample complexity benefits of model-based methods but enable faster training and evaluation via distillation into a reactive controller. We evaluate FIT with experiments on the Reacher and Pusher MuJoCodomains using the deep MBRL algorithm, PETS, as the improving supervisor. To the best of our knowledge, this work is the first to formally consider the setting of an improving supervisor in on-policy imitation learning.
