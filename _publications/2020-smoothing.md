---
title: 'Deep Imitation Learning of Sequential Fabric Smoothing From an Algorithmic Supervisor'
authors: 'Daniel Seita, Aditya Ganapathi, Ryan Hoque, Minho Hwang, Edward Cen, Ajay Kumar Tanwani, Ashwin Balakrishna, Brijen Thananjeyan, Jeffrey Ichnowski, Nawid Jamali, Katsu Yamane, Soshi Iba, John F. Canny, Ken Goldberg'
venue: 'International Conference on Intelligent Robots and Systems (IROS)'
date: 2020-10-25
category: 'accepted'
pdf: '2020-smoothing.pdf'
bibtex: '2020-smoothing.bib'
teaser: '2020-smoothing.png'
permalink: /publication/2020-smoothing
collection: publications
---

Abstract
-------
Sequential pulling policies to flatten and smooth fabrics have applications from surgery to manufacturing to home tasks such as bed making and folding clothes. Due to the complexity of fabric states and dynamics, we apply deep imitation learning to learn policies that, given color (RGB), depth (D), or combined color-depth (RGBD) images of a rectangular fabric sample, estimate pick points and pull vectors to spread the fabric to maximize coverage. To generate data, we develop a fabric simulator and an algorithmic supervisor that has access to complete state information. We train policies in simulation using domain randomization and dataset aggregation (DAgger) on three tiers of difficulty in the initial randomized configuration. We present results comparing five baseline policies to learned policies and report systematic comparisons of RGB vs D vs RGBD images as inputs. In simulation, learned policies achieve comparable or superior performance to analytic baselines. In 180 physical experiments with the da Vinci Research Kit (dVRK) surgical robot, RGBD policies trained in simulation attain coverage of 83% to 95% depending on difficulty tier, suggesting that effective fabric smoothing policies can be learned from an algorithmic supervisor and that depth sensing is a valuable addition to color alone. Supplementary material is available at https://sites.google.com/view/fabric-smoothing.
