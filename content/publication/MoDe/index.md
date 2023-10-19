---
title: "Controlling Classifier Bias with Moment Decomposition: A Method to Enhance Searches for Resonances" 
authors:
- admin
- Benjamin Nachman
- Constantin Weisser
- Mike Williams

date: "2020-08-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "NeurIPS2020 ML4PS"
publication_short: ""

abstract: A key challenge in searches for resonant new physics is that classifiers trained to enhance potential signals must not induce localized structures. Such structures could result in a false signal when the background is estimated from data using sideband methods. A variety of techniques have been developed to construct classifiers which are independent from the resonant feature (often a mass). Such strategies are sufficient to avoid localized structures, but are not necessary. We develop a new set of tools using a novel moment loss function (Moment Decomposition or MoDe) which relax the assumption of independence without creating structures in the background. By allowing classifiers to be more flexible, we enhance the sensitivity to new physics without compromising the fidelity of the background estimation.

# Summary. An optional shortened abstract.
summary: Moment Decorrelation (MoDe) is a tool designed to ensure that a model's output remains uncorrelated with certain parameters, commonly termed as protected attributes in fairness contexts. Beyond mere decorrelation, MoDe can even shape the response function to adopt linear or quadratic relationships with the protected attribute.

tags:
- Deep Learning 
featured: false

links:
- name: INSPIRE-HEP
  url: https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=find%20eprint%202010.09745
- name: NeurIPS Abstract
  url: https://ml4physicalsciences.github.io/2020/files/NeurIPS_ML4PS_2020_45.pdf
url_pdf: https://arxiv.org/abs/2010.09745
url_code: 'https://github.com/okitouni/MoDe'
#url_dataset: './featured.jpg'
url_poster: 'https://ml4physicalsciences.github.io/2020/files/NeurIPS_ML4PS_2020_45_poster.pdf'
url_project: ''
url_slides: ''
#url_source: '#'
url_video: 'https://youtu.be/ASqP0tcU6Ag'

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
