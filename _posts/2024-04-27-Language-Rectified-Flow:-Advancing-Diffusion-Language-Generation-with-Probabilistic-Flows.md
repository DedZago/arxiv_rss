---
layout: post
title: "Language Rectified Flow: Advancing Diffusion Language Generation with Probabilistic Flows"
date: 2024-04-27
author: Shujian Zhang, Lemeng Wu, Chengyue Gong, Xingchao Liu
tags: stat.ML
---

Recent works have demonstrated success in controlling sentence attributes ($e.g.$, sentiment) and structure ($e.g.$, syntactic structure) based on the diffusion language model. A key component that drives theimpressive performance for generating high-quality samples from noise is iteratively denoise for thousands of steps. While beneficial, the complexity of starting from the noise and the learning steps has limited its implementation to many NLP real-world applications. This paper proposes Language Rectified Flow ({\ours}). Our method is based on the reformulation of the standard probabilistic flow models. Language rectified flow learns (neural) ordinary differential equation models to transport between the source distribution and the target distribution, hence providing a unified and effective solution to generative modeling and domain transfer. From the source distribution, our language rectified flow yields fast simulation and effectively decreases the inference time. Experiments on three challenging fine-grained control tasks and multiple high-quality text editing show that our method consistently outperforms its baselines. Extensive experiments and ablation studies demonstrate that our method can be general, effective, and beneficial for many NLP tasks.

[Read more](https://arxiv.org/abs/2403.16995)