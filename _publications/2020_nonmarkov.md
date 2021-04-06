---
title: 'Non-Markov Policies to Reduce Sequential Failures in Robot Bin Picking'
authors: 'Kate Sanders, Michael Danielczuk, Jeffrey Mahler, Ajay Tanwani, Ken Goldberg'
venue: '2020 IEEE 16th International Conference on Automation Science and Engineering (CASE)'
date: 2020-8-20
category: 'published'
pdf: '2018-suction.pdf'
teaser: '2020-nonmarkov.png'
permalink: /publication/2020-nonmarkov
collection: publications
---

Abstract
-------
A new generation of automated bin picking systems using deep learning is evolving to support increasing demand for e-commerce. To accommodate a wide variety of products, many automated systems include multiple gripper types and/or tool changers. However, for some objects, sequential grasp failures are common: when a computed grasp fails to lift and remove the object, the bin is often left unchanged; as the sensor input is consistent, the system retries the same grasp over and over, resulting in a significant reduction in mean successful picks per hour (MPPH). Based on an empirical study of sequential failures, we characterize a class of “sequential failure objects” (SFOs) - objects prone to sequential failures based on a novel taxonomy. We then propose three non-Markov picking policies that incorporate memory of past failures to modify subsequent actions. Simulation experiments on SFO models and the EGAD dataset suggest that the non-Markov policies significantly outperform the Markov policy in terms of the sequential failure rate and MPPH. In physical experiments on 50 heaps of 12 SFOs the most effective Non-Markov policy increased MPPH over the Dex-Net Markov policy by 107%.
