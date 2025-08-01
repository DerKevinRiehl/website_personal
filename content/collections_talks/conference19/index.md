---
title: 'From sensors to sustainability: Digital-twin calibration through vehicle trip reconstruction using timestamped loop-detector event data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Anastasios Kouvelas
  - Michail A. Makridis

# Author notes (optional)
author_notes:
  #- 'Equal contribution'
  #- 'Equal contribution'

date: '2025-07-08'
#doi: '10.3929/ethz-b-000681446'
#url_source: 'https://www.research-collection.ethz.ch/handle/20.500.11850/681446'

# Schedule page publish date (NOT publication's date).
#publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference-journal']

# Publication name and optional abbreviated publication name.
publication: "*Symposium on Traffic Flow Theory and Characteristics (TFTC 2025), Cairns, Australia, July 07-09, 2025*"
#publication_short: In *Scientific Reports*

abstract: Symposium on Traffic Flow Theory and Characteristics (TFTC 2025), Cairns, Australia, July 07-09, 2025

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 
- eth
- transportation
- control
- computer science
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
*Symposium on Traffic Flow Theory and Characteristics (TFTC 2025), Cairns, Australia, July 07-09, 2025*

Municipal road authorities are responsible for operating and refining intelligent traffic control systems, to reduce congestion and related externalities. Loop-detectors are a fundamental component of such activities, and are among the most widely used road sensing technologies. An emerging trend are digital twin models, that allow for real-time, simulation-based support in safety-critical, informed decision-making. The calibration of traffic microsimulation models typically relies on aggregated vehicle counts from loopdetectors, overlooking the richer, timestamped event data these sensors provide. This study proposes a methodology to reconstruct single trips from traces that vehicles leave passing a sensor and road network. The method consists of two key steps: (i) matching individual loop-detector events to infer vehicle passage at intersections, and (ii) reconstructing full vehicle trajectories across the road network. This approach moves beyond probabilistic origin-destination estimates, enabling a detailed reconstruction of real-world traffic flow. The approach is validated using the case study on the Schorndorfer Strasse arterial network in Esslingen am Neckar, Germany, leveraging data from 34 loop detectors and 96 traffic lights. Benchmarking against conventional methods demonstrates that the approach maintains comparable accuracy at macroscopic (traffic flow metrics) and mesoscopic (detector counts) scales, while achieving up to 40% greater accuracy in microscopic traffic characteristics, such as vehicle delays and emission distributions. By leveraging existing sensor infrastructure, this work significantly enhances traffic model calibration, providing deeper insights into spatio-temporal traffic delays and emissions. These improvements support better-informed evaluation, and design, aligning intelligent traffic control with decarbonization and environmental goals.

<table>
  <tr>
    <td>{{< figure src="Featured.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt-00.jpg" width=100 >}}</td>
    <td>{{< figure src="Unbenannt-01.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG-20250708-WA0028.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG-20250708-WA0064.jpg" width=100 >}}</td>
  </tr>
  <tr>
    <td>{{< figure src="IMG-20250708-WA0065.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG-20250708-WA0066.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG-20250712-WA0000.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG-20250716-WA0005.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG-20250716-WA0007.jpg" width=100 >}}</td>
  </tr>
    
  <tr>
    <td>{{< figure src="IMG-20250801-WA0000.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG-20250801-WA0001.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG-20250801-WA0002.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG-20250801-WA0003.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG-20250801-WA0004.jpg" width=100 >}}</td>
  </tr>
    
  <tr>
    <td>{{< figure src="IMG-20250801-WA0005.jpg" width=100 >}}</td>
    <td>{{< figure src="IMG-20250801-WA0006.jpg" width=100 >}}</td>
  </tr>
</table>
