---
title: "PE-MIU: A Training-Free Privacy-Enhancing Face Recognition Approach Based on Minimum Information Units" 
authors:
  - Philipp Terhörst
  - admin
  - Naser Damer
  - Peter Rot
  - Blaz Bortolato
  - Florian Kirchbuchner
  - Vitomir Struc
  - Arjan Kuijper

author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2020-05-15"
doi: "https://doi.org/10.1109/ACCESS.2020.2994960"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access*"
publication_short: ""

abstract: Research on soft-biometrics showed that privacy-sensitive information can be deduced from biometric data. Utilizing biometric templates only, information about a persons gender, age, ethnicity, sexual orientation, and health state can be deduced. For many applications, these templates are expected to be used for recognition purposes only. Thus, extracting this information raises major privacy issues. Previous work proposed two kinds of learning-based solutions for this problem. The first ones provide strong privacy-enhancements, but limited to pre-defined attributes. The second ones achieve more comprehensive but weaker privacy-improvements. In this work, we propose a Privacy-Enhancing face recognition approach based on Minimum Information Units (PE-MIU). PE-MIU, as we demonstrate in this work, is a privacy-enhancement approach for face recognition templates that achieves strong privacy-improvements and is not limited to pre-defined attributes. We exploit the structural differences between face recognition and facial attribute estimation by creating templates in a mixed representation of minimal information units. These representations contain pattern of privacy-sensitive attributes in a highly randomized form. Therefore, the estimation of these attributes becomes hard for function creep attacks. During verification, these units of a probe template are assigned to the units of a reference template by solving an optimal best-matching problem. This allows our approach to maintain a high recognition ability. The experiments are conducted on three publicly available datasets and with five state-of-the-art approaches. Moreover, we conduct the experiments simulating an attacker that knows and adapts to the systems privacy mechanism. The experiments demonstrate that PE-MIU is able to suppress privacy-sensitive information to a significantly higher degree than previous work in all investigated scenarios. At the same time, our solution is able to achieve a verification performance close to that of the unmodified recognition system. Unlike previous works, our approach offers a strong and comprehensive privacy-enhancement without the need of training.



# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 
- biometrics
- face recognition
- privacy
- soft-biometrics
- journal paper
featured: true

links:
#- name: "DOI"
#  url: "https://www.nature.com/articles/s41598-023-36062-y"
url_article: ''
url_pdf: ''
url_code: 'https://github.com/pterhoer/PrivacyPreservingFaceRecognition'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/abstract/document/9094207'
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

<table>
  <tr>
    <td>{{< figure src="pe-miu-1.JPG" width=100 >}}</td>
    <td>{{< figure src="pe-miu-2.JPG" width=100 >}}</td>
    <td>{{< figure src="pe-miu-3.JPG" width=100 >}}</td>
    <td>{{< figure src="pe-miu-4.JPG" width=100 >}}</td>
  </tr>
</table>
