---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Tradeoffs in Transactional Memory Virtualization
subtitle: ''
summary: ''
authors:
- JaeWoong Chung
- Chi Cao Minh
- Austen McDonald
- Travis Skare
- Hassan Chafi
- Brian D. Carlstrom
- admin
- Kunle Olukotun
tags:
- OS support
- transactional memory
- chip multi-processor
- virtualization
categories: []
date: '2006-10-01'
lastmod: 2022-05-15T13:35:22-07:00
featured: false
draft: false
venue: ASPLOS'06

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
publishDate: '2022-05-15T20:35:22.475157Z'
publication_types:
- '1'
abstract: For transactional memory (TM) to achieve widespread acceptance, transactions
  should not be limited to the physical resources of any specific hardware implementation.
  TM systems should guarantee correct execution even when transactions exceed scheduling
  quanta, overflow the capacity of hardware caches and physical memory, or include
  more independent nesting levels than what is supported in hardware. Existing proposals
  for TM virtualization are either incomplete or rely on complex hardware implementations,
  which are an overkill if virtualization is invoked infrequently in the common case.We
  present eXtended Transactional Memory (XTM), the first TM virtualization system
  that virtualizes all aspects of transactional execution (time, space, and nesting
  depth). XTM is implemented in software using virtual memory support. It operates
  at page granularity, using private copies of overflowed pages to buffer memory updates
  until the transaction commits and snapshots of pages to detect interference between
  transactions. We also describe two enhancements to XTM that use limited hardware
  support to address key performance bottlenecks.We compare XTM to hardwarebased virtualization
  using both real applications and synthetic microbenchmarks. We show that despite
  being software-based, XTM and its enhancements are competitive with hardware-based
  alternatives. Overall, we demonstrate that XTM provides a complete, flexible, and
  low-cost mechanism for practical TM virtualization.
publication: '*Proceedings of the 12th International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/1168857.1168903
---
