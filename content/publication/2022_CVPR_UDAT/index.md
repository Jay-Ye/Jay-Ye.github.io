---
title: "Unsupervised Domain Adaptation for Nighttime Aerial Tracking"
# subtitle: "ICCV, 2021."
authors:
- admin
- Changhong Fu
- Guangze Zheng
- Danda Pani Paudel
- Guang Chen
date: "2022-03-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), New Orleans, Louisiana, USA, pp.8896-8905, 2022.
publication_short: In *CVPR2022*

abstract: Previous advances in object tracking mostly reported on favorable illumination circumstances while neglecting performance at nighttime, which significantly impeded the development of related aerial robot applications. This work instead develops a novel unsupervised domain adaptation framework for nighttime aerial tracking (named UDAT). Specifically, a unique object discovery approach is provided to generate training patches from raw nighttime tracking videos. To tackle the domain discrepancy, we employ a Transformer-based bridging layer post to the feature extractor to align image features from both domains. With a Transformer day/night feature discriminator, the daytime tracking model is adversarially trained to track at night. Moreover, we construct a pioneering benchmark namely NAT2021 for unsupervised domain adaptive nighttime tracking, which comprises a test set of 180 manually annotated tracking sequences and a train set of over 276k unlabelled nighttime tracking frames. Exhaustive experiments demonstrate the robustness and domain adaptability of the proposed framework in nighttime aerial tracking. The code and benchmark are available at https://github.com/vision4robotics/UDAT.

# Summary. An optional shortened abstract.
summary: '<font color=DAB88B>CVPR2022.</font> *Proposed an unsupervised domain adaptation framework to adapt object tracking from daytime to nighttime, along with a nighttime tracking benchmark.*'

tags:
- Unsupervised domain adaptation
- Nighttime aerial tracking
- Benchmark
- Transformer
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://openaccess.thecvf.com/content/CVPR2022/html/Ye_Unsupervised_Domain_Adaptation_for_Nighttime_Aerial_Tracking_CVPR_2022_paper.html
url_code: https://github.com/vision4robotics/UDAT
url_dataset: https://vision4robotics.github.io/NAT2021/
url_poster: https://drive.google.com/file/d/1ivUzKo3JYdBnxMP-5zUYt5Em6BfVBgac/view?usp=sharing
url_project: ''
url_slides: https://drive.google.com/file/d/16zZFuj5lMn9dJJvRD__qP4z0ZZe1PzlU/view?usp=sharing
url_source: ''
url_video: https://www.youtube.com/watch?app=desktop&v=-nB5XitC-Lk&feature=youtu.be

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

# <!-- <center>

# ![HiFT_workflow](featured.png)
# <small> Illustration of the proposed unsupervised domain adaptation framework for nighttime aerial tracking.</small>

# </center> -->
---
