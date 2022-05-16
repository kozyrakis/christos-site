---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Real-World Buffer Overflow Protection for Userspace &amp; Kernelspace
subtitle: ''
summary: ''
authors:
- Michael Dalton
- Hari Kannan
- admin
tags: []
categories: []
date: '2008-07-01'
lastmod: 2022-05-15T13:35:20-07:00
featured: false
draft: false
venue: Usenix Security'08
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
publishDate: '2022-05-15T20:35:20.419765Z'
publication_types:
- '1'
abstract: Despite having been around for more than 25 years, buffer overflow attacks
  are still a major security threat for deployed software. Existing techniques for
  buffer overflow detection provide partial protection at best as they detect limited
  cases, suffer from many false positives, require source code access, or introduce
  large performance overheads. Moreover, none of these techniques are easily applicable
  to the operating system kernel.This paper presents a practical security environment
  for buffer overflow detection in userspace and kernelspace code. Our techniques
  build upon dynamic information flow tracking (DIFT) and prevent the attacker from
  overwriting pointers in the application or operating system. Unlike previous work,
  our technique does not have false positives on unmodified binaries, protects both
  data and control pointers, and allows for practical hardware support. Moreover,
  it is applicable to the kernel and provides robust detection of buffer overflows
  and user/kernel pointer dereferences. Using a full system prototype of a Linux workstation
  (hardware and software), we demonstrate our security approach in practice and discuss
  the major challenges for robust buffer overflow protection in real-world software.
publication: '*Proceedings of the 17th USENIX Security Symposium (UsenixSec)*'
---
