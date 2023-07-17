---
title: "Local Perception-Aware Transformer for Aerial Tracking"
authors:
- Changhong Fu
- Weiyu Peng
- Sihang Li
- admin
- Ziang Cao

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
publication: In Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Kyoto, Japan, pp. 12122-12129, 2022. 
publication_short: "IROS 2022"

abstract: Visual object tracking has been utilized in numerous aerial platforms, where is facing the challenges of more extremely complex conditions. To address the inefficient long-range modeling of traditional networks with fully convolutional neural networks, Transformer is introduced into the state-of-the-art trackers’ frameworks. Benefiting from full receptive field of global attention, these Transformer trackers can efficiently model long-range information. However, the structure of vanilla Transformer is lack of enough inductive bias and directly adopting global attention will lead to overfocusing on global information which does harm to modeling local details. This work proposes a local perception-aware Transformer for aerial tracking, i.e., LPAT. Specifically, this novel tracker is constructed with modified local-recognition attention and local element correction network to process information via local-modeling to global-search mechanism. To grab local details and strengthen the local inductive bias of Transformer structure. The Transformer encoder with local-recognition attention is constructed to fuse local features for accurate feature modeling and the local element correction network can strengthen the capability of both Transformer encoder and decoder to distinguish local details. The proposed method achieves competitive accuracy and robustness in several benchmarks with 316 sequences in total. The proposed tracker’s practicability and efficiency have been validated by the real-world tests on a typical aerial platform. The code is available at https://github.com/vision4robotics/LPAT.
# Summary. An optional shortened abstract.
# 

tags:
- Aerial object tracking
- Local perception-aware Transformer
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/9981248
url_code: https://github.com/vision4robotics/LPAT
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://github.com/vision4robotics/LPAT
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