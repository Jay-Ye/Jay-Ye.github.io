---
title: Siamese Network-Based UAV Tracking
summary: Construct robust Siamese network-based trackers for high-performance UAV tracking.
tags:
- Siamese Network
- Aerial tracking
date: "2020-10-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""
# 1= visible
project_type: ["1"]
image:
  caption: ""
  focal_point: "smart"

links:
#- icon: github
#  icon_pack: fab
#  name: Follow
#  url: ""
#- icon: download
#  icon_pack: fab
#  name: Download
#  url: ""
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

### Overview

Construct robust Siamese network-based trackers for high-performance UAV tracking. Through enhancing the anchor proposal process, feature fusion strategy, attention mechanism, etc, we have developed several robust deep learning-based trackers for UAV.
---

### Papers with code

Related works are presented as follows:
- Proposed the **anchor proposal network (APN)** for adaptive anchor proposing. Alleviated the hyper-parameters in anchor-based approaches and redundent anchors in anchor-free approaches simultaneously. <iframe src="https://ghbtns.com/github-btn.html?user=vision4robotics&repo=SiamAPN&type=star&count=true&size=medium" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

   > [*Siamese Anchor Proposal Network for High-Speed Aerial Tracking*](../../publication/2021_icra_siamapn/) in **ICRA 2021**
   
   > [*Onboard Real-Time Aerial Tracking with Efficient Siamese Anchor Proposal Network*](../../publication/2021_tgrs_siamapn_ext/) in **IEEE TRANSACTIONS ON GEOSCIENCE AND REMOTE SENSING 2021**

- Integrated **self-attention** and **cross-attention** into SiamAPN, enhanced the perception ability for various scale objects of the proposed SiamAPN++. Evaluation on UAV tracking datasets and **real-world onboard test** demonstrate its effectiveness. <iframe src="https://ghbtns.com/github-btn.html?user=vision4robotics&repo=SiamAPN&type=star&count=true&size=medium" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

   > [*SiamAPN++: Siamese Attentional Aggregation Network for Real-Time UAV Tracking*](../../publication/2021_iros_siamapn++/) in **IROS 2021**

- Introduced the **hierarchical feature transformer** into the Siamese framework to achieve interactive fusion of spatial and semantic cues. <iframe src="https://ghbtns.com/github-btn.html?user=vision4robotics&repo=HiFT&type=star&count=true&size=medium" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>

   > [*HiFT: Hierarchical Feature Transformer for Aerial Tracking*](../../publication/2021_iccv_hift/) in **ICCV 2021**

### Benchmarks

![featured](https://github.com/vision4robotics/SiamSA/blob/main/img/dataset.png "[UAMT100](https://github.com/vision4robotics/SiamSA)---a benchmark built for UAM tracking method evaluation which contains 100 image sequences recorded on a flying UAM platform.")

