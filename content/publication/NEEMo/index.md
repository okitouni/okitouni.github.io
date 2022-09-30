---
title: "NEEMo: Geometric Fitting using Neural Estimation of the Energy Mover's Distance" 
authors:
- admin
- Niklas Nolte
- Mike Williams

date: "2022-09-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "A novel neural architecture was recently developed that enforces an exact upper bound on the Lipschitz constant of the model by constraining the norm of its weights in a minimal way, resulting in higher expressiveness compared to other techniques. We present a new and interesting direction for this architecture: estimation of the Wasserstein metric (Earth Mover's Distance) in optimal transport by employing the Kantorovich-Rubinstein duality to enable its use in geometric fitting applications. Specifically, we focus on the field of high-energy particle physics, where it has been shown that a metric for the space of particle-collider events can be defined based on the Wasserstein metric, referred to as the Energy Mover's Distance (EMD). This metrization has the potential to revolutionize data-driven collider phenomenology. The work presented here represents a major step towards realizing this goal by providing a differentiable way of directly calculating the EMD. We show how the flexibility that our approach enables can be used to develop novel clustering algorithms."

# Summary. An optional shortened abstract.
summary: NEEMo is technique to fit arbitrary geometries to an arbitrary collection of points. Much like WGANs, it relies on the neural estimation of the Wasserstein metric through the KR dual formulation.

tags:
- Deep Learning 
- Particle Physics
featured: false

links:
# - name: INSPIRE-HEP
  # url: https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=find%20eprint%202010.09745
# - name: NeurIPS Abstract
  # url: https://ml4physicalsciences.github.io/2020/files/NeurIPS_ML4PS_2020_45.pdf
# url_pdf: https://arxiv.org/abs/2010.09745
url_code: 'https://github.com/okitouni/EnergyMover-Dual/tree/neurips2022'
#url_dataset: './featured.jpg'
# url_poster: 'https://ml4physicalsciences.github.io/2020/files/NeurIPS_ML4PS_2020_45_poster.pdf'
url_project: ''
url_slides: ''
#url_source: '#'
# url_video: 'https://youtu.be/ASqP0tcU6Ag'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
