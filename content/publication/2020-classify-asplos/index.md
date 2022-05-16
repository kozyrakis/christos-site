---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Classifying Memory Access Patterns for Prefetching
subtitle: ''
summary: ''
authors:
- Grant Ayers
- Heiner Litz
- admin
- Parthasarathy Ranganathan
tags: []
categories: []
date: '2020-03-01'
lastmod: 2022-05-15T13:35:10-07:00
featured: false
draft: false
venue: ASPLOS'20

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
publishDate: '2022-05-15T20:35:10.748215Z'
publication_types:
- '1'
abstract: Prefetching is a well-studied technique for addressing the memory access
  stall time of contemporary microprocessors. However, despite a large body of related
  work, the memory access behavior of applications is not well understood, and it
  remains difficult to predict whether a particular application will benefit from
  a given prefetcher technique. In this work we propose a novel methodology to classify
  the memory access patterns of applications, enabling well-informed reasoning about
  the applicability of a certain prefetcher. Our approach leverages instruction dataflow
  information to uncover a wide range of access patterns, including arbitrary combinations
  of offsets and indirection. These combinations or prefetch kernels represent reuse,
  strides, reference locality, and complex address generation. By determining the
  complexity and frequency of these access patterns, we enable reasoning about prefetcher
  timeliness and criticality, exposing the limitations of existing prefetchers today.
  Moreover, using these kernels, we are able to compute the next address for the majority
  of top-missing instructions, and we propose a software prefetch injection methodology
  that is able to outperform state-of-the-art hardware prefetchers.
publication: '*Proceedings of the 25th International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
links:
- name: URL
  url: https://doi.org/10.1145/3373376.3378498
---
