---
title: "BikeZ-ETH – A Mass-Cycling Trajectory Dataset from a Controlled Experiment" 
authors:
  - admin
  - Shaimaa K. El-Baklish
  - Ying-Chuan Ni
  - Anastasios Kouvelas
  - Michail A. Makridis
  
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2026-04-13"
doi: "https://doi.org/10.1038/s41597-026-07247-7"
url_source: 'https://www.nature.com/articles/s41597-026-07247-7#article-info'

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Scientific Data*"
publication_short: ""

abstract: This dataset contains high-resolution bicycle trajectory data collected during a controlled mass-cycling experiment conducted on a circular test track at ETH Zurich. A total of 28 cyclists were recorded using aerial video over approximately 30 minutes. The experiment systematically varied the number of simultaneous cyclists and the effective lane width to capture a range of traffic density conditions, including free-flow, disturbed flow, and stop-and-go regimes. Bicycle positions were extracted from drone footage using computer vision-based object detection and tracking, followed by state estimation and Kalman filtering to obtain smooth Cartesian trajectories at frame level. The dataset includes raw video recordings, object annotations, and processed trajectories with spatial and temporal attributes. By isolating cyclist interactions from complex road geometry and mixed traffic, the dataset provides a controlled basis for studying bicycle traffic flow, lateral movement, overtaking manoeuvres, and collective dynamics. The dataset is suitable for use in traffic flow analysis, microscopic modelling, and the development and evaluation of bicycle-specific trajectory prediction methods.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 
- bicycle
- computer vision
- mass cycling
- eth
- transportation
featured: true

links:
#- name: "DOI"
url_article: 'https://www.nature.com/articles/s41597-026-07247-7#article-info'
url_pdf: ''
url_code: 'https://github.com/DerKevinRiehl/mass_cycling_experiment/'
url_dataset: 'https://zenodo.org/records/18098714'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.nature.com/articles/s41597-026-07247-7#article-info'
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
