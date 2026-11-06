---
title: 'TiKMD: Traffic-informed Koopman Mode Decomposition For Short-Term Traffic State Prediction'

# Use the admin profile for Kevin Riehl, preserving the supplied author order.
authors:
  - Shaimaa K. El-Baklish
  - admin
  - Anastasios Kouvelas
  - Michail A. Makridis

date: '2026-12-15'
publishDate: '2026-11-05'
url_code: 'https://github.com/shaimaa-elbaklish/kmd_prediction'

publication_types: ['conference-journal']
publication: "*65th IEEE Conference on Decision and Control (CDC 2026), Hilton Hawaiian Village, Honolulu, Hawaii, USA, December 15-18, 2026.*"

abstract: "*65th IEEE Conference on Decision and Control (CDC 2026), Hilton Hawaiian Village, Honolulu, Hawaii, USA, December 15-18, 2026.*"

tags:
- traffic state prediction
- Koopman mode decomposition
- physics-informed modeling
- traffic control
- eth
- transportation
- conference

featured: true

---

*65th IEEE Conference on Decision and Control (CDC 2026), Hilton Hawaiian Village, Honolulu, Hawaii, USA, December 15-18, 2026.*

Freeway congestion is a significant and growing issue. Intelligent transportation systems for the control of large-scale traffic networks can substantially improve traffic conditions by reducing congestion. These intelligent control systems, however, rely on accurate traffic state forecasting. Traffic flow data is characterized by temporal and spatial correlations, and a dynamic sequential structure; thereby making its short-term prediction challenging. This study explores the application of the Koopman operator for traffic state prediction, which transforms a nonlinear system into a linear one in an infinite-dimensional space. The data-driven nature of Koopman mode decomposition enables it to effectively capture these spatio-temporal correlations, making it well suited for traffic prediction. Specifically, we incorporate known spatio-temporal inter-dependencies in traffic flow to develop a physics-informed modeling pipeline. A computational benchmark with Koopman's linear counterpart, dynamic mode decomposition, demonstrates its benefits in more accurate predictions and a wider range of traffic scenarios. Due to its lightweight structure and minimal training requirements, TiKMD is particularly suitable for integration into model-based traffic control frameworks such as ramp metering and variable speed limit optimization, without requiring extensive historical data or offline training.

[Source code on GitHub](https://github.com/shaimaa-elbaklish/kmd_prediction).
