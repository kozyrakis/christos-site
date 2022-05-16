---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Decoupling Datacenter Studies from Access to Large-Scale Applications: A Modeling
  Approach for Storage Workloads'
subtitle: ''
summary: ''
authors:
- Christina Delimitrou
- Sriram Sankar
- Kushagra Vaid
- admin
tags: []
categories: []
date: '2011-11-01'
lastmod: 2022-05-15T13:35:17-07:00
featured: false
draft: false
venue: IISWC'11

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
publishDate: '2022-05-15T20:35:17.204352Z'
publication_types:
- '1'
abstract: "The cost and power impact of suboptimal storage configurations is significant\
  \ in datacenters (DCs) as inefficiencies are aggregated over several thousand servers\
  \ and represent considerable losses in capital and operating costs. Designing performance,\
  \ power and cost-optimized systems requires a deep understanding of target workloads,\
  \ and mechanisms to effectively model different storage design choices. Traditional\
  \ benchmarking is invalid in cloud data-stores, representative storage profiles\
  \ are hard to obtain, while replaying the entire application in all storage configurations\
  \ is impractical both from a cost and time perspective. Despite these issues, current\
  \ workload generators are not able to accurately reproduce key aspects of real application\
  \ patterns. Some of these features include spatial and temporal locality, as well\
  \ as tuning the intensity of the workload to emulate different storage system configurations.\
  \ To address these limitations, we propose a modeling and characterization framework\
  \ for large-scale storage applications. As part of this framework we use a state\
  \ diagram-based storage model, extend it to a hierarchical representation and implement\
  \ a tool that consistently recreates I/O loads of DC applications. We present the\
  \ principal features of the framework that allow accurate modeling and generation\
  \ of storage workloads and the validation process performed against ten original\
  \ DC applications traces. Furthermore, using our framework, we perform an in-depth,\
  \ per-thread characterization of these applications and provide insights on their\
  \ behavior. Finally, we explore two practical applications of this methodology:\
  \ SSD caching and defragmentation benefits on enterprise storage. In both cases\
  \ we observe significant speedup for most of the examined applications. Since knowledge\
  \ of the workload's spatial and temporal locality is necessary to model these use\
  \ cases, our framework was instrumental in quantifying their performance benefits.\
  \ The proposed methodology provides a detailed understanding on the storage activity\
  \ of large-scale applications and enables a wide spectrum of storage studies without\
  \ the requirement for access to real applications and full application deployment."
publication: '*Proceedings of the 2011 IEEE International Symposium on Workload Characterization
  (IISWC)*'
doi: 10.1109/IISWC.2011.6114196
---
