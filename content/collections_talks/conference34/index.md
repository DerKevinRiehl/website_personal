---
title: 'Great GATsBi: Hybrid, Multimodal, Trajectory Forecasting for Bicycles using Anticipation Mechanism'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Shaimaa K. El-Baklish
  - Anastasios Kouvelas
  - Michail A. Makridis

# Author notes (optional)
author_notes:
  #- 'Equal contribution'
  #- 'Equal contribution'

date: '2026-09-15'
#doi: ''
#url_source: ''
url_code: 'https://github.com/DerKevinRiehl/great_gatsbi'
#url_pdf: 'https://arxiv.org/pdf/2508.14523'

# Schedule page publish date (NOT publication's date).
#publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference-journal']

# Publication name and optional abbreviated publication name.
publication: "*IEEE International Conference on Intelligent Transportation Systems (ITSC 2026), Naples, Italy, September 15-18, 2026.*"
#publication_short: In *Scientific Reports*

abstract: "*IEEE International Conference on Intelligent Transportation Systems (ITSC 2026), Naples, Italy, September 15-18, 2026.*"

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- bicycle trajectory forecasting
- multimodal prediction
- graph attention networks
- road safety
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

*IEEE International Conference on Intelligent Transportation Systems (ITSC 2026), Naples, Italy, September 15-18, 2026.*

Accurate prediction of road user movement is increasingly required by many applications ranging from advanced driver assistance systems to autonomous driving, and especially crucial for road safety. Even though most traffic accident fatalities account to bicycles, they have received little attention, as previous work focused mainly on pedestrians and motorized vehicles. In this work, we present the Great GATsBi, a domain-knowledge-based, hybrid, multimodal trajectory prediction framework for bicycles. The model incorporates both physics-based modeling (inspired by motorized vehicles) and social-based modeling (inspired by pedestrian movements) to explicitly account for the dual nature of bicycle movement. The social interactions are modeled with a graph attention network, and include decayed historical, but also anticipated, future trajectory data of a bicycles neighborhood, following recent insights from psychological and social studies. The results indicate that the proposed ensemble of physics models -- performing well in the short-term predictions -- and social models -- performing well in the long-term predictions -- exceeds state-of-the-art performance. We also conducted a controlled mass-cycling experiment to demonstrate the framework's performance when forecasting bicycle trajectories and modeling social interactions with road users.

[Paper on arXiv](https://arxiv.org/abs/2508.14523) [Source code on GitHub](https://github.com/DerKevinRiehl/great_gatsbi)

<table>
  <tr>
    <td>{{< figure src="Featured.png" width=100 >}}</td>
    <td>{{< figure src="IMG_7923.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG_7925.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG_7934.jpg" width=100 >}}</td>
  </tr>
  <tr>
    <td>{{< figure src="pic_1.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt2.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt3.jpg" width=100 >}}</td>
  </tr>
  <tr>
    <td>{{< figure src="Unbenannt4.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt5.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt6.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt7.jpg" width=100 >}}</td>
  </tr>
  <tr>
    <td>{{< figure src="Unbenannt8.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt9.jpg" width=100 >}}</td>
  </tr>
</table>
