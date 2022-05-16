---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'TETRIS: Scalable and Efficient Neural Network Acceleration with 3D Memory'
subtitle: ''
summary: ''
authors:
- Mingyu Gao
- Jing Pu
- Xuan Yang
- Mark Horowitz
- admin
tags:
- neural networks
- partitioning
- 3d memory
- dataflow scheduling
- acceleration
categories: []
date: '2017-04-01'
lastmod: 2022-05-15T13:35:13-07:00
featured: false
draft: false
venue: ASPLOS'17

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
publishDate: '2022-05-15T20:35:13.351919Z'
publication_types:
- '1'
abstract: The high accuracy of deep neural networks (NNs) has led to the development
  of NN accelerators that improve performance by two orders of magnitude. However,
  scaling these accelerators for higher performance with increasingly larger NNs exacerbates
  the cost and energy overheads of their memory systems, including the on-chip SRAM
  buffers and the off-chip DRAM channels.This paper presents the hardware architecture
  and software scheduling and partitioning techniques for TETRIS, a scalable NN accelerator
  using 3D memory. First, we show that the high throughput and low energy characteristics
  of 3D memory allow us to rebalance the NN accelerator design, using more area for
  processing elements and less area for SRAM buffers. Second, we move portions of
  the NN computations close to the DRAM banks to decrease bandwidth pressure and increase
  performance and energy efficiency. Third, we show that despite the use of small
  SRAM buffers, the presence of 3D memory simplifies dataflow scheduling for NN computations.
  We present an analytical scheduling scheme that matches the efficiency of schedules
  derived through exhaustive search. Finally, we develop a hybrid partitioning scheme
  that parallelizes the NN computations over multiple accelerators. Overall, we show
  that TETRIS improves mthe performance by 4.1x and reduces the energy by 1.5x over
  NN accelerators with conventional, low-power DRAM memory systems.
publication: '*Proceedings of the 22nd International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/3037697.3037702
---
