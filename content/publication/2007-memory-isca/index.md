---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Comparing Memory Systems for Chip Multiprocessors
subtitle: ''
summary: ''
authors:
- Jacob Leverich
- Hideho Arakida
- Alex Solomatnikov
- Amin Firoozshahian
- Mark Horowitz
- admin
tags:
- streaming memory
- chip multiprocessors
- coherent caches
- parallel programming
- locality optimizations
categories: []
date: '2007-06-01'
lastmod: 2022-05-15T13:35:21-07:00
featured: false
draft: false
venue: ISCA'07

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
publishDate: '2022-05-15T20:35:21.323412Z'
publication_types:
- '1'
abstract: There are two basic models for the on-chip memory in CMP systems:hardware-managed
  coherent caches and software-managed streaming memory. This paper performs a direct
  comparison of the two modelsunder the same set of assumptions about technology,
  area, and computational capabilities. The goal is to quantify how and when they
  differ in terms of performance, energy consumption, bandwidth requirements, and
  latency tolerance for general-purpose CMPs. We demonstrate that for data-parallel
  applications, the cache-based and streaming models perform and scale equally well.
  For certain applications with little data reuse, streaming scales better due to
  better bandwidth use and macroscopic software prefetching. However, the introduction
  of techniques such as hardware prefetching and non-allocating stores to the cache-based
  model eliminates the streaming advantage. Overall, our results indicate that there
  is not sufficient advantage in building streaming memory systems where all on-chip
  memory structures are explicitly managed. On the other hand, we show that streaming
  at the programming model level is particularly beneficial, even with the cache-based
  model, as it enhances locality and creates opportunities for bandwidth optimizations.
  Moreover, we observe that stream programming is actually easier with the cache-based
  model because the hardware guarantees correct, best-effort execution even when the
  programmer cannot fully regularize an application's code.
publication: '*Proceedings of the 34th International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1145/1250662.1250707
---
