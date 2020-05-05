---
title: 'VisuoSpatial Foresight for Multi-Step, Multi-Task Fabric Manipulation'
authors: 'Ryan Hoque*, Daniel Seita*, Ashwin Balakrishna, Aditya Ganapathi, Ajay Kumar Tanwani, Nawid Jamili, Katsu Yamane, Soshi Iba, Ken Goldberg'
venue: 'Robotics Science and Systems (RSS)'
date: 2020-07-12
category: 'accepted'
pdf: '2020-vis-mpc-fabric.pdf'
bibtex: '2020-vis-mpc-fabric.bib'
teaser: '2020-vis-mpc-fabric.png'
permalink: /publication/2020-vis-mpc-fabric
collection: publications
---

Abstract
-------
Robotic fabric manipulation has applications in cloth and cable management, senior care, surgery and more. Existing fabric manipulation techniques, however, are designed for specific tasks, making it difficult to generalize across different but related tasks. We address this problem by extending the recently proposed Visual Foresight framework to learn fabric dynamics, which can be efficiently reused to accomplish a variety of different fabric manipulation tasks with a single goal- conditioned policy. We introduce VisuoSpatial Foresight (VSF), which extends prior work by learning visual dynamics on domain randomized RGB images and depth maps simultaneously and completely in simulation. We experimentally evaluate VSF on multi-step fabric smoothing and folding tasks both in simulation and on the da Vinci Research Kit (dVRK) surgical robot without any demonstrations at train or test time. Furthermore, we find that leveraging depth significantly improves performance for cloth manipulation tasks, and results suggest that leveraging RGBD data for video prediction and planning yields an 80% improvement in fabric folding success rate over pure RGB data. Supplementary material is available at https://sites.google.com/view/fabric-vsf/.
