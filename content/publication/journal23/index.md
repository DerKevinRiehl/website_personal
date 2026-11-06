---
title: "sumoITScontrol: Traffic Controller Collection for SUMO Traffic Simulations"
authors:
  - admin
  - Anastasios Kouvelas
  - Michail A. Makridis

author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2026-10-12"

doi: "https://doi.org/10.52825/scp.v7i.3284"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*SUMO Conference Proceedings*"
publication_short: ""

abstract: >-
  Reliable benchmarking is essential for progress in intelligent traffic control research. While microscopic traffic simulators such as SUMO enable detailed modelling of individual vehicle interactions, many published control studies still rely on single-run evaluations and project-specific baseline implementations, limiting reproducibility and comparability. This paper presents sumoITScontrol, an open-source and extensible Python framework providing a curated collection of widely used traffic controllers implemented for SUMO via the TraCI interface. The framework includes established methods for both urban and freeway traffic management, such as Max Pressure signal control, SCOOT/SCATS-inspired adaptive strategies, and ramp metering algorithms including ALINEA, HERO, and METALINE. Beyond providing implementations, the paper emphasises methodological best-practices for controller evaluation in stochastic microscopic environments. Through systematic calibration and replicated simulation experiments, we demonstrate the substantial impact of stochastic variability on performance metrics and highlight the necessity of variance-aware reporting and statistical hypothesis testing. By combining standardised controller implementations with reproducibility-oriented evaluation guidelines, sumoITScontrol aims to improve methodological transparency, enable fair benchmarking of novel approaches, and strengthen experimental standards within the SUMO and intelligent transportation systems research communities. Source Code on project’s GitHub page: https://github.com/DerKevinRiehl/sumoITScontrol/.

# Summary. An optional shortened abstract.
#summary:

tags:
- SUMO
- traffic control
- benchmarking
- reproducibility
- eth
- transportation
featured: true

links:
#- name: "DOI"
url_article: 'https://www.tib-op.org/ojs/index.php/scp/article/view/3284'
url_pdf: 'https://www.tib-op.org/ojs/index.php/scp/article/download/3284/3820'
url_code: 'https://github.com/DerKevinRiehl/sumoITScontrol/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.tib-op.org/ojs/index.php/scp/article/view/3284'
url_video: 'https://youtu.be/CMWLaSPljXY'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: Kevin Riehl'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
#slides: example

---

{{< youtube CMWLaSPljXY >}}
