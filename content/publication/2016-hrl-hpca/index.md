---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'HRL: Efficient and flexible reconfigurable logic for near-data processing'
subtitle: ''
summary: ''
authors:
- Mingyu Gao
- admin
tags:
- Field programmable gate arrays;Arrays;Three-dimensional displays;Bandwidth;Random
  access memory;Layout
categories: []
date: '2016-03-01'
lastmod: 2022-05-15T13:35:14-07:00
featured: false
draft: false
venue: HPCA'16

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
publishDate: '2022-05-15T20:35:13.931217Z'
publication_types:
- '1'
abstract: The energy constraints due to the end of Dennard scaling, the popularity
  of in-memory analytics, and the advances in 3D integration technology have led to
  renewed interest in near-data processing (NDP) architectures that move processing
  closer to main memory. Due to the limited power and area budgets of the logic layer,
  the NDP compute units should be area and energy efficient while providing sufficient
  compute capability to match the high bandwidth of vertical memory channels. They
  should also be flexible to accommodate a wide range of applications. Towards this
  goal, NDP units based on fine-grained (FPGA) and coarse-grained (CGRA) reconfigurable
  logic have been proposed as a compromise between the efficiency of custom engines
  and the flexibility of programmable cores. Unfortunately, FPGAs incur significant
  area overheads for bit-level reconfiguration, while CGRAs consume significant power
  in the interconnect and are inefficient for irregular data layouts and control flows.
  This paper presents Heterogeneous Reconfigurable Logic (HRL), a reconfigurable array
  for NDP systems that improves on both FPGA and CGRA arrays. HRL combines both coarse-grained
  and fine-grained logic blocks, separates routing networks for data and control signals,
  and uses specialized units to effectively support branch operations and irregular
  data layouts in analytics workloads. HRL has the power efficiency of FPGA and the
  area efficiency of CGRA. It improves performance per Watt by 2.2x over FPGA and
  1.7x over CGRA. For NDP systems running MapReduce, graph processing, and deep neural
  networks, HRL achieves 92% of the peak performance of an NDP system based on custom
  accelerators for each application.
publication: '*2016 IEEE International Symposium on High Performance Computer Architecture
  (HPCA)*'
doi: 10.1109/HPCA.2016.7446059
---
