---
title: "DeconNet: End-to-End Decontaminated Network for Vision-Based Aerial Tracking"
authors:
- Haobo Zuo 
- Changhong Fu 
- Sihang Li 
- admin
- Guangze Zheng
date: "2022-10-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Geoscience and Remote Sensing, 2022. (JCR Q1, IF = 8.2)
publication_short: '*IEEE T-GRS* (JCR Q1, IF = 8.2)'

abstract: Vision-based aerial tracking has proven enormous potential in the field of remote sensing recently. However, challenges such as occlusion, fast motion, and illumination variation remain crucial issues for realistic aerial tracking applications. These challenges, frequently occurring from the aerial perspectives, can easily cause object feature pollution. With the contaminated object features, the credibility of trackers is prone to be substantially degraded. To address this issue, this work proposes a novel end-to-end decontaminated network, i.e., DeconNet, to alleviate object feature pollution efficiently and effectively. DeconNet mainly consists of downsampling and upsampling phases. Specifically, the decontaminated downsampling network first decreases the polluted object information with two convolution branches, enhancing the object location information. Subsequently, the decontaminated upsampling network applies the super-resolution technology to restore the object scale and shape information, with the low-to-high encoder for further decontamination. Additionally, the pooling distance loss function is carefully designed to improve the decontamination effect of the decontaminated downsampling network. Comprehensive evaluations on four well-known aerial tracking benchmarks validate the effectiveness of DeconNet. Especially, the proposed tracker has superior performance on the sequences with feature pollution. Besides, real-world tests on an aerial platform have proven the efficiency of DeconNet with 30.6 frames per second.
# Summary. An optional shortened abstract.
# 

tags:
- Vision-based aerial tracking 
- End-to-end decontaminated network 
- Downsampling-upsampling strategy 
- Low-to-high encoder 
- Pooling distance loss
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/abstract/document/9991169
url_code: https://github.com/vision4robotics/DeconNet
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

![workflow](featured.jpg)
<small>Overview of the proposed DeconNet.</small>

</center>