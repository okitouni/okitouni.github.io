---
title: "From Neurons to Neutrons: A Case Study in Interpretability" 
authors:
- admin
- Niklas Nolte
- Victor Samuel Perez-Diaz
- Sokratis Trifinopoulos 
- Mike Williams

date: "2024-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Mechanistic Interpretability (MI) promises a path toward fully understanding how neural networks make their predictions. Prior work demonstrates that even when trained to perform simple arithmetic, models can implement a variety of algorithms (sometimes concurrently) depending on initialization and hyperparameters. Does this mean neuron-level interpretability techniques have limited applicability? We argue that high-dimensional neural networks can learn low-dimensional representations of their training data that are useful beyond simply making good predictions. Such representations can be understood through the mechanistic interpretability lens and provide insights that are surprisingly faithful to human-derived domain knowledge. This indicates that such approaches to interpretability can be useful for deriving a new understanding of a problem from models trained to solve it. As a case study, we extract nuclear physics concepts by studying models trained to reproduce nuclear data.

# Summary. An optional shortened abstract.
summary: Transformers trained on nuclear physics data learn representations close to human-derived nuclear theory. Mechanistic interpretability of neural networks can be a path towards new scientific understanding.

tags:
- Mech Interp
featured: false

links:
- name: ArXiv
  url: 'https://arxiv.org/pdf/2405.17425' 
# url_code: 'https://github.com/niklasnolte/MonotOneNorm'
# url_dataset: './featured.jpg'
# url_poster: 'https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_86_poster.png'
# - name: NeurIPS 2022
  # url: https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_86.pdf
# url_pdf: https://arxiv.org/abs/2205.10343
# url_project: ''
# url_slides: ''
#url_source: '#'
# url_video: 'https://youtu.be/ASqP0tcU6Ag'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#   caption: "DiSK architecture on the left and key for the diagram on the right. In this example, the model is tasked to predict the masked value for the 'weight.value' property."
  focal_point: "Center"
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
