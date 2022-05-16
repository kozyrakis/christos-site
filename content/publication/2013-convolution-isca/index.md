---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Convolution Engine: Balancing Efficiency &amp; Flexibility in Specialized
  Computing'
subtitle: ''
summary: ''
authors:
- Wajahat Qadeer
- Rehan Hameed
- Ofer Shacham
- Preethi Venkatesan
- admin
- Mark A. Horowitz
tags:
- specialized computing
- H.264
- tensilica
- demosaic
- energy efficiency
- computational photography
- convolution
categories: []
date: '2013-06-01'
lastmod: 2022-05-15T13:35:16-07:00
featured: false
draft: false
venue: ISCA'13

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
publishDate: '2022-05-15T20:35:16.060207Z'
publication_types:
- '1'
abstract: This paper focuses on the trade-off between flexibility and efficiency in
  specialized computing. We observe that specialized units achieve most of their efficiency
  gains by tuning data storage and compute structures and their connectivity to the
  data-flow and data-locality patterns in the kernels. Hence, by identifying key data-flow
  patterns used in a domain, we can create efficient engines that can be programmed
  and reused across a wide range of applications.We present an example, the Convolution
  Engine (CE), specialized for the convolution-like data-flow that is common in computational
  photography, image processing, and video processing applications. CE achieves energy
  efficiency by capturing data reuse patterns, eliminating data transfer overheads,
  and enabling a large number of operations per memory access. We quantify the tradeoffs
  in efficiency and flexibility and demonstrate that CE is within a factor of 2-3x
  of the energy and area efficiency of custom units optimized for a single kernel.
  CE improves energy and area efficiency by 8-15x over a SIMD engine for most applications.
publication: '*Proceedings of the 40th  International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1145/2485922.2485925
---
