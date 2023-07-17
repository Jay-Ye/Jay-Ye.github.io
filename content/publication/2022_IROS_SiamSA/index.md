---
title: "Siamese Object Tracking for Vision-Based UAM Approaching with Pairwise Scale-Channel Attention"
authors:
- Guangze Zheng
- Changhong Fu
- admin
- Bowen Li
- Geng Lu
- Jia Pan

date: "2022-06-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).意思是网页将上线的时间
publishDate: "2022-06-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Kyoto, Japan, pp. 10486-10492, 2022. 
publication_short: "IROS 2022"

abstract: Visual approaching to the target object is crucial to the subsequent manipulating of the unmanned aerial manipulator (UAM). Although the manipulating methods have been widely studied, the vision-based UAM approaching generally lacks efficient design. The key to the visual UAM approaching lies in object tracking, while current approaching generally relies on costly model-based methods. Besides, UAM approaching often confronts more severe object scale variation issues, which makes it inappropriate to directly employ state-of-the-art model-free Siamese-based methods from the object tracking field. To address the above problems, this work proposes a novel Siamese network with pairwise scale-channel attention (SiamPSA) for vision-based UAM approaching. Specifically, SiamPSA consists of a scale attention network (SAN) and a scale-aware anchor proposal network (SA-APN). SAN acquires valuable scale information for feature processing, while SA-APN mainly attaches scale-awareness to anchor proposing. Moreover, a new tracking benchmark for UAM approaching, namely UAMT100, is recorded with 35K frames on a flying UAM platform for evaluation. Exhaustive experiments on the benchmark and real-world tests validate the efficiency and practicality of SiamPSA with a promising speed. Both the code and UAMT100 benchmark are now available at https://github.com/vision4robotics/SiamSA.
# Summary. An optional shortened abstract.
# 

tags:
- Unmanned aerial manipulator
- UAM approaching
- Visual tracking
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/9982189
url_code: https://github.com/vision4robotics/SiamSA
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://github.com/vision4robotics/SiamSA
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
---