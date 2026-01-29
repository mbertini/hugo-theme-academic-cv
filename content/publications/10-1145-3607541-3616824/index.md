---
title: "4DSR-GCN: 4D Video Point Cloud Upsampling Using Graph Convolutional Networks"
authors:
  - "Lorenzo Berlincioni"
  - "Stefano Berretti"
  - me
  - "Alberto Del Bimbo"
date: "2023-01-01T00:00:00Z"
publishDate: "2023-01-01T00:00:00Z"
publication_types: ["paper-conference"]
publication: "Proc. of ACM International Conference on Multimedia (ACM MM) Workshops"
publication_short: ""
abstract: "Time varying sequences of 3D point clouds, or 4D point clouds, are now being acquired at an increasing pace in several applications (personal avatar representation, LiDAR in autonomous or assisted driving). In many cases, such volume of data is transmitted, thus requiring that proper compression tools are applied to either reduce the resolution or the bandwidth. In this paper, we propose a new solution for upscaling and restoration of time-varying 3D video point clouds after they have been heavily compressed. Our model consists of a specifically designed Graph Convolutional Network that combines Dynamic Edge Convolution and Graph Attention Networks for feature aggregation in a Generative Adversarial setting. We present a different way to sample dense point clouds with the intent to make these modules work in synergy to provide each node enough features about its neighbourhood in order to later on generate new vertices. Compared to other solutions in the literature that address the same task, our proposed model is capable of obtaining comparable results in terms of quality of the reconstruction, while using a substantially lower number of parameters (simeq 300KB), making our solution deployable in edge computing devices."
summary: ""
featured: false
hugoblox:
  ids:
    doi: 10.1145/3607541.3616824
links:
  - type: source
    url: "https://doi.org/10.1145/3607541.3616824"
---
