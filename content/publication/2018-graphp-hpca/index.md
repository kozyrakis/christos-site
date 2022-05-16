---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'GraphP: Reducing Communication for PIM-Based Graph Processing with Efficient
  Data Partition'
subtitle: ''
summary: ''
authors:
- Mingxing Zhang
- Youwei Zhuo
- Chao Wang
- Mingyu Gao
- Yongwei Wu
- Kang Chen
- admin
- Xuehai Qian
tags:
- Bandwidth;Programming;Organizations;Three-dimensional displays;Partitioning algorithms;Memory
  management;Graph processing;Processing In Memory;Hybrid Memory Cube
categories: []
date: '2018-02-01'
lastmod: 2022-05-15T13:35:12-07:00
featured: false
draft: false
venue: HPCA'18

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
publishDate: '2022-05-15T20:35:12.454627Z'
publication_types:
- '1'
abstract: "Processing-In-Memory (PIM) is an effective technique that reduces data\
  \ movements by integrating processing units within memory. The recent advance of\
  \ “big data” and 3D stacking technology make PIM a practical and viable solution\
  \ for the modern data processing workloads. It is exemplified by the recent research\
  \ interests on PIM-based acceleration. Among them, TESSERACT is a PIM-enabled parallel\
  \ graph processing architecture based on Micron's Hybrid Memory Cube (HMC), one\
  \ of the most prominent 3D-stacked memory technologies. It implements a Pregel-like\
  \ vertex-centric programming model, so that users could develop programs in the\
  \ familiar interface while taking advantage of PIM. Despite the orders of magnitude\
  \ speedup compared to DRAM-based systems, TESSERACT generates excessive crosscube\
  \ communications through SerDes links, whose bandwidth is much less than the aggregated\
  \ local bandwidth of HMCs. Our investigation indicates that this is because of the\
  \ restricted data organization required by the vertex programming model. In this\
  \ paper, we argue that a PIM-based graph processing system should take data organization\
  \ as a first-order design consideration. Following this principle, we propose GraphP,\
  \ a novel HMC-based software/hardware co-designed graph processing system that drastically\
  \ reduces communication and energy consumption compared to TESSERACT. GraphP features\
  \ three key techniques. 1) “Source-cut” partitioning, which fundamentally changes\
  \ the cross-cube communication from one remote put per cross-cube edge to one update\
  \ per replica. 2) “Two-phase Vertex Program”, a programming model designed for the\
  \ “source-cut” partitioning with two operations: GenUpdate and ApplyUpdate. 3) Hierarchical\
  \ communication and overlapping, which further improves performance with unique\
  \ opportunities offered by the proposed partitioning and programming model. We evaluate\
  \ GraphP using a cycle accurate simulator with 5 real-world graphs and 4 algorithms.\
  \ The results show that it provides on average 1.7 speedup and 89% energy saving\
  \ compared to TESSERACT."
publication: '*2018 IEEE International Symposium on High Performance Computer Architecture
  (HPCA)*'
doi: 10.1109/HPCA.2018.00053
---
