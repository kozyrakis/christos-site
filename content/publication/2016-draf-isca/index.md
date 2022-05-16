---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'DRAF: A Low-Power DRAM-Based Reconfigurable Acceleration Fabric'
subtitle: ''
summary: ''
authors:
- Mingyu Gao
- Christina Delimitrou
- Dimin Niu
- Krishna T. Malladi
- Hongzhong Zheng
- Bob Brennan
- admin
tags:
- FPGA
- low-power
- DRAM
- reconfigurable logic
categories: []
date: '2016-06-01'
lastmod: 2022-05-15T13:35:13-07:00
featured: false
draft: false
venue: ISCA'16

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
publishDate: '2022-05-15T20:35:13.686155Z'
publication_types:
- '1'
abstract: FPGAs are a popular target for application-specific accelerators because
  they lead to a good balance between flexibility and energy efficiency. However,
  FPGA lookup tables introduce significant area and power overheads, making it difficult
  to use FPGA devices in environments with tight cost and power constraints. This
  is the case for datacenter servers, where a modestly-sized FPGA cannot accommodate
  the large number of diverse accelerators that datacenter applications need.This
  paper introduces DRAF, an architecture for bit-level reconfigurable logic that uses
  DRAM subarrays to implement dense lookup tables. DRAF overlaps DRAM operations like
  bitline precharge and charge restoration with routing within the reconfigurable
  routing fabric to minimize the impact of DRAM latency. It also supports multiple
  configuration contexts that can be used to quickly switch between different accelerators
  with minimal latency. Overall, DRAF trades off some of the performance of FPGAs
  for significant gains in area and power. DRAF improves area density by 10x over
  FPGAs and power consumption by more than 3x, enabling DRAF to satisfy demanding
  applications within strict power and cost constraints. While accelerators mapped
  to DRAF are 2-3x slower than those in FPGAs, they still deliver a 13x speedup and
  an 11x reduction in power consumption over a Xeon core for a wide range of datacenter
  tasks, including analytics and interactive services like speech recognition.
publication: '*Proceedings of the 43rd International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1109/ISCA.2016.51
---
