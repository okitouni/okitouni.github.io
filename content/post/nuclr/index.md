---
title: "Reverse-engineering a Nuclear Physics model"
subtitle: "A Scientific Case for Mechanistic Interpretability"
summary: "A mechanistic interpretability effort that aims to reverse-engineer NuCLR, which accurately predicts nuclear properties and demonstrates an understanding of basic nuclear theory, to potentially derive new insights in nuclear physics."
authors:
- admin
tags: []
categories: []
date: "2023-06-21T00:00:00Z"
# lastMod: "2019-09-05T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: "Most important principal components of the neutron embedding representations from (left) early and (right) late in the training.
# The left panel shows that the most crucial aspects of the nuclear shell model, namely the shell structure, including the magic numbers, and
# the Pauli Exclusion Principle, arise already early in the training. (The Pauli principle is evident with the even (odd) numbers represented
# as negative (positve) values of PC2. The ends of the even chains of numbers are the magic numbers where each nuclear shell become full.)
# In the right panel, the even-odd split now occurs in PC dimension 4, hence is not shown. The shell structure has grown into 3-dimensional
# spirals, with the largest 4 magic numbers all occurring at local maxima in PC2 and each shell represented as one revolution around an
# approximately conic surface. Interpreting this spiral structure is ongoing work."
#   focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
[NuCLR](https://arxiv.org/pdf/2306.06099.pdf) can accurately predict many nuclear properties and generalizes well across tasks, indicating it has learned fundamental physics. Initial investigation reveals NuCLR has acquired some basic nuclear theory, including the Pauli Exclusion principle and magic numbers. Furthermore, NuCLR exhibits intriguing spiral embeddings for protons and neutrons. However, can we fully describe the mechanisms behind NuCLR's performance? This project aims to fully reverse engineer the NuCLR algorithm to potentially derive new physics insights.

The work is still in progress, but code is available [here](https://github.com/okitouni/NuCLR-MechInterp/tree/main).

## Visualization of the "nuclear" embeddings
One-hot encoded representations of proton number, neutron number, and task are concatenated and input to the first layer. The visualization shows the first three principal components of all observed proton-neutron combinations, with the first two components as x-y axes and the third as color.
{{< nuclr_plotly_firstlayer2d >}}

Here's a 3D version with the 4th principal component as color.
{{< nuclr_plotly_firstlayer3d >}}

<iframe 
    src="https://okitouni-streamlit-example-streamlit-app-ooy6wu.streamlit.app/?embed=true"
    height="1700"
    style="width:100%;border:none;"
  ></iframe>
