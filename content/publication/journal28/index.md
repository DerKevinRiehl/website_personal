---
title: "Observability-Driven Sensor Placement and Delay-Resilient Kalman Filtering for Traffic State Estimation on Ring Roads"
authors:
  - Mohammad Azimi
  - Shima Sadat Mousavi
  - Hajar Atrianfar
  - admin
  - Anastasios Kouvelas

author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2026-11-09"
draft: false

doi: "https://doi.org/10.1109/TITS.2026.3741214"

# Keep the page accessible by its direct URL without showing it in lists.
# Set list to always when this publication should appear in lists again.
build:
  list: always
  render: always

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
publication_types: ["article-journal"]

publication: "*IEEE Transactions on Intelligent Transportation Systems*"
publication_short: ""

abstract: >-
  Accurate traffic state estimation on large-scale ring-road motorways is challenged by sparse sensing and delayed or out-of-sequence measurements. This paper presents a framework based on the macroscopic traffic-flow model METANET that combines graph-theoretic sensor-placement rules for strong structural observability with nonlinear Kalman filtering, including the Extended Kalman Filter (EKF), Unscented Kalman Filter (UKF), Modified Re-iterated Kalman Filter (MRIKF), and Modified Re-iterated Unscented Kalman Filter (MRIUKF). The proposed placement yields an observability-sufficient sparse sensor layout under the adopted ring-road graph structure, while the re-iterated filters process delayed measurements by updating historical states and propagating the correction forward. Synthetic tests and a calibrated Simulation of Urban MObility (SUMO) case study of Amsterdam’s A10 Ring Road show that the sensor layout reduces sensing requirements by over 40%. Under stress-test delays, MRIKF reduces density mean absolute error (MAE) by up to 86.17% relative to EKF and 5.58% relative to the delay-aware Bar-Shalom out-of-sequence measurement (BS-OOSM) baseline, demonstrating a sensor-efficient and delay-resilient framework for real-time motorway traffic state estimation.

# Summary. An optional shortened abstract.
#summary:

tags:
- traffic state estimation
- structural observability
- kalman filtering
- intelligent transportation systems
- eth
- transportation

featured: true

links:
#- name: "DOI"
url_article: 'https://ieeexplore.ieee.org/document/11783122'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/document/11783122'
url_video: ''

# Featured image
image:
  caption: 'Image credit: Kevin Riehl'
  focal_point: ""
  preview_only: false

projects: []

---
