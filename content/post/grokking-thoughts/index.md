---
title: Some thoughts on Grokking  
subtitle: "[Towards Understanding Grokking: an effective theory of representation learning]"
summary: "A short blog post on \"Towards Understanding Grokking: an effective theory of representation learning\"" 
authors:
- admin
tags: []
categories: []
date: "2021-09-21T00:00:00Z"
# lastMod: "2019-09-05T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
This page is a work-in-progress.
## Animations

The example below is an animation of the first Figure from [our Grokking paper]({{< relref "/publication/Grok" >}}). 
We visualize the first two principal components of the embeddings of a transformer model trained on the task of addition modulo 59. An interesting feature is that generalization seems to coincide with learnning an ordered representation of the embeddings around a circle (much like how a human would reason about modular addition).
{{< video src="modular-addition59-deep_pca12.mp4" controls="yes" >}}
What is more intriguing is that this "perfect" representation actually exists very early (up to local ordering of embeddings). In the animation below, the axes are fixed to the first two principal components **at the end of training**. This seems to suggest that the network picks a good representation at initialization and prunes away the noise throughout training. As one might expect, this "lottery ticket" found at initialization gets better (*i.e.*, closer to the perfect representation) the wider the model dimension.
{{< video src="modular-addition59-deep_pca12_fixed.mp4" controls="yes" >}}
*N.b.*, it is not necessary to get a perfect ordering in the first two principal components for generalization to occur. In some cases, the circle can be "spread out" over many components at different frequencies. For instance, the circle can be ordered modulo 2 in the first two principal components such that there are two degenerate cicles on top of each other. But this multiplicity is broken in lower principal components.