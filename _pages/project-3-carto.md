---
layout: page
title: Project
permalink: projects/cartograph/
---

## Cartograph: Unlocking Thematic Cartography Through Semantic Enhancement

[Github](https://github.com/shilad/cartograph-alg)

I have been working with Prof. [Shilad Sen](http://www.shilad.com/) on the [Cartograph](cartograph.info) system which visualizes non-spatial thematic information in the form of interactive geographical maps. The maps help people explore meaningful relationships among data points in a way that is familiar to them - geographically and spatially. As part of a research team of four undergraduate students, I examined three main algorithms: embedding, clustering, and labeling in latent spaces. Based on neural networks trained on Wikipedia, Cartograph’s map embedding reduces high-dimensional vector space for semantic interpretation to two-dimensional coordinate space for visualization. In order to improve users’ efficient exploration, we replaced the previous t-SNE dimension reduction method with a more robust UMAP algorithm, which lowers the run time from 24 hours to less than 30 minutes for 500,000 points. Also, we enhanced users’ perception of more homogenous clusters by minimizing a joint loss function in the high-dimensional, the low-dimensional, and the label-dimensional vector spaces. We conducted a study of 604 users on Amazon Mechanical Turk to understand the best labels assigned to each cluster that makes the most sense. In the end, I built automated pipelines that integrate the algorithms and developed a web-based interactive tool using signal processing and graph data structures in Python and JavaScript. Through this experience, I became more interested in InfoVis and designing human-centered interactive systems. 

