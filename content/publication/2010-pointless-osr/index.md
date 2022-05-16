---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Tainting is Not Pointless
subtitle: ''
summary: ''
authors:
- Michael Dalton
- Hari Kannan
- admin
tags:
- memory corruption
- software security
- virus detection
- malware detection
- dynamic information flow tracking
- pointer tainting
- buffer overflow
categories: []
date: '2010-04-01'
lastmod: 2022-05-15T13:35:18-07:00
featured: false
draft: false
venue: Usenix OSR

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
publishDate: '2022-05-15T20:35:18.848271Z'
publication_types:
- '2'
abstract: Pointer tainting is a form of Dynamic Information Flow Tracking used primarily
  to prevent software security attacks such as buffer overflows. Researchers have
  also applied pointer tainting to malware and virus analysis.A recent paper by Slowinska
  and Bos has criticized pointer tainting as a security mechanism, arguing that it
  is has serious, inherent false positive and false negative defects. We present a
  rebuttal that addresses the confusion due to the two uses of pointer tainting in
  security literature. We clarify that many of the arguments against pointer tainting
  apply only to its use as a malware and virus analysis platform, but do not apply
  to the application of pointer tainting to memory corruption protection. Hence, we
  argue that pointer tainting remains a useful and promising technique for robust
  protection against memory corruption attacks.
publication: '*SIGOPS Operating Systems Review (OSR)*'
doi: 10.1145/1773912.1773933
---
