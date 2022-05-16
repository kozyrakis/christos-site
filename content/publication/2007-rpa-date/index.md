---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Register Pointer Architecture for Efficient Embedded Processors
subtitle: ''
summary: ''
authors:
- JongSoo Park
- Sung-Boem Park
- James D. Balfour
- David Black-Schaffer
- admin
- William J. Dally
tags: []
categories: []
date: '2007-01-01'
lastmod: 2022-05-15T13:35:21-07:00
featured: false
draft: false
venue: DATE'07

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
publishDate: '2022-05-15T20:35:21.649739Z'
publication_types:
- '1'
abstract: Conventional register file architectures cannot optimally exploit temporal
  locality in data references due to their limited capacity and static encoding of
  register addresses in instructions. In conventional embedded architectures, the
  register file capacity cannot be increased without resorting to longer instruction
  words. Similarly, loop unrolling is often required to exploit locality in the register
  file accesses across iterations because naming registers statically is inflexible.
  Both optimizations lead to significant code size increases, which is undesirable
  in embedded systems.In this paper, we introduce the Register Pointer Architecture
  (RPA), which allows registers to be accessed indirectly through register pointers.
  Indirection allows a larger register file to be used without increasing the length
  of instruction words. Additional register file capacity allows many loads and stores,
  such as those introduced by spill code, to be eliminated, which improves performance
  and reduces energy consumption. Moreover, indirection affords additional flexibility
  in naming registers, which reduces the need to apply loop unrolling in order to
  maximize reuse of register allocated variables.
publication: '*Proceedings of the Conference on Design, Automation and Test in Europe
  (DATE)*'
---
