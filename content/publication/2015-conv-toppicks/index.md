---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Convolution Engine: Balancing Efficiency and Flexibility in Specialized Computing'
subtitle: ''
summary: ''
authors:
- Wajahat Qadeer
- Rehan Hameed
- Ofer Shacham
- Preethi Venkatesan
- admin
- Mark Horowitz
tags: []
categories: []
date: '2015-03-01'
lastmod: 2022-05-15T13:35:14-07:00
featured: false
draft: false
venue: Top Picks'15
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
publishDate: '2022-05-15T20:35:14.829550Z'
publication_types:
- '2'
abstract: General-purpose processors, while tremendously versatile, pay a huge cost
  for their flexibility by wasting over 99% of the energy in programmability overheads.
  We observe that reducing this waste requires tuning data storage and compute structures
  and their connectivity to the data-flow and data-locality patterns in the algorithms.
  Hence, by backing off from full programmability and instead targeting key data-flow
  patterns used in a domain, we can create efficient engines that can be programmed
  and reused across a wide range of applications within that domain.We present the
  Convolution Engine (CE)---a programmable processor specialized for the convolution-like
  data-flow prevalent in computational photography, computer vision, and video processing.
  The CE achieves energy efficiency by capturing data-reuse patterns, eliminating
  data transfer overheads, and enabling a large number of operations per memory access.
  We demonstrate that the CE is within a factor of 2--3× of the energy and area efficiency
  of custom units optimized for a single kernel. The CE improves energy and area efficiency
  by 8--15× over data-parallel Single Instruction Multiple Data (SIMD) engines for
  most image processing applications.&lt;!-- END_PAGE_1 --&gt;
publication: '*Communications of the ACM*'
doi: 10.1145/2735841
---
