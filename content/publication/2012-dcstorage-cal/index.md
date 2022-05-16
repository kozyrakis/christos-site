---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Decoupling Datacenter Storage Studies from Access to Large-Scale Applications
subtitle: ''
summary: ''
authors:
- Christina Delimitrou
- Sriram Sankar
- Kushagra Vaid
- admin
tags:
- Very large scale integration
- Modeling techniques
- Modeling of computer architecture
- Computational modeling
- Generators
- Storage area networks
- Super (very large) computers
- Electronic mail
- Load modeling
- Throughput
- Mass storage
categories: []
date: '2012-07-01'
lastmod: 2022-05-15T13:35:16-07:00
featured: false
draft: false
venue: IEEE CAL

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
publishDate: '2022-05-15T20:35:16.715258Z'
publication_types:
- '2'
abstract: "Suboptimal storage design has significant cost and power impact in large-scale\
  \ datacenters (DCs). Performance, power and cost-optimized systems require deep\
  \ understanding of target workloads, and mechanisms to effectively model different\
  \ storage design choices. Traditional benchmarking is invalid in cloud data-stores,\
  \ representative storage profiles are hard to obtain, while replaying applications\
  \ in different storage configurations is impractical both in cost and time. Despite\
  \ these issues, current workload generators are not able to reproduce key aspects\
  \ of real application patterns (e.g., spatial/temporal locality, I/O intensity).\
  \ In this paper, we propose a modeling and generation framework for large-scale\
  \ storage applications. As part of this framework we use a state diagram-based storage\
  \ model, extend it to a hierarchical representation, and implement a tool that consistently\
  \ recreates DC application I/O loads. We present the principal features of the framework\
  \ that allow accurate modeling and generation of storage workloads, and the validation\
  \ process performed against ten original DC application traces. Finally, we explore\
  \ two practical applications of this methodology: SSD caching and defragmentation\
  \ benefits on enterprise storage. Since knowledge of the workload's spatial and\
  \ temporal locality is necessary to model these use cases, our framework was instrumental\
  \ in quantifying their performance benefits. The proposed methodology provides detailed\
  \ understanding of the storage activity of large-scale applications, and enables\
  \ a wide spectrum of storage studies, without the requirement to access application\
  \ code and full application deployment."
publication: '*IEEE Compututer Architecture Letters*'
doi: 10.1109/L-CA.2011.37
---
