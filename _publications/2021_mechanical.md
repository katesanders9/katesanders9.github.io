---
title: 'Mechanical Search on Shelves using Lateral Access X-RAY'
authors: 'Huang Huang, Marcus Dominguez-Kuhne, Vishal Satish, Michael Danielczuk, Kate Sanders, Jeffrey Ichnowski, Andrew Lee, Anelia Angelova, Vincent Vanhoucke, Ken Goldberg'
venue: '2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
date: 2021-03-05
category: 'under review'
pdf: '2019-sdmaskrcnn.pdf'
teaser: '2021-mechanical.png'
permalink: /publication/2021-mechanical
collection: publications
---

Abstract
-------
Efficiently finding an occluded object in a lateral access environment such as a shelf or cabinet arises in many contexts such as warehouses, retail, healthcare, shipping, and homes. While this mechanical search problem has commonly been studied in the overhead access environment, the lateral access setting  introduces novel constraints both on the poses of the objects and on available grasp actions that can render pushing actions more efficient in this setting. We propose LAX-RAY (Lateral Access maXimal Reduction in support Area of occupancY distribution): a system that combines a target object occupancy distribution predictions with a mechanical search policy that sequentially pushes occluding objects to efficiently reveal the target. For scenarios with extruded polygonal objects occluding a known stationary target, we introduce two lateral access search policies that encode a history of predicted target distributions and can plan up to three actions into the future. We evaluate these policies both in 200 random shelf environments per policy using a novel First-Order Shelf Simulator (FOSS) and in 5 physical shelf environments using a Fetch robot with an embedded PrimeSense RGBD Camera and an attached blade, where they outperform baselines by up to 25% and up to 60% in physical experiments as the number of occluding objects increases. Additionally, the two-step prediction policy is the highest performing in simulation with an 87.3% average success rate, suggesting a tradeoff between future information and prediction errors. Code, videos, and supplementary material can be found at [https://sites.google.com/berkeley.edu/lax-ray](https://sites.google.com/berkeley.edu/lax-ray).