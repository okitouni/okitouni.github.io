---
title: "Robust and Provably Monotonic Networks" 
authors:
- admin
- Niklas Nolte
- Mike Williams

date: "2021-08-07T00:00:00Z"
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

abstract: The Lipschitz constant of the map between the input and output space represented by a neural network is a natural metric for assessing the robustness of the model. We present a new method to constrain the Lipschitz constant of dense deep learning models that can also be generalized to other architectures. The method relies on a simple weight normalization scheme during training that ensures the Lipschitz constant of every layer is below an upper limit specified by the analyst. A simple residual connection can then be used to make the model monotonic in any subset of its inputs, which is useful in scenarios where domain knowledge dictates such dependence. Examples can be found in algorithmic fairness requirements or, as presented here, in the classification of the decays of subatomic particles produced at the CERN Large Hadron Collider. Our normalization is minimally constraining and allows the underlying architecture to maintain higher expressiveness compared to other techniques which aim to either control the Lipschitz constant of the model or ensure its monotonicity. We show how the algorithm was used to train a powerful, robust, and interpretable discriminator for heavy-flavor decays in the LHCb realtime data-processing system. 

# Summary. An optional shortened abstract.
summary: We develop a novel architecture with an exact bound on its Lipschitz constant and which can be made monotonic in any subset of its features. This inductive bias is especially important for fairness and interpretability considerations.

tags:
- Deep Learning 
featured: false

links:
- name: NeurIPS Abstract
  url: https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_86.pdf
url_pdf: https://arxiv.org/abs/2112.00038
url_code: 'https://github.com/niklasnolte/MonotOneNorm'
#url_dataset: './featured.jpg'
url_poster: 'https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_86_poster.png'
url_project: ''
url_slides: ''
#url_source: '#'
# url_video: 'https://youtu.be/ASqP0tcU6Ag'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Training monotonic and unconstrained models using four realizations (purple data points) of toy data which is assumed to be monotonic from domain knowledge. 
    The shaded regions represent the (top) extrapolation or (bottom) interpolation regions of interest, where training data are absent. 
    The unconstrained models exhibit overfitting of the noise and non-monotonic behavior, and when extrapolating or interpolating into regions where training data were absent, these models exhibit highly undesirable and unpredictable behavior.    
    Conversely, the monotonic Lipschitz models always produce a monotonic function, even in scenarios where the noise is strongly suggestive of non-monotonic behavior.  '
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
