---
title: "Mutation Sensitive Correlation Filter for Real-Time UAV Tracking with Adaptive Hybrid Label"
authors:
- Guangze Zheng
- Changhong Fu
- admin
- Fuling Lin
- Fangqiang Ding
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
publication: In Proceedings of the IEEE International Conference on Robotics and Automation (ICRA), Xi'an, China, pp.503-509, 2021.
publication_short: In *ICRA2021*

abstract: Unmanned aerial vehicle (UAV) based visual tracking has been confronted with numerous challenges, e.g., object motion and occlusion. These challenges generally bring about target appearance mutations and cause tracking failure. However, most prevalent discriminative correlation filter (DCF) based trackers are insensitive to target mutations due to a predefined label, which concentrates on merely the centre of the target. Meanwhile, appearance mutations incited by occlusion or similar objects commonly lead to inevitable learning of erroneous information. To cope with appearance mutations, this paper proposes a novel DCF-based method to enhance the sensitivity and resistance to mutations with an adaptive hybrid label, i.e., MSCF. The ideal label is optimized jointly with the correlation filter and remains consistent with the previous label. Meanwhile, a novel measurement of mutations called mutation threat factor (MTF) is applied to correct the label dynamically. Through the revision of label into hybrid shape, MSCF can demonstrate preferable adaptability during appearance mutations. Considerable experiments are conducted on widely used UAV benchmarks. Results manifest the performance of MSCF tracker surpassing other 26 state-ofthe-art DCF-based and deep-based trackers. With a real-time speed of ~ 38 frames/s, the proposed approach is sufficient for UAV tracking commissions.

# Summary. An optional shortened abstract.
summary: '<font color=DAB88B>ICRA2021.</font> *Constructed a novel CF-based tracker to enhance the sensitivity and resistance to mutations with an adaptive hybrid label.*'

tags:
- Visual tracking
- Unmanned aerial vehicles
- Correlation filter
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/document/9561931
url_code: https://github.com/vision4robotics/MSCF-tracker
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://youtu.be/4EPGBCuatxU

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
# ![MKCT_workflow](featured.png)
# <small>Tracking procedure of the proposed MSCF tracker. Dashed boxes denote the variables to be solved in the main regression. As MTF in the red
# box is generated from search region in frame k, it is applied to adjust the altitude value of the cruciform pedestal.</small>

# </center>
---



