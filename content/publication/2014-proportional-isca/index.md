---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Towards Energy Proportionality for Large-Scale Latency-Critical Workloads
subtitle: ''
summary: ''
authors:
- David Lo
- Liqun Cheng
- Rama Govindaraju
- Luiz André Barroso
- admin
tags: []
categories: []
date: '2014-06-01'
lastmod: 2022-05-15T13:35:15-07:00
featured: false
draft: false
venue: ISCA'14

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
publishDate: '2022-05-15T20:35:15.238343Z'
publication_types:
- '1'
abstract: Reducing the energy footprint of warehouse-scale computer (WSC) systems
  is key to their affordability, yet difficult to achieve in practice. The lack of
  energy proportionality of typical WSC hardware and the fact that important workloads
  (such as search) require all servers to remain up regardless of traffic intensity
  renders existing power management techniques ineffective at reducing WSC energy
  use.We present PEGASUS, a feedback-based controller that significantly improves
  the energy proportionality of WSC systems, as demonstrated by a real implementation
  in a Google search cluster. PEGASUS uses request latency statistics to dynamically
  adjust server power management limits in a fine-grain manner, running each server
  just fast enough to meet global service-level latency objectives. In large cluster
  experiments, PEGASUS reduces power consumption by up to 20%. We also estimate that
  a distributed version of PEGASUS can nearly double these savings
publication: '*Proceeding of the 41st  International Symposium on Computer Architecuture
  (ISCA)*'
---
