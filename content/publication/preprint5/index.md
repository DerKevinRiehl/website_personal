---
title: "sumo3Dviz: A three dimensional traffic visualisation" 
authors:
  - admin
  - Julius Schlapbach
  - Anastasios Kouvelas
  - Michail Makridis
  
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2026-06-01"
doi: "https://doi.org/10.48550/arXiv.2604.19194"
url_source: 'https://arxiv.org/abs/2604.19194'

links:
#- name: "DOI"
url_article: 'https://arxiv.org/abs/2604.19194'
url_pdf: ''
url_code: 'https://github.com/DerKevinRiehl/sumo3dviz/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://arxiv.org/abs/2604.19194'
url_video: 'https://www.youtube.com/watch?v=XvpG5cbv7Ig'

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-preprint"]

# Publication name and optional abbreviated publication name.
publication: "*Preprint in arXiv*"
publication_short: ""

abstract: Traffic microsimulation software such as SUMO generate rich spatio-temporal data describing individual vehicle movements, interactions, and support the development of control strategies. While numerical outputs and 2D visualisations are sufficient for many technical analyses, they are often inadequate for applications that require intuitive interpretation, effective communication, or human-centred evaluation. In particular, user studies in mobility psychology, acceptance research, and virtual experience stated-preference experiments require realistic visualisations that reflect how traffic scenarios are perceived from a human perspective. This paper introduces sumo3Dviz, a lightweight, open-source 3D visualisation pipeline for SUMO traffic simulations. It converts standard SUMO simulation outputs, such as vehicle trajectories and signal states, into high-quality 3D renderings using a Python-based framework. In contrast to heavyweight game-engine-based approaches or tightly coupled co-simulation frameworks, sumo3Dviz is designed to be simple, scriptable, and reproducible. The tool is installable through the pip package manager, runs across operating systems, and works independently of any proprietary software or licenses. sumo3Dviz supports both external camera views and first-person perspectives, enabling cinematic overviews as well as driver-level experiences. The rendering process is optimized for batch video generation, making it suitable for large-scale scenario visualisation, educational demonstrations, and automated experiment pipelines. A key technical challenge addressed by the tool is trajectory interpolation and orientation smoothing, enabling visually coherent motion from discrete simulation outputs. Source Code on project's GitHub page www.github.com/DerKevinRiehl/sumo3dviz/. 



# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 
- fairness
- resource allocation
- eth
- transportation
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Kevin Riehl'
  focal_point: ""
  preview_only: false

---
