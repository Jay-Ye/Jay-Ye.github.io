---
title: "PVT++: A Simple End-to-End Latency-Aware Visual Tracking Framework"
authors:
- Bowen Li
- Ziyuan Huang
- admin
- Yiming Li
- Sebastian Scherer
- Hang Zhao
- Changhong Fu
date: "2023-07-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV), Paris, France, pp.1-11, 2023.
publication_short: In *ICCV2023*

abstract: Visual object tracking is an essential capability of intelligent robots. Most existing approaches have ignored the online latency that can cause severe performance degradation during real-world processing. Especially for unmanned aerial vehicle, where robust tracking is more challenging and onboard computation is limited, latency issue could be fatal. In this work, we present a simple framework for end-to-end latency-aware tracking, i.e., end-to-end predictive visual tracking (PVT++). PVT++ is capable of turning most leading-edge trackers into predictive trackers by appending an online predictor. Unlike existing solutions that use model-based approaches, our framework is learnable, such that it can take not only motion information as input but it can also take advantage of visual cues or a combination of both. Moreover, since PVT++ is end-to-end optimizable, it can further boost the latency-aware tracking performance by joint training. Additionally, this work presents an extended latency-aware evaluation benchmark for assessing an any-speed tracker in the online setting. Empirical results on robotic platform from aerial perspective show that PVT++ can achieve up to 60% performance gain on various trackers and exhibit better robustness than prior modelbased solution, largely mitigating the degradation brought by latency. Code and models will be made public.
# Summary. An optional shortened abstract.
summary: '<font color=DAB88B>ICCV2023.</font>*A simple and effective framework to realize robust predictive visual tracking.*'

tags:
- Unmanned aerial vehicle
- Visual object tracking
- Latency-aware tracking
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/pdf/2211.11629.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

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
# <center>
# ![ADTrack_workflow](featured.png)
# <small></small>
# </center>
---

