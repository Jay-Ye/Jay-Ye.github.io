---
title: "Scale-Aware Siamese Object Tracking for Vision-Based UAM Approaching"
authors:
- Guangze Zheng
- Changhong Fu
- admin
- Bowen Li
- Geng Lu
- Jia Pan

date: "2022-11-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).意思是网页将上线的时间
publishDate: "2022-11-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Industrial Informatics, 2022. (JCR Q1, IF = 12.3)
publication_short: '*IEEE T-II* (JCR Q1, IF = 12.3)'

abstract: In many industrial applications of unmanned aerial manipulator (UAM), visual approaching to the object is crucial to subsequent manipulating. In comparison with the widely-studied manipulating, the key to efficient vision-based UAM approaching, i.e., UAM object tracking, is still limited. Since traditional model-based UAM tracking is costly and cannot track arbitrary objects, an intuitive solution is to introduce state-of-the-art model-free Siamese trackers from the visual tracking field. Although Siamese tracking is most suitable for the onboard embedded processors, severe object scale variation in UAM tracking brings formidable challenges. To address these problems, this work proposes a novel model-free scale-aware Siamese tracker (SiamSA). Specifically, a scale attention network is proposed to emphasize scale awareness in feature processing. A scale-aware anchor proposal network is designed to achieve anchor proposing. Besides, two novel UAM tracking benchmarks are first recorded. Comprehensive experiments on benchmarks validate the effectiveness of SiamSA. Furthermore, real-world tests also confirm practicality for industrial UAM approaching tasks with high efficiency and robustness.
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
url_pdf: https://ieeexplore.ieee.org/abstract/document/9980457
url_code: https://github.com/vision4robotics/SiamSA
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://www.youtube.com/watch?v=Fi6kESBBpnk

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
 <center>  
 
 ![workflow](featured.png) 
 <small>Demonstration of the vision-based UAM approaching system and qualitative comparison.</small>  
 
 </center>