---
layout: post
title: Self Introduction - PhD Applicant
subtitle: From Physics to Quantitative Finance, now pursuing AI research
cover-img: /assets/img/selfie1.jpg
gh-repo: zhangqunying/phd-application
gh-badge: [star, fork, follow]
tags: [self-introduction, phd, ai, ml, robotics]
share-img: /assets/img/selfie2.jpg
comments: false
mathjax: true
author: Qunying Zhang
---

{: .box-success}
Thank you for visiting my page! This serves as a brief self-introduction as part of my PhD application materials.

**About Me**

I am Qunying Zhang, currently working as a Quantitative Researcher in Boston. I have a multidisciplinary academic background in **Physics** (B.Sc, Shanghai Jiao Tong University) and **Computational Finance** (M.Sc, Carnegie Mellon University). Over the past five years, I have been applying advanced quantitative methods and machine learning models to financial data in the asset management industry.

## My Research Interests

While my professional work has been centered around quantitative finance, my long-term passion lies in **Machine Learning**, particularly at the intersection of **AI, Embodied Intelligence, and Robotics**. My research interests include:

- Representation learning for high-dimensional data
- Vision-language models and multimodal learning
- Reinforcement learning and imitation learning for embodied AI
- World modeling and grounded reasoning
- Large language models for scientific discovery

{: .box-note}
**Note:** I aspire to contribute to fundamental research that enables AI systems to better understand not just textual data, but also the underlying logic, physical laws, and causal structures of the real world.

## My Journey So Far

I first encountered Machine Learning during my undergraduate research at Prof. Alexandre Thiéry’s lab, where I explored **Generative Adversarial Networks (GANs)** and **Variational Autoencoders (VAEs)** for medical image analysis. Later, I completed my undergraduate thesis on **image deblurring algorithms**.

During my master's study at CMU, I was deeply fascinated by **dimensionality reduction**, **representation learning**, and **theoretical aspects of ML**. More recently, in my industry work, I have applied **Large Language Models (LLMs)** to process financial texts, earning calls, and industrial news data. However, I find myself unsatisfied with simply applying models — I hope to contribute to the design and development of next-generation AI models that generalize across modalities and tasks.

## A Table Summary

| Degree | Institution | Field |
| :------ |:--- | :--- |
| B.Sc | Shanghai Jiao Tong University | Physics |
| M.Sc | Carnegie Mellon University | Computational Finance |
| Current | Boston | Quantitative Researcher |

## Math Demonstration (LaTeX)

For example, my interest in generative modeling includes solving equations such as:
$$\min_G \max_D \mathbb{E}_{x \sim p_\text{data}}[\log D(x)] + \mathbb{E}_{z \sim p_z}[\log(1 - D(G(z)))]$$

## Sample Code Snippet

```python
import torch
from transformers import AutoModel

model = AutoModel.from_pretrained("bert-base-uncased")
output = model(**inputs)
