---
title: "V2VSL: Infrastructure-Free, Decentralized Variable Speed Limit Control" 
authors:
  - admin
  - Davide Pusino
  - Anastasios Kouvelas
  - Michail Makridis
  
author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2026-03-16"
doi: "https://doi.org/10.1007/s42421-026-00153-9"
url_source: 'https://link.springer.com/article/10.1007/s42421-026-00153-9'

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Data Science for Transportation*"
publication_short: ""

abstract: Traffic congestion is a pertinent issue on highways, with severe consequences on environment, economy, and quality of life. Variable speed limit control can help avoid traffic jams before congestion forms, as vehicles upstream are required to decelerate at times to stop emerging congestion from propagating and expanding. This work proposes a fully decentralized, model-free, and infrastructure-free approach to variable speed limit control -- V2VSL -- that employs connected vehicles as communication infrastructure, as moving sensors, and as actuators. Dedicated short range communication, consensus algorithm and gossip algorithm protocols, and a Bellman controller are components of this approach. At the example of three highway bottleneck scenarios, performance is assessed by traffic micro-simulations, that show the approach is robust to gaps between platoons and capable of recovering from periods of disconnection. The proposed method achieves significant improvements in traffic states, with up to 15% higher speeds, 5% lower density, and 8% higher flows. These traffic improvements become significant at a compliance rate as low as 25%, making the method potentially viable in near-term mixed traffic environments with partial CAV penetration. V2VSL achieves efficiency gains comparable to centralized VSL systems, but without requiring roadside infrastructure, detailed traffic models, or centralized communication. An open-source implementation and computational results are provided as SUMO simulation with Python on GitHub.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 
- control
- variable speed limits
- highways
- resource allocation
- eth
- transportation
featured: true

links:
#- name: "DOI"
url_article: 'https://link.springer.com/article/10.1007/s42421-026-00153-9'
url_pdf: ''
url_code: 'https://github.com/DerKevinRiehl/decentralized_vsl/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://link.springer.com/article/10.1007/s42421-026-00153-9'
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
