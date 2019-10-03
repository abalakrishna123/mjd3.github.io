---
title: ' Reliable Real-Time Signal/Noise Discrimination with Deep and Shallow Machine Learning Classifiers'
authors: 'Men-Andrin Meier, Zachary Ross, Anshul Ramachandran, Ashwin Balakrishna, Suraj Nair, Peter Kundzicz, Zefeng Li, Egill Hauksson, Jennifer Andrews'
venue: 'Machine Learning for Geophysical & Geochemical Signals Workshop, NeurIPS'
date: 2018-12-03
category: 'published'
pdf: '2018-earthquake-nips.pdf'
teaser: '2018-earthquake-nips.png'
permalink: /publication/2018-earthquake-nips
collection: publications
---

Abstract
-------
In Earthquake Early Warning (EEW), every sufficiently impulsive signal is potentially the first evidence for an unfolding large earthquake. More often than not, however, impulsive signals are mere nuisance signals. One of the most fundamental - and difficult - tasks in EEW is to rapidly and reliably discriminate between real local earthquake signals, and any kind of other signal. Current EEW systems struggle to avoid discrimination errors, and suffer from false and missed alerts. In this study we show how machine learning classifiers can strongly improve real-time signal/noise discrimination. We develop and compare a series of non-linear classifiers with variable architecture depths, including random forests, fully connected, convolutional (CNN, Figure 1) and recurrent neural networks, and a generative adversarial network (GAN). We train all classifiers on the same waveform data set that includes 374k 3-component local earthquake records with magnitudes M3.0-9.1, and 946k impulsive noise signals. We find that the deep architectures significantly outperform the more simple ones. Using 3s long waveform snippets, the CNN and the GAN classifiers both reach 99.5% precision and 99.3% recall on an independent validation data set. Our results suggest that machine learning classifiers can strongly improve the reliability and speed of EEW alerts.
