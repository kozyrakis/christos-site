---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Dynamic management of TurboMode in modern multi-core chips
subtitle: ''
summary: ''
authors:
- David Lo
- admin
tags:
- Hardware;Servers;Interference;Bridges;Clocks;Quality of service
categories: []
date: '2014-02-01'
lastmod: 2022-05-15T13:35:15-07:00
featured: false
draft: false
venue: HPCA'14

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-05-15T20:35:15.074338Z'
publication_types:
- '1'
abstract: Dynamic overclocking of CPUs, or TurboMode, is a feature recently introduced
  on all x86 multi-core chips. It leverages thermal and power headroom from idle execution
  resources to overclock active cores to increase performance. TurboMode can accelerate
  CPU-bound applications at the cost of additional power consumption. Nevertheless,
  naive use of TurboMode can significantly increase power consumption without increasing
  performance. Thus far, there is no strategy for managing TurboMode to optimize its
  use across all workloads and efficiency metrics. This paper analyzes the impact
  of TurboMode on a wide range of efficiency metrics (performance, power, cost, and
  combined metrics such as QPS/W and ED2) for representative server workloads on various
  hardware configurations. We determine that TurboMode is generally beneficial for
  performance (up to +24%), cost efficiency (QPS/$ up to +8%), energy-delay product
  (ED, up to +47%), and energy-delay-squared product (ED2, up to +68%). However, TurboMode
  is inefficient for workloads that exhibit interference for shared resources. We
  use this information to build and validate a model that predicts the optimal TurboMode
  setting for each efficiency metric. We then implement autoturbo, a background daemon
  that dynamically manages TurboMode in real time without any hardware changes. We
  demonstrate that autoturbo improves QPS/$, ED, and ED2 by 8%, 47%, and 68% respectively
  over not using TurboMode. At the same time, autoturbo virtually eliminates all the
  large drops in those same metrics (-12%, -25%, -25% for QPS/$, ED, and ED2) that
  occur when TurboMode is used naively (always on).
publication: '*Proceedings of the IEEE 20th International Symposium on High Performance
  Computer Architecture (HPCA)*'
doi: 10.1109/HPCA.2014.6835969
---
