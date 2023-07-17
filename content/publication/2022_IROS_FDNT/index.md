---
title: "End-to-End Feature Decontaminated Network for UAV Tracking"
authors:
- Haobo Zuo
- Changhong Fu
- Sihang Li
- admin
- Guangze Zheng

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
publication: In Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Kyoto, Japan, pp. 12130-12137, 2022. 
publication_short: "IROS 2022"

abstract: Object feature pollution is one of the burning issues in vision-based UAV tracking, commonly caused by occlusion, fast motion, and illumination variation. Due to the contaminated information in the polluted object features, most trackers fail to precisely estimate the object location and scale. To address the above disturbing issue, this work proposes a novel end-to-end feature decontaminated network for efficient and effective UAV tracking, i.e., FDNT. FDNT mainly includes two modules, a decontaminated downsampling network and a decontaminated upsampling network. The former reduces the interference information of the feature pollution and enhanced the expression of the object location information with two asymmetric convolution branches. The latter restores the object scale information with the super-resolution technology-based low-to-high encoder, achieving a further decontamination effect. Moreover, a novel pooling distance loss is carefully developed to assist the decontaminated downsampling network in concentrating on the critical regions with the object information. Exhaustive experiments on three well-known benchmarks validate the effectiveness of FDNT, especially on the sequences with feature pollution. In addition, real-world tests show the efficiency of FDNT with 31.4 frames per second. The code and demo videos are available at https://github.com/vision4robotics/FDNT. 
# Summary. An optional shortened abstract.
# 

tags:
- Feature Decontamination
- UAV tracking
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/9981882
url_code: https://github.com/vision4robotics/FDNT
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://github.com/vision4robotics/FDNT
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