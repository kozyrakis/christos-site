---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Block-Aware Instruction Set Architecture
subtitle: ''
summary: ''
authors:
- Ahmad Zmily
- admin
tags:
- basic block
- instruction fetch
- Instruction set architecture
- decoupled architecture
- software hints
- branch prediction
categories: []
date: '2006-09-01'
lastmod: 2022-05-15T13:35:22-07:00
featured: false
draft: false
venue: ACM TACO

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
publishDate: '2022-05-15T20:35:22.637837Z'
publication_types:
- '2'
abstract: Instruction delivery is a critical component for wide-issue, high-frequency
  processors since its bandwidth and accuracy place an upper limit on performance.
  The processor front-end accuracy and bandwidth are limited by instruction-cache
  misses, multicycle instruction-cache accesses, and target or direction mispredictions
  for control-flow operations. This paper presents a block-aware instruction set (BLISS)
  that allows software to assist with front-end challenges. BLISS defines basic block
  descriptors that are stored separately from the actual instructions in a program.
  We show that BLISS allows for a decoupled front-end that tolerates instruction-cache
  latency, facilitates instruction prefetching, and leads to higher prediction accuracy.
publication: '*ACM Transactions on Architure and Code Optimization (TACO)*'
doi: 10.1145/1162690.1162694
---
