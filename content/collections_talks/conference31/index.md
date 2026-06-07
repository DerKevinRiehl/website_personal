---
title: 'sumoITScontrol: Traffic Controller Collection for SUMO Traffic Simulations'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
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

Reliable benchmarking is essential for progress in intelligent traffic control research. While microscopic traffic simulators such as SUMO enable detailed modelling of individual vehicle interactions, many published control studies still rely on single-run evaluations and project-specific baseline implementations, limiting reproducibility and comparability. This paper presents \texttt{sumoITScontrol}, an open-source and extensible Python framework providing a curated collection of widely used traffic controllers implemented for SUMO via the TraCI interface. The framework includes established methods for both urban and freeway traffic management, such as Max Pressure signal control, SCOOT/SCATS-inspired adaptive strategies, and ramp metering algorithms including ALINEA, HERO-inspired, and METALINE. Beyond providing implementations, the paper emphasises methodological best-practices for controller evaluation in stochastic microscopic environments. Through systematic calibration and replicated simulation experiments, we demonstrate the substantial impact of stochastic variability on performance metrics and highlight the necessity of variance-aware reporting and statistical hypothesis testing. By combining standardised controller implementations with reproducibility-oriented evaluation guidelines, \texttt{sumoITScontrol} aims to improve methodological transparency, enable fair benchmarking of novel approaches, and strengthen experimental standards within the SUMO and intelligent transportation systems research communities. Source Code on project's GitHub: https://github.com/DerKevinRiehl/sumoITScontrol/.

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