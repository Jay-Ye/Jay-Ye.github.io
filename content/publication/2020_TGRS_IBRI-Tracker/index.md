---
title: "Disruptor-Aware Interval-Based Response Inconsistency for Correlation Filters in Real-Time Aerial Tracking"
authors:
- Changhong Fu
- admin
- Juntao Xu
- Yujie He
- Fuling Lin
date: "2020-10-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Geoscience and Remote Sensing, 2020. (JCR Q1, IF = 8.2)
publication_short: '*IEEE T-GRS* (JCR Q1, IF = 8.2)'

abstract: Aerial object tracking approaches based on discriminative correlation filter (DCF) have attracted wide attention in the tracking community due to their impressive progress recently. Many studies introduce temporal regularization into the DCF-based framework to achieve a more robust appearance model and further enhance the tracking performance. However, existing temporal regularization approaches usually utilize the information of two consecutive frames, which are not robust enough due to limited information. Although some methods attempt to incorporate abundant training samples and generally improve the tracking performance, these improvements are at the expense of significantly increased computing consumption. Besides, most existing methods introduce historical information directly without denoising, which means background noises are also introduced into the filter training and may degrade the tracking accuracy. To tackle the drawbacks mentioned above, this work proposes a novel aerial object tracking approach to exploit disruptor-aware interval-based response inconsistency, i.e., IBRI tracker. The proposed method is able to incorporate historical interval information by utilizing responses in the filter training process, thereby obtaining a robust tracking performance while maintaining the real-time speed. Moreover, to reduce the disruptions caused by similar object, partial occlusion, and other challenging scenes, a novel disruptor-aware scheme based on response bucketing is introduced to detect the disruptor and enforce a spatial penalty for the disruptive area around the tracked object. Exhausted experiments on multiple well-known challenging aerial tracking benchmarks demonstrate the accuracy and robustness of the proposed IBRI tracker against other 35 state-of-the-art trackers. With a real-time speed of ~32 frames per second on a single CPU, the proposed approach can be applied for typical aerial platforms to achieve aerial visual object tracking efficiently.
# Summary. An optional shortened abstract.
summary: '<font color=DAB88B>IEEE T-GRS (IF: 8.2).</font> *Introduced the interval response inconsistency and the disruptor-aware mechanism into correlation filters.*'

tags:
- Aerial object tracking
- Discriminative correlation filter (DCF)
- Temporal regularization
- Historical frame information
- Interval-based response inconsistency
- Disruptor-aware bucketing
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/document/9239349
url_code: https://github.com/vision4robotics/IBRI-tracker
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://youtu.be/5RFpQuDo6rc

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
# ![IBRI_workflow](featured.jpg)
# <small>Tracking procedure of the proposed IBRI tracker in the k-th frame. Historical interval responses are incorporated into the filter training phase after denoising by a novel disruptor-aware scheme based on response bucketing.</small>
# </center>
---

