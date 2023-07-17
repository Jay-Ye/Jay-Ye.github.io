---
title: "Siamese Anchor Proposal Network for High-Speed Aerial Tracking"
authors:
- Changhong Fu
- Ziang Cao
- Yiming Li
- admin
- Chen Feng
date: "2021-02-28T08:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-28T08:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the IEEE International Conference on Robotics and Automation (ICRA), Xi'an, China, pp.510-516, 2021.
publication_short: In *ICRA2021*

abstract: In the domain of visual tracking, most deep learning-based trackers highlight the accuracy but casting aside efficiency, thereby impeding their real-world deployment on mobile platforms like the unmanned aerial vehicle (UAV). In this work, a novel two-stage siamese network-based method is proposed for aerial tracking, \textit{i.e.}, stage-1 for high-quality anchor proposal generation, stage-2 for refining the anchor proposal. Different from anchor-based methods with numerous pre-defined fixed-sized anchors, our no-prior method can 1) make tracker robust and general to different objects with various sizes, especially to small, occluded, and fast-moving objects, under complex scenarios in light of the adaptive anchor generation, 2) make calculation feasible due to the substantial decrease of anchor numbers. In addition, compared to anchor-free methods, our framework has better performance owing to refinement at stage-2. Comprehensive experiments on three benchmarks have proven the state-of-the-art performance of our approach, with a speed of ~ 200 frames/s.

# Summary. An optional shortened abstract.
# 

tags:
- Visual tracking
- Unmanned aerial vehicles
- Anchor proposal network
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/9560756
url_code: https://github.com/vision4robotics/SiamAPN
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://youtu.be/tp3YIb2XHVk

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


<center>

![MKCT_workflow](featured.png)
<small>The overview of SiamAPN tracker. It composes of four subnetworks, i.e., feature extraction network, feature fusion network, anchor proposal network (APN), and muti-classification®ression network.</small>

</center>
