---
title: "Composed Image Retrieval Using Contrastive Learning and Task-Oriented CLIP-Based Features"
authors:
  - "Alberto Baldrati"
  - me
  - "Tiberio Uricchio"
  - "Alberto Del Bimbo"
date: "2023-10-01T00:00:00Z"
publishDate: "2023-10-01T00:00:00Z"
publication_types: ["article-journal"]
publication: "ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM)"
publication_short: ""
abstract: "Given a query composed of a reference image and a relative caption, the Composed Image Retrieval goal is to retrieve images visually similar to the reference one that integrates the modifications expressed by the caption. Given that recent research has demonstrated the efficacy of large-scale vision and language pre-trained (VLP) models in various tasks, we rely on features from the OpenAI CLIP model to tackle the considered task. We initially perform a task-oriented fine-tuning of both CLIP encoders using the element-wise sum of visual and textual features. Then, in the second stage, we train a Combiner network that learns to combine the image-text features integrating the bimodal information and providing combined features used to perform the retrieval. We use contrastive learning in both stages of training. Starting from the bare CLIP features as a baseline, experimental results show that the task-oriented fine-tuning and the carefully crafted Combiner network are highly effective and outperform more complex state-of-the-art approaches on FashionIQ and CIRR, two popular and challenging datasets for composed image retrieval. Code and pre-trained models are available at ."
summary: ""
featured: false
hugoblox:
  ids:
    doi: 10.1145/3617597
links:
  - type: source
    url: "https://doi.org/10.1145/3617597"
---
