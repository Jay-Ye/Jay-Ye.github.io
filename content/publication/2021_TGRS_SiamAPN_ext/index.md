---
title: "Onboard Real-Time Aerial Tracking with Efficient Siamese Anchor Proposal Network"
authors:
- Changhong Fu
- Ziang Cao
- Yiming Li
- admin
- Chen Feng
date: "2021-05-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Geoscience and Remote Sensing, 2021. (JCR Q1, IF = 8.2)
publication_short: '*IEEE T-GRS* (JCR Q1, IF = 8.2)'

abstract: Object tracking approaches based on siamese network have demonstrated their huge potential in remote sensing field recently. Nevertheless, due to the limited computing resource of aerial platforms and special challenges in aerial tracking, most existing siamese-based methods can hardly meet the real-time and state-of-the-art performance at the same time. Consequently, a novel siamese-based method is proposed in this work for onboard real-time aerial tracking, i.e., SiamAPN. The proposed method is a no-prior two-stage method, i.e., stage-1 for proposing adaptive anchors to enhance the ability of object perception, stage-2 for fine-tuning the proposed anchors to obtain accurate results. Distinct from pre-defined fixed-sized anchors, our adaptive anchors are adapt automatically to accommodate the tracking object. Besides, the internal information of adaptive anchors is utilized to feedback SiamAPN for enhancing the object perception. Attributing to the feature fusion network, different semantic information is integrated, enriching the information flow. In the end, the regression and multi-classification operation refine the proposed anchors meticulously. Comprehensive evaluations on three well-known benchmarks have proven the superior performance of our approach. Moreover, to verify the practicability of the proposed method, SiamAPN is implemented in an onboard system. Real-world flight tests are conducted on aerial tracking specific scenarios, e.g., low resolution, fast motion, and long-term tracking, the results demonstrate the efficiency and accuracy of our approach, with a processing speed of over 30 frame/s. In addition, the image sequences in the real-world flight tests are collected and annotated as a new benchmark, i.e., UAVTrack112.
# Summary. An optional shortened abstract.
# 

tags:
- Real-time aerial tracking
- Efficient siamese structure
- Anchor proposal network
- No-prior adaptive anchors
- Onboard embedded processing
- Real-world flight tests
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/document/9477413
url_code: https://github.com/vision4robotics/SiamAPN
url_dataset: https://github.com/vision4robotics/SiamAPN
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://youtu.be/baJ2F4TFqpU

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

![SiamAPN_workflow](featured.jpg)
<small>The workflow of SiamAPN. It is composed of four subnetworks and two stages, i.e., feature extraction network, feature fusion network, anchor proposal network, and classification&amp;regression network. Stage-1 includes feature extraction network and anchor proposal network (APN). Stage-2 contains feature fusion network and classification&amp;regression network.</small>

</center>