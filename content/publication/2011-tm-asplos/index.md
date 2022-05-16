---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Hardware Acceleration of Transactional Memory on Commodity Systems
subtitle: ''
summary: ''
authors:
- Jared Casper
- Tayo Oguntebi
- Sungpack Hong
- Nathan G. Bronson
- admin
- Kunle Olukotun
tags:
- fpga
- hardware acceleration
- transactional memory
categories: []
date: '2011-03-01'
lastmod: 2022-05-15T13:35:18-07:00
featured: false
draft: false
venue: ASPLOS'11

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
publishDate: '2022-05-15T20:35:18.025675Z'
publication_types:
- '1'
abstract: The adoption of transactional memory is hindered by the high overhead of
  software transactional memory and the intrusive design changes required by previously
  proposed TM hardware. We propose that hardware to accelerate software transactional
  memory (STM) can reside outside an unmodified commodity processor core, thereby
  substantially reducing implementation costs. This paper introduces Transactional
  Memory Acceleration using Commodity Cores (TMACC), a hardware-accelerated TM system
  that does not modify the processor, caches, or coherence protocol.We present a complete
  hardware implementation of TMACC using a rapid prototyping platform. Using this
  hardware, we implement two unique conflict detection schemes which are accelerated
  using Bloom filters on an FPGA. These schemes employ novel techniques for tolerating
  the latency of fine-grained asynchronous communication with an out-of-core accelerator.
  We then conduct experiments to explore the feasibility of accelerating TM without
  modifying existing system hardware. We show that, for all but short transactions,
  it is not necessary to modify the processor to obtain substantial improvement in
  TM performance. In these cases, TMACC outperforms an STM by an average of 69% in
  applications using moderate-length transactions, showing maximum speedup within
  8% of an upper bound on TM acceleration. Overall, we demonstrate that hardware can
  substantially accelerate the performance of an STM on unmodified commodity processors.
publication: '*Proceedings of the 16th International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/1950365.1950372
---
