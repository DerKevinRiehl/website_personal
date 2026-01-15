---
title: 'FairSCOSCA: Fairness At Arterial Signals — Just Around The Corner '

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Justin Weiss
  - Anastasios Kouvelas
  - Michail Makridis

# Author notes (optional)
author_notes:
  #- 'Equal contribution'
  #- 'Equal contribution'

date: '2026-01-12'
#doi: '10.3929/ethz-b-000710841'
#url_source: 'https://www.research-collection.ethz.ch/handle/20.500.11850/716127'

# Schedule page publish date (NOT publication's date).
#publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference-journal']

# Publication name and optional abbreviated publication name.
publication: "*105th Annual Meeting of the Transportation Research Board (TRB 2026), Washington, DC, USA, January 11-15, 2026*"
#publication_short: In *Scientific Reports*

abstract: "*105th Annual Meeting of the Transportation Research Board (TRB 2026), Washington, DC, USA, January 11-15, 2026*"

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

*105th Annual Meeting of the Transportation Research Board (TRB 2026), Washington, DC, USA, January 11-15, 2026*

Traffic signal control at intersections, especially in arterial networks, is a key lever for mitigating the growing issue of traffic congestion in cities. Despite the widespread deployment of SCOOTS and SCATS, which prioritize efficiency, fairness has remained largely absent from their design logic, often resulting in unfair outcomes for certain road users, such as excessive waiting times. Fairness however, is a major driver of public acceptance for implementation of new controll systems. Therefore, this work proposes FairSCOSCA, a fairness-enhancing extension to these systems, featuring two novel yet practical design adaptations grounded in multiple normative fairness definitions: (1) green phase optimization incorporating cumulative waiting times, and (2) early termination of underutilized green phases. Those extensions ensure fairer distributions of green times. Evaluated in a calibrated microsimulation case study of the arterial network in Esslingen am Neckar (Germany), FairSCOSCA demonstrates substantial improvements across multiple fairness dimensions (Egalitarian, Rawlsian, Utilitarian, and Harsanyian) without sacrificing traffic efficiency. Compared against Fixed-Cycle, Max-Pressure, and standard SCOOTS/SCATS controllers, FairSCOSCA significantly reduces excessive waiting times, delay inequality and horizontal discrimination between arterial and feeder roads. This work contributes to the growing literature on equitable traffic control by bridging the gap between fairness theory and the practical enhancement of globally deployed signal systems. Open source implementation available on GitHub.

<table>
  <tr>
    <td>{{< figure src="Featured.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt-1.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt-2.jpg" width=100 >}}</td>
  </tr>
  <tr>
    <td>{{< figure src="Unbenannt-3.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt-4.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt-5.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt-6.jpg" width=100 >}}</td>
  </tr>
</table>