---
# Documentation: https://wowchemy.com/docs/managing-content/

title: ' Exploiting On-chip Memory Bandwidth in the VIRAM Compiler'
subtitle: ''
summary: ''
authors:
- David Judd
- Katherine Yelick
- admin, 
- David Martin
- David Patterson 
tags: []
categories: []
date: '2000-11-01'
lastmod: 2022-05-15T13:35:25-07:00
featured: false
draft: false
venue: IMS'00

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
publishDate: '2022-05-15T20:35:25.431333Z'
publication_types:
- '0'
abstract: Many architectural ideas that appear to be useful from a hardware standpoint
  fail to achieve wide acceptance due to lack of compiler support. In this paper we
  explore the design of the VIRAM architecture from the perspective of compiler writers,
  describing some of the code generation problems that arise in VIRAM and their solutions
  in the VIRAM compiler. VIRAM is a single chip system designed primarily for multimedia.
  It combines vector processing with mixed logic and DRAM to achieve high performance
  with relatively low energy, area, and design complexity. The paper focuses on two
  aspects of the VIRAM compiler and architecture. The first problem is to take advantage
  of the on-chip bandwidth for memory-intensive applications, including those with
  non-contiguous or unpredictable memory access patterns. The second problem is to
  support that kinds of narrow data types that arise in media processing, including
  processing of 8 and 16-bit data.
publication: '*Proceedings of the 2nd Workshop on Intelligent Memory Systems (IMS)*'
---
