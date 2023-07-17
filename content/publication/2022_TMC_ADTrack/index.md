---
title: "All-Day Object Tracking for Unmanned Aerial Vehicle"
authors:
- Bowen Li
- Changhong Fu
- Fangqiang Ding
- admin
- Fuling Lin
date: "2022-03-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Mobile Computing, 2022. (JCR Q1, IF = 7.9)
publication_short: '*IEEE T-MC* (JCR Q1, IF = 7.9)'

abstract: Unmanned aerial vehicle (UAV) has facilitated a wide range of real-world applications and attracted extensive research in the mobile computing field. Specially, developing real-time robust visual onboard trackers for all-day aerial maneuver can remarkably broaden the scope of intelligent deployment of UAV. However, prior tracking methods have merely focused on robust tracking in the well-illuminated scenes, while ignoring trackers’ capabilities to be deployed in the dark. In darkness, the conditions can be more complex and harsh, easily posing inferior robust tracking or even tracking failure. To this end, this work proposes a novel discriminative correlation filter-based tracker with illumination adaptive and anti-dark capability, namely ADTrack. ADTrack firstly exploits image illuminance information to enable adaptability of the model to the given light condition. Then, by virtue of an efficient enhancer, ADTrack carries out image pretreatment where a target aware mask is generated. Benefiting from the mask, ADTrack aims to solve a novel dual regression problem where dual filters are online trained with mutual constraint. Besides, this work also constructs a UAV nighttime tracking benchmark UAVDark135. Exhaustive experiments on authoritative benchmarks and onboard tests are implemented to validate the superiority and robustness of ADTrack in all-day conditions.
# Summary. An optional shortened abstract.
# 

tags:
- Unmanned aerial vehicle
- Visual object tracking
- Discriminative correlation filter
- Dark tracking benchmark
- Image illumination based mask
- Dual regression model
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/document/9744417
url_code: https://github.com/vision4robotics/ADTrack_v2
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://youtu.be/cJMUKF4J38A
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
# ![ADTrack_workflow](featured.jpg)
# <small>Pipeline of ADTrack.</small>
# </center>
---

