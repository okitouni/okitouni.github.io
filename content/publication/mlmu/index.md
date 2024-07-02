---
title: "The Factorization Curse: Which Tokens You Predict Underlie the Reversal Curse and More" 
authors:
- admin
- Niklas Nolte
- Diane Bouchacourt
- Adina Williams
- Mike Rabbat
- Mark Ibrahim

date: "2024-06-01T00:00:00Z"
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

abstract: Left-to-right autogressive transformers have shown impressive capabilities but still suffer from fundamental isses which stem from their inability to use their training data perfectly. We argue that LLMs can absorb a lot more information from a given training sample provided they are trained with stronger objectives than next token prediction. We propose factorization training as a fix for the reversal curse and show that it can encourage transformers to learn how to plan much better than the standard next token objective. The key insight is that training models to predict many tokens ahead (or many tokens backward) can unlock new capabilities and solve some of the limitations of left-to-right transformers.

# Summary. An optional shortened abstract.
summary: Training transformers to predict "any-to-any" as opposed to just next token solves the reversal curse and can improve planning capabilites. 

tags:
- Deep Learning 
featured: true

links:
- name: ArXiv
  url: 'https://arxiv.org/pdf/2406.05183' 
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
{{% callout note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
-->