---
title: Nighttime Aerial Tracking
summary: Adapt SOTA tracking approaches to low-light conditions.
# All sequences are captured at night in urban scenes with a frame-rate of 30 frames/s (FPS).
tags:
- Low-light
- Aerial tracking
date: "2021-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page). https://darktrack2021.netlify.app/
external_link: ""

# 1= visible
project_type: ["1"]

image:
  caption: ""
  focal_point: Smart


# links:
# - icon: github
#   icon_pack: fab
#   name: Follow
#   url: https://github.com/vision4robotics/ADTrack_v2
# - icon: download
#   icon_pack: fab
#   name: Download
#   url: https://github.com/vision4robotics/ADTrack_v2
# url_code: ""
# url_pdf: "https://arxiv.org/abs/2101.08446"
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: "example"
---
## Overview

Exploit low-light enhancement, denoising, domain adaption technologies to adapt SOTA tracking approaches to low-light conditions. With slight computational consumption, enable UAV tracking at night.

---

### Papers with code
Related works are presented as follows:

- Designed a *Retinex-inspired plug-and-play* deep low-light enhancer, dubbed *DarkLighter*, to light up the darkness for UAV tracking. Experiments on a dark tracking benchmark verify its effectiveness in several trackers and superiority against other SOTA general low-light enhancement algorithms, with *sufficient real-time speed on an embedded system*.  <iframe src="https://ghbtns.com/github-btn.html?user=vision4robotics&repo=DarkLighter&type=star&count=true&size=medium" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

  > [DarkLighter: Light up the Darkness for UAV Tracking](../../publication/2021_iros_darklighter/) in **IROS 2021**

- Constructed a *spatial-channel Transformer (SCT)* enhancer to facilitate nighttime UAV tracking in a task-inspired manner. Evaluations on the public UAVDark135 and the newly constructed DarkTrack2021 benchmarks demonstrate that the performance gains of SCT brought to nighttime UAV tracking surpass general low-light enhancers.  <iframe src="https://ghbtns.com/github-btn.html?user=vision4robotics&repo=SCT&type=star&count=true&size=medium" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

  > [Tracker Meets Night: A Transformer Enhancer for UAV Tracking](../../publication/2022_ral_sct/) in **RA-L with ICRA2022 presentation**

- Proposed an unsupervised domain adaptation framework to adapt object tracking from daytime to nighttime, along with a nighttime tracking benchmark.  <iframe src="https://ghbtns.com/github-btn.html?user=vision4robotics&repo=UDAT&type=star&count=true&size=medium" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

  > [Unsupervised Domain Adaptation for Nighttime Aerial Tracking](../../publication/2022_cvpr_udat/) in **CVPR2022**

---
### Benchmarks
We construct some pioneer benchmarks to serve for the development of nighttime object tracking:
![featured](featured.gif "[NAT2021](https://vision4robotics.github.io/NAT2021/)---a pioneering benchmark for unsupervised domain adaptive nighttime tracking.")

![featured](https://darktrack2021.netlify.app/post/getting-started/featured_hubbbc35ec4e7f72d7d989382d37396e97_1656952_1200x0_resize_lanczos_3.png "[DarkTrack2021](https://darktrack2021.netlify.app/)---a nighttime tracking benchmark comprises 110 challenging sequences with 100K frames in total.")


![featured](https://jayye99.github.io/project/uavdark135/featured1_hu47b59972aa09e73897af607e7951342f_209882_720x2500_fit_q75_h2_lanczos.webp "[UAVDark135](../uavdark135/)---a pioneering UAV dark tracking benchmark consists of 135 videos with a variety of objects.") 