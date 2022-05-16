---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Bolt: I Know What You Did Last Summer... In The Cloud'
subtitle: ''
summary: ''
authors:
- Christina Delimitrou
- admin
tags:
- data mining
- interference
- cloud computing
- security
- datacenter
- isolation
- denial of service attack
- latency
categories: []
date: '2017-04-01'
lastmod: 2022-05-15T13:35:13-07:00
featured: false
draft: false
venue: ASPLOS'17

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
publishDate: '2022-05-15T20:35:13.433969Z'
publication_types:
- '1'
abstract: Cloud providers routinely schedule multiple applications per physical host
  to increase efficiency. The resulting interference on shared resources often leads
  to performance degradation and, more importantly, security vulnerabilities. Interference
  can leak important information ranging from a service's placement to confidential
  data, like private keys. We present Bolt, a practical system that accurately detects
  the type and characteristics of applications sharing a cloud platform based on the
  interference an adversary sees on shared resources. Bolt leverages online data mining
  techniques that only require 2-5 seconds for detection. In a multi-user study on
  EC2, Bolt correctly identifies the characteristics of 385 out of 436 diverse workloads.
  Extracting this information enables a wide spectrum of previously-impractical cloud
  attacks, including denial of service attacks (DoS) that increase tail latency by
  140x, as well as resource freeing (RFA) and co-residency attacks. Finally, we show
  that while advanced isolation mechanisms, such as cache partitioning lower detection
  accuracy, they are insufficient to eliminate these vulnerabilities altogether. To
  do so, one must either disallow core sharing, or only allow it between threads of
  the same application, leading to significant inefficiencies and performance penalties.
publication: '*Proceedings of the 22nd International Conference on Architectural Support
  for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/3037697.3037703
---
