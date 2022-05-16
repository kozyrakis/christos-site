---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Understanding Sources of Inefficiency in General-Purpose Chips
subtitle: ''
summary: ''
authors:
- Rehan Hameed
- Wajahat Qadeer
- Megan Wachs
- Omid Azizi
- Alex Solomatnikov
- Benjamin C. Lee
- Stephen Richardson
- admin
- Mark Horowitz
tags: []
categories: []
date: '2011-10-01'
lastmod: 2022-05-15T13:35:17-07:00
featured: false
draft: false
venue: CACM

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
publishDate: '2022-05-15T20:35:17.451117Z'
publication_types:
- '2'
abstract: "Scaling the performance of a power limited processor requires decreasing\
  \ the energy expended per instruction executed, since energy/op * op/second is power.\
  \ To better understand what improvement in processor efficiency is possible, and\
  \ what must be done to capture it, we quantify the sources of the performance and\
  \ energy overheads of a 720p HD H.264 encoder running on a general-purpose four-processor\
  \ CMP system. The initial overheads are large: the CMP was 500 x less energy efficient\
  \ than an Application Specific Integrated Circuit (ASIC) doing the same job. We\
  \ explore methods to eliminate these overheads by transforming the CPU into a specialized\
  \ system for H.264 encoding. Broadly applicable optimizations like single instruction,\
  \ multiple data (SIMD) units improve CMP performance by 14 x and energy by 10x,\
  \ which is still 50x worse than an ASIC. The problem is that the basic operation\
  \ costs in H.264 are so small that even with a SIMD unit doing over 10 ops per cycle,\
  \ 90% of the energy is still overhead. Achieving ASIC-like performance and effciency\
  \ requires algorithm-specifc optimizations. For each subalgorithm of H.264, we create\
  \ a large, specialized functional/storage unit capable of executing hundreds of\
  \ operations per instruction. This improves energy effciency by 160x (instead of\
  \ 10x), and the final customized CMP reaches the same performance and within 3x\
  \ of an ASIC solution's energy in comparable area."
publication: '*Communications of the ACM*'
doi: 10.1145/2001269.2001291
---
