---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Characterization of TCC on Chip-Multiprocessors
subtitle: ''
summary: ''
authors:
- Austen McDonald
- JaeWoong Chung
- Hassan Chafi
- Chi Cao Minh
- Brian D. Carlstrom
- Lance Hammond
- admin
- Kunle Olukotun
tags: []
categories: []
date: '2005-09-01'
lastmod: 2022-05-15T13:35:24-07:00
featured: false
draft: false
venue: PACT'05

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
publishDate: '2022-05-15T20:35:24.035609Z'
publication_types:
- '1'
abstract: Transactional Coherence and Consistency (TCC) is a novel coherence scheme
  for shared memory multiprocessors that uses programmer-defined transactions as the
  fundamental unit of parallel work, synchronization, coherence, and consistency.
  TCC has the potential to simplify parallel program development and optimization
  by providing a smooth transition from sequential to parallel programs. In this paper,
  we study the implementation of TCC on chip-multiprocessors (CMPs). We explore design
  alternatives such as the granularity of state tracking, doublebuffering, and write-update
  and write-invalidate protocols. Furthermore, we characterize the performance of
  TCC in comparison to conventional snoopy cache coherence (SCC) using parallel applications
  optimized for each scheme. We conclude that the two coherence schemes perform similarly,
  with each scheme having a slight advantage for some applications. The bandwidth
  requirements of TCC are slightly higher but well within the capabilities of CMP
  systems. Also, we find that overflow of speculative state can be effectively handled
  by a simple victim cache. Our results suggest TCC can provide its programming advantages
  without compromising the performance expected from well-tuned parallel applications.
publication: '*Proceedings of the 14th International Conference on Parallel Architectures
  and Compilation Techniques (PACT)*'
doi: 10.1109/PACT.2005.11
---
