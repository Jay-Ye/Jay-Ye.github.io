---
title: "Ad2Attack: Adaptive Adversarial Attack on Real-Time UAV Tracking"
authors:
- Changhong Fu
- Sihang Li
- Xinnan Yuan
- admin
- Ziang Cao
- Fangqiang Ding
date: "2022-02-01T08:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-31T08:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the IEEE International Conference on Robotics and Automation (ICRA), Philadelphia (PA), USA, pp.5893-5899, 2022.
publication_short: In *ICRA2022*

abstract: Visual tracking is adopted to extensive unmanned aerial vehicle (UAV)-related applications, which leads to a highly demanding requirement on the robustness of UAV trackers. However, adding imperceptible perturbations can easily fool the tracker and cause tracking failures. This risk is often overlooked and rarely researched at present. Therefore, to help increase awareness of the potential risk and the robustness of UAV tracking, this work proposes a novel adaptive adversarial attack approach, i.e., Ad2Attack, against UAV object tracking. Specifically, adversarial examples are generated online during the resampling of the search patch image, which leads trackers to lose the target in the following frames. Ad2Attack is composed of a direct downsampling module and a super-resolution upsampling module with adaptive stages. A novel optimization function is proposed for balancing the imperceptibility and efficiency of the attack. Comprehensive experiments on several well-known benchmarks and real-world conditions show the effectiveness of our attack method, which dramatically reduces the performance of the most advanced Siamese trackers. 

# Summary. An optional shortened abstract.
# 

tags:
- Visual tracking
- Unmanned aerial vehicles
- Adversarial attack
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/document/9812056
url_code: https://github.com/vision4robotics/Ad2Attack
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://github.com/vision4robotics/Ad2Attack

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
# <small>Overview of our Ad2Attack pipeline.</small>

# </center>
---



