---
title: "ML Optimization for Concentrated Solar Power Plants" 
authors:
- Hansley Narasiah 
- admin
- Andrea Scorsoglio
- Bernd Sturdza
- Shawn Hatcher
- Dolores Garcia
- Matt Kusner  

date: "2023-12-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "NeurIPS2023 ML4PS"
publication_short: ""

abstract: 'Concentrated solar power (CSP) plants offer sustainable energy with the benefit of day-to-night energy storage. The recent development of the supercritical carbon dioxide (sCO2) Brayton cycle made CSP plants cost-competitive. However, the cost of cooling required for these CSP plants can vary wildly depending on design, and current cooler designs are far from optimal. Here, we optimize the design and configuration of a dry cooling system. We develop a physics-based simulation of the cooling properties of an air-cooled heat exchanger.
Using this simulator, we leverage recent results in high-dimensional Bayesian optimization to find dry cooler designs that minimize lifetime cost, reducing this cost by about 67% compared to recently proposed designs. Our simulation and optimization framework can increase the development pace of economically viable sustainable energy generation systems.'

# Summary. An optional shortened abstract.
summary: We use Bayesian Optimization to improve dry cooling systems for concentrated solar power plants, making them more cost-competitive.

tags:
- Bayesian Optimization
- ML for Physical Sciences
featured: false

links:
# - name: NeurIPS Abstract
#   url: https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_86.pdf
- name: PDF
  url: '/files/CSP/CSP-latest.pdf' 
#url_dataset: './featured.jpg'
# url_poster: 'https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_86_poster.png'
url_project: ''
url_slides: ''
#url_source: '#'
# url_video: 'https://youtu.be/ASqP0tcU6Ag'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Optimized heat exchanger costs for different ambient temperatures by location around the world.'
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
