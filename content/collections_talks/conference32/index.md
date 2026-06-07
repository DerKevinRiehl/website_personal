---
title: 'sumo3Dviz: A three dimensional traffic visualisation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Julius Schlapbach
  - Anastasios Kouvelas
  - Michail Makridis

# Author notes (optional)
author_notes:
  #- 'Equal contribution'
  #- 'Equal contribution'

date: '2026-06-02'
#doi: '10.3929/ethz-b-000710841'
#url_source: 'https://www.research-collection.ethz.ch/handle/20.500.11850/716127'

# Schedule page publish date (NOT publication's date).
#publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference-journal']

# Publication name and optional abbreviated publication name.
publication: "*SUMO User Conference 2026, Berlin, Germany, June 01-04, 2026.*"
#publication_short: In *Scientific Reports*

abstract: "*SUMO User Conference 2026, Berlin, Germany, June 01-04, 2026.*"

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 
- fairness
- signal control
- eth
- transportation
- conference

# Display this page in the Featured widget?
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Kevin Riehl'
  focal_point: ""
  preview_only: false


---

*SUMO User Conference 2026, Berlin, Germany, June 01-04, 2026.*

Traffic microsimulation software such as SUMO generate rich spatio-temporal data describing individual vehicle movements, interactions, and support the development of control strategies. While numerical outputs and 2D visualisations are sufficient for many technical analyses, they are often inadequate for applications that require intuitive interpretation, effective communication, or human-centred evaluation. In particular, user studies in mobility psychology, acceptance research, and virtual experience stated-preference experiments require realistic visualisations that reflect how traffic scenarios are perceived from a human perspective. This paper introduces sumo3Dviz, a lightweight, open-source 3D visualisation pipeline for SUMO traffic simulations. It converts standard SUMO simulation outputs, such as vehicle trajectories and signal states, into high-quality 3D renderings using a Python-based framework. In contrast to heavyweight game-engine-based approaches or tightly coupled co-simulation frameworks, sumo3Dviz is designed to be simple, scriptable, and reproducible. The tool is installable through the pip package manager, runs across operating systems, and works independently of any proprietary software or licenses. sumo3Dviz supports both external camera views and first-person perspectives, enabling cinematic overviews as well as driver-level experiences. The rendering process is optimized for batch video generation, making it suitable for large-scale scenario visualisation, educational demonstrations, and automated experiment pipelines. A key technical challenge addressed by the tool is trajectory interpolation and orientation smoothing, enabling visually coherent motion from discrete simulation outputs. Source Code on project's GitHub page:  https://github.com/DerKevinRiehl/sumo3dviz/.

<table>
  <tr>
    <td>{{< figure src="Featured.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG_20260531_220802.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG_20260601_131928.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG_20260601_183449.jpg" width=100 >}}</td>
  </tr>
  <tr>
    <td>{{< figure src="IMG_20260601_200600.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG_20260601_203619.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG_20260603_141004.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG_20260603_160128.jpg" width=100 >}}</td>
  </tr>
  <tr>
    <td>{{< figure src="IMG_20260604_171017.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG_20260605_112632.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG_20260605_150901.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG_20260605_183304.jpg" width=100 >}}</td>
  </tr>
  <tr>
    <td>{{< figure src="IMG_20260605_192213.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG-20260602-WA0045.jpg" width=100 >}}</td>
  </tr>
</table>