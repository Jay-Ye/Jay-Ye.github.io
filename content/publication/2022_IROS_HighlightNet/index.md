---
title: "HighlightNet: Highlighting Low-Light Potential Features for Real-Time UAV Tracking"
authors:
- Changhong Fu
- Haolin Dong
- admin
- Guangze Zheng
- Sihang Li
- Jilin Zhao

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
publication: In Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Kyoto, Japan, pp. 12146-12153, 2022. 
publication_short: "IROS 2022"

abstract: Low-light environments have posed a formidable challenge for robust UAV tracking even with state-of-the-art trackers since the potential image features are hard to extract under adverse light conditions. Besides, due to the low visibility, accurate online selection of the object also becomes extremely difficult for human monitors to initialize UAV tracking in ground control stations (GCSs). To address these problems, this work proposed a novel enhancer, i.e., HighlightNet, to light up potential objects for both human operators and UAV trackers. By employing Transformer, HighlightNet can adjust enhancement parameters according to global features and is thus adaptive for illumination variation. Pixel-level range mask is introduced to make HighlightNet more focused on the enhancement of the tracking object and regions without light sources. Furthermore, a soft truncation mechanism is built to prevent background noise from being mistaken for crucial features. Experiments on image enhancement benchmarks demonstrate HighlightNet has advantages in facilitating human perception. Evaluations on the public UAVDark135 benchmark show that HightlightNet is more suitable for UAV tracking tasks than other top-ranked low-light enhancers. In addition, with real-world tests on a typical UAV platform, HighlightNet verifies its practicability and efficiency in nighttime aerial tracking-related applications. The code and demo videos are available at https://github.com/vision4robotics/HighlightNet.
# Summary. An optional shortened abstract.
# 

tags:
- Nighttime UAV tracking
- Low-light enhancement
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/9981070
url_code: https://github.com/vision4robotics/HighlightNet
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://github.com/vision4robotics/HighlightNet
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
