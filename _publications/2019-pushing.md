---
title: 'Automating Planar Object Singulation by Linear Pushing with Single-point and Multi-point Contacts'
authors: 'Zisu Dong, Sanjay Krishnan, Sona Dolasia, Ashwin Balakrishna, Michael Danielczuk, Ken Goldberg'
venue: 'Conference on Automation Science and Engineering'
date: 2019-08-22
category: 'published'
pdf: '2019-pushing.pdf'
bib: '2019-pushing.bib'
teaser: '2019-pushing.png'
permalink: /publication/2019-pushing
collection: publications
---

Abstract
-------
Singulation is useful for manufacturing, logistics, and service applications; we consider the problem in a planar setting. We propose a novel O(n(n + v)) linear push policy (n denotes the number of objects, v denotes the maximum number of vertices per object), ClusterPush, that can be efficiently computed using clustering. To evaluate the policy, we define singulation distance as the average pairwise distance of polygon centroids given random arrangements of 2D polygonal objects on a surface, and seek pushing policies that can maximize singulation distance. When compared with a brute force evaluation of all candidate pushes in Box2D simulator using 50,000 pushing scenarios, ClusterPush achieves 70% of the singulation distance achieved using brute force and is 2000x faster. ClusterPush also improves on previous pushing policies and can be used for multi-point pushes with two-point and edge (infinite-point) contacts. Compared with pushes with single- point contacts using ClusterPush, pushes with two-point and edge contacts improve singulation by 7% and 13% respectively. In physical experiments conducted with an ABB YuMi robot on 40 sets of 3-7 blocks, ClusterPush increases singulation distance by 15-30%, outperforming the next best policy by 24% on average. Data and code are available at https: //github.com/Jekyll1021/MultiPointPushing.
