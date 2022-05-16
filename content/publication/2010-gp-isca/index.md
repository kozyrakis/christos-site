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
tags:
- chip multiprocessor
- ASIC
- tensilica
- energy efficiency
- high performance
- customization
- h.264
categories: []
date: '2010-06-01'
lastmod: 2022-05-15T13:35:18-07:00
featured: false
draft: false
venue: ISCA'10

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
publishDate: '2022-05-15T20:35:18.351854Z'
publication_types:
- '1'
abstract: Due to their high volume, general-purpose processors, and now chip multiprocessors
  (CMPs), are much more cost effective than ASICs, but lag significantly in terms
  of performance and energy efficiency. This paper explores the sources of these performance
  and energy overheads in general-purpose processing systems by quantifying the overheads
  of a 720p HD H.264 encoder running on a general-purpose CMP system. It then explores
  methods to eliminate these overheads by transforming the CPU into a specialized
  system for H.264 encoding. We evaluate the gains from customizations useful to broad
  classes of algorithms, such as SIMD units, as well as those specific to particular
  computation, such as customized storage and functional units.The ASIC is 500x more
  energy efficient than our original four-processor CMP. Broadly applicable optimizations
  improve performance by 10x and energy by 7x. However, the very low energy costs
  of actual core ops (100s fJ in 90nm) mean that over 90% of the energy used in these
  solutions is still \"overhead\". Achieving ASIC-like performance and efficiency
  requires algorithm-specific optimizations. For each sub-algorithm of H.264, we create
  a large, specialized functional unit that is capable of executing 100s of operations
  per instruction. This improves performance and energy by an additional 25x and the
  final customized CMP matches an ASIC solution's performance within 3x of its energy
  and within comparable area.
publication: '*Proceedings of the 37th International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1145/1815961.1815968
---
