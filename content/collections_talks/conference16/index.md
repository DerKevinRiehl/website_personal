---
title: 'Oriented Object Detection For Aerial Vehicle Trajectory Extraction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Shaimaa El-Baklish
  - Anastasios Kouvelas
  - Michail Makridis

# Author notes (optional)
author_notes:
  #- 'Equal contribution'
  #- 'Equal contribution'

date: '2025-05-15'
#doi: '10.3929/ethz-b-000681446'
#url_source: 'https://www.research-collection.ethz.ch/handle/20.500.11850/681446'

# Schedule page publish date (NOT publication's date).
#publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference-journal']

# Publication name and optional abbreviated publication name.
publication: "*25th Swiss Transport Research Conference (STRC 2025), Ascona, Switzerland, May 14-16, 2025*"
#publication_short: In *Scientific Reports*

abstract: 25th Swiss Transport Research Conference (STRC 2025), Ascona, Switzerland, May 14-16, 2025

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 
- eth
- transportation
- computer vision
- conference

# Display this page in the Featured widget?
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Kevin Riehl'
  focal_point: ""
  preview_only: false


---
*25th Swiss Transport Research Conference (STRC 2025), Ascona, Switzerland, May 14-16, 2025*

Vehicle trajectories offer valuable insights for a wide range of road transportation applications and research fields. A growing branch of literature explores vehicle trajectory extraction from aerial videos, where object detection using neural networks is an important component. Horizontal bounding box object detection struggles to differentiate well between rotated vehicles, especially when dealing with complex backgrounds or densely packed vehicles. In this work, we demonstrate how oriented object detection and the use of angular, directional information can be used to significantly improve the quality of extracted trajectories. The benchmark of 18 object detection models on a real world video dataset shows, that oriented object detection achieves 0.20m (15%) better internal, and 0.75m (20%) better platoon consistency; REDET and S2A from the openmmlab family count amongst the best performing detection models. Additionally, the analysis of synthetic trajectories with different levels of noise and coverage highlights, that improvements with angular information can be achieved when positional noise is high, coverage is low. At the presence of very noisy angular information however, these improvements diminish.

<table>
  <tr>
    <td>{{< figure src="Featured2.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt-1.jpg" width=100 >}}</td>
    <td>{{< figure src="Featured.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt2.jpg" width=100 >}}</td>
  </tr>
</table>
