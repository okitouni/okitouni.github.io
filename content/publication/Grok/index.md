---
title: "Towards Understanding Grokking: An Effective Theory of Representation Learning" 
authors:
- admin
- Ziming Liu
- Eric Michaud
- Niklas Nolte
- Mike Williams
- Max Tegmark

date: "2022-08-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "We aim to understand grokking, a phenomenon where models generalize long after overfitting their training set. We present both a microscopic analysis anchored by an effective theory and a macroscopic analysis of phase diagrams describing learning performance across hyperparameters. We find that generalization originates from structured representations whose training dynamics and dependence on training set size can be predicted by our effective theory in a toy setting. We observe empirically the presence of four learning phases: comprehension, grokking, memorization, and confusion. We find representation learning to occur only in a "Goldilocks zone" (including comprehension and grokking) between memorization and confusion. Compared to the comprehension phase, the grokking phase stays closer to the memorization phase, leading to delayed generalization. The Goldilocks phase is reminiscent of "intelligence from starvation" in Darwinian evolution, where resource limitations drive discovery of more efficient solutions. This study not only provides intuitive explanations of the origin of grokking, but also highlights the usefulness of physics-inspired tools, e.g., effective theories and phase diagrams, for understanding deep learning."

# Summary. An optional shortened abstract.
summary: We develop an effective theory to understand transformer architectures’ ability to generalize on arithmetic datasets. The
theory links generalization to a particular structured representation of the embeddings and predicts a range of phenomena
associated with *grokking*, or delayed generalization. Moreover, we show that grokking is one of four different phases of
learning and can be avoided with proper hyper-parameter tuning.

tags:
- Deep Learning 
featured: false

links:
- name: To appear in NeurIPS 2022
  # url: https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_86.pdf
url_pdf: https://arxiv.org/abs/2205.10343
# url_code: 'https://github.com/niklasnolte/MonotOneNorm'
#url_dataset: './featured.jpg'
# url_poster: 'https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_86_poster.png'
url_project: ''
url_slides: ''
#url_source: '#'
# url_video: 'https://youtu.be/ASqP0tcU6Ag'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Visualization of the first two principal components of the learned input embeddings at
different training stages of a transformer learning modular addition. We observe that generalization
coincides with the emergence of structure in the embeddings.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
<!--
{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
-->
