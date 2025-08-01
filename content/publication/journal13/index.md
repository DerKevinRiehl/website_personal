
---
title: "Consistent vehicle trajectory extraction from aerial recordings using oriented object detection" 
authors:
  - admin
  - Shaimaa K. El-Baklish
  - Anastasios Kouvelas
  - Michail A. Makridis

author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2025-07-28"
doi: "https://doi.org/10.1038/s41598-025-12301-2"
#url: https://www.nature.com/articles/s41598-025-12301-2

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Scientific Reports*"
publication_short: ""

abstract: Vehicle trajectories offer valuable insights for a wide range of road transportation applications. Due to the rise of drone technology, a growing branch of literature explores optical vehicle trajectory extraction from aerial videos, where object detection using neural networks is an important component. Horizontal bounding box object detection struggles to differentiate well between rotated vehicles, especially when dealing with complex backgrounds or densely packed vehicles. This work proposes a generalizable computation pipeline that leverages angular information to extract high-quality trajectories starting from video recordings and ending in trajectories in Cartesian and lane coordinates. A trajectory reconstruction algorithm is designed to be vehicle- and driver-informed and to maximize the physical consistency of the reconstructed trajectories both on the individual vehicles’ and platoon levels. A comprehensive benchmark of 18 object detection models on a real-world video dataset demonstrates how oriented object detection and the use of angular information can be used to significantly improve the consistency of extracted trajectories (15% better internal, and 20% better platoon consistency), and that orientation-informed trajectories can be reconstructed to lane coordinates of higher quality. The reconstructed vehicle trajectories better capture car-following and traffic dynamics, thereby improving their usability for traffic flow studies.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 
- eth
- transportation
- journal
- computer vision
featured: true

links:
#- name: "DOI"
url_article: 'https://www.nature.com/articles/s41598-025-12301-2#article-info'
url_pdf: ''
url_code: 'https://github.com/DerKevinRiehl/trajectory_analysis'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.nature.com/articles/s41598-025-12301-2#article-info'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Kevin Riehl'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
