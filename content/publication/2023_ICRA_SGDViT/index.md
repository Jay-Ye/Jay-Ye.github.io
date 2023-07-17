---
title: "SGDViT: Saliency-Guided Dynamic Vision Transformer for UAV Tracking"
authors:
- Liangliang Yao
- Changhong Fu
- Sihang Li 
- Guangze Zheng 
- admin
date: "2023-01-15T08:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-15T08:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the IEEE International Conference on Robotics and Automation (ICRA), ExCeL London, pp.1-8, 2023.
publication_short: In *ICRA 2023*

abstract: Vision-based object tracking has boosted extensive autonomous applications for unmanned aerial vehicles (UAVs). However, the frequent maneuvering flight and viewpoint change are prone to cause nerve-wracking challenges, e.g., aspect ratio change and scale variation. The cross-correlation operation’s weak ability to mine perceptual similarity and easy introduction of background information become more apparent when confronted with these challenges. To address these issues, this work proposes a novel saliency-guided dynamic vision Transformer (SGDViT) for UAV tracking. Specifically, a UAV taskoriented object saliency mining network is designed to refine the perceptual similarity indicated by cross-correlation operation, distinguishing the foreground and background preliminarily. Furthermore, an innovative saliency adaption embedding operation is developed to generate dynamic tokens based on the initial saliency, reducing the computational complexity of the Transformer structure. On this bases, a lightweight saliency filtering Transformer is implemented to refine the saliency information and increase attention to the appearance information. Comprehensive evaluations on three authoritative UAV tracking benchmarks and real-world tests have proven the effectiveness and robustness of the proposed method. The source code and demo videos are available at https://github.com/vision4robotics/SGDViT.

# Summary. An optional shortened abstract.
# 

tags:
- Visual tracking
- Unmanned aerial vehicles
- Saliency-guided dynamic Transformer
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: ''
url_code: https://github.com/vision4robotics/SGDViT
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://github.com/vision4robotics/SGDViT

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
<small>Overall comparison of tracking results between baseline (blue) and the proposed saliency-guided dynamic vision Transformer (SGDViT) (red).</small>

</center>
