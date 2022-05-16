---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Locality-Aware Task Management for Unstructured Parallelism: A Quantitative
  Limit Study'
subtitle: ''
summary: ''
authors:
- Richard M. Yoo
- Christopher J. Hughes
- Changkyu Kim
- Yen-Kuang Chen
- admin
tags:
- task stealing
- task scheduling
- energy
- performance
- locality
categories: []
date: '2013-07-01'
lastmod: 2022-05-15T13:35:15-07:00
featured: false
draft: false
venue: IISWC'13

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
publishDate: '2022-05-15T20:35:15.648521Z'
publication_types:
- '1'
abstract: 'As we increase the number of cores on a processor die, the on-chip cache
  hierarchies that support these cores are getting larger, deeper, and more complex.
  As a result, non-uniform memory access effects are now prevalent even on a single
  chip. To reduce execution time and energy consumption, data access locality should
  be exploited. This is especially important for task-based programming systems, where
  a scheduler decides when and where on the chip the code segments, i.e., tasks, should
  execute. Capturing locality for structured task parallelism has been done effectively,
  but the more difficult case, unstructured parallelism, remains largely unsolved
  - little quantitative analysis exists to demonstrate the potential of locality-aware
  scheduling, and to guide future scheduler implementations in the most fruitful direction.This
  paper quantifies the potential of locality-aware scheduling for unstructured parallelism
  on three different many-core processors. Our simulation results of 32-core systems
  show that locality-aware scheduling can bring up to 2.39x speedup over a randomized
  schedule, and 2.05x speedup over a state-of-the-art baseline scheduling scheme.
  At the same time, a locality-aware schedule reduces average energy consumption by
  55% and 47%, relative to the random and the baseline schedule, respectively. In
  addition, our 1024-core simulation results project that these benefits will only
  increase: Compared to 32-core executions, we see up to 1.83x additional locality
  benefits. To capture such potentials in a practical setting, we also perform a detailed
  scheduler design space exploration to quantify the impact of different scheduling
  decisions. We also highlight the importance of locality-aware stealing, and demonstrate
  that a stealing scheme can exploit significant locality while performing load balancing.
  Over randomized stealing, our proposed scheme shows up to 2.0x speedup for stolen
  tasks.'
publication: '*Proceedings of the 25th  ACM Symposium on Parallelism in Algorithms
  and Architectures (SPAA)*'
doi: 10.1145/2486159.2486175
---
