---
title: "DarkLighter: Light Up the Darkness for UAV Tracking"
authors:
- admin
- Changhong Fu
- Guangze Zheng
- Ziang Cao
- Bowen Li

date: "2021-06-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).意思是网页将上线的时间
publishDate: "2021-06-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Prague, Czech Republic, pp. 3079-3085, 2021. 
publication_short: In *IROS2021*

abstract: Recent years have witnessed the fast evolution and promising performance of the convolutional neural network (CNN)-based trackers, which aim at imitating biological visual systems. However, current CNN-based trackers can hardly generalize well to low-light scenes that are commonly lacked in the existing training set. In indistinguishable night scenarios frequently encountered in unmanned aerial vehicle (UAV) tracking-based applications, the robustness of the state-of-the-art (SOTA) trackers drops significantly. To facilitate aerial tracking in the dark through a general fashion, this work proposes a low-light image enhancer namely DarkLighter, which dedicates to alleviate the impact of poor illumination and noise iteratively. A lightweight map estimation network, \textit{i.e.}, ME-Net, is trained to efficiently estimate illumination maps and noise maps jointly. Experiments are conducted with several SOTA trackers on numerous UAV dark tracking scenes. Exhaustive evaluations demonstrate the reliability and universality of DarkLighter, with high efficiency. Moreover, DarkLighter has further been implemented on a typical UAV system. Real-world tests at night scenes have verified its practicability and dependability.
# Summary. An optional shortened abstract.
summary: "<font color=DAB88B>IROS2021.</font> *Designed a Retinex-inspired plug-and-play deep low-light enhancer to light up the darkness for UAV tracking.*"

tags:
- Low-light enhancement
- Visual tracking
- Unmanned aerial vehicles
featured: true

links:
- name: Talk (English)
  url: https://drive.google.com/file/d/1ADJ1Om4O2C9DHnKqwcZaPhi2UTAaejL7/view?usp=sharing
- name: Talk (Chinese)
  url: https://drive.google.com/file/d/1pqI0oGmcq4s_xJhB_D-yr6v3DEF_hVFK/view?usp=sharing
url_pdf: https://ieeexplore.ieee.org/document/9636680
url_code: https://github.com/vision4robotics/DarkLighter
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: https://docs.google.com/presentation/d/1NWSpJR7szX9yidy2th9gK7dEoy_mpllS/edit?usp=sharing&ouid=116373631792838281336&rtpof=true&sd=true
url_source: ''
url_video: https://www.youtube.com/watch?v=rJtPST69J60
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
# ![MKCT_workflow](featured.png)
# <small>Tracking performance comparison in a typical dark scene with the
# proposed DarkLighter module activated (in red) or not (in pink).</small> -->

---
