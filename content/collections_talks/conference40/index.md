---
title: 'sumo3Dviz: A three dimensional traffic visualisation'

# Use the admin profile for Kevin Riehl, preserving the supplied author order.
authors:
  - admin
  - Julius Schlapbach
  - Anastasios Kouvelas
  - Michail Makridis

date: '2027-01-10'
url_source: 'https://www.nationalacademies.org/events/887'
url_code: 'https://github.com/DerKevinRiehl/sumo3dviz/'

publication_types: ['conference-journal']
publication: "*106th Annual Meeting of the Transportation Research Board (TRB 2027), Washington, DC, USA, January 10-14, 2027.*"

abstract: "*106th Annual Meeting of the Transportation Research Board (TRB 2027), Washington, DC, USA, January 10-14, 2027.*"

tags:
- SUMO
- traffic simulation
- 3D visualisation
- eth
- transportation
- conference

featured: true

---

*106th Annual Meeting of the Transportation Research Board (TRB 2027), Washington, DC, USA, January 10-14, 2027.*

Traffic microsimulation software such as SUMO generate rich spatio-temporal data describing individual vehicle movements, interactions, and support the development of control strategies. While numerical outputs and 2D visualisations are sufficient for many technical analyses, they are often inadequate for applications that require intuitive interpretation, effective communication, or human-centred evaluation. In particular, user studies in mobility psychology, acceptance research, and virtual experience stated-preference experiments require realistic visualisations that reflect how traffic scenarios are perceived from a human perspective. This paper introduces sumo3Dviz, a lightweight, open-source 3D visualisation pipeline for SUMO traffic simulations. It converts standard SUMO simulation outputs, such as vehicle trajectories and signal states, into high-quality 3D renderings using a Python-based framework. In contrast to heavyweight game-engine-based approaches or tightly coupled co-simulation frameworks, sumo3Dviz is designed to be simple, scriptable, and reproducible. The tool is installable through the pip package manager, runs across operating systems, and works independently of any proprietary software or licenses. sumo3Dviz supports both external camera views and first-person perspectives, enabling cinematic overviews as well as driver-level experiences. The rendering process is optimized for batch video generation, making it suitable for large-scale scenario visualisation, educational demonstrations, and automated experiment pipelines. A key technical challenge addressed by the tool is trajectory interpolation and orientation smoothing, enabling visually coherent motion from discrete simulation outputs. Source Code on project's GitHub page:  https://github.com/DerKevinRiehl/sumo3dviz/.

[TRB conference page](https://www.nationalacademies.org/events/887) · [Source code on GitHub](https://github.com/DerKevinRiehl/sumo3dviz/)
