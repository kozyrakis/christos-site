---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'ECHO: Recreating Network Traffic Maps for Datacenters with Tens of Thousands
  of Servers'
subtitle: ''
summary: ''
authors:
- Christina Delimitrou
- Sriram Sankar
- Aman Kansal
- admin
tags: []
categories: []
date: '2012-11-01'
lastmod: 2022-05-15T13:35:16-07:00
featured: false
draft: false
venue: IISWC'12

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
publishDate: '2022-05-15T20:35:16.468893Z'
publication_types:
- '1'
abstract: Large-scale datacenters now host a large part of the world's data and computation,
  which makes their design a crucial architectural challenge. Datacenter (DC) applications,
  unlike traditional workloads, are dominated by user patterns that only emerge in
  the large-scale. This creates the need for concise, accurate and scalable analytical
  models that capture both their temporal and spatial features and can be used to
  create representative activity patterns. Unfortunately, previous work lacks the
  ability to track the complex patterns that are present in these applications, or
  scales poorly with the size of the system. In this work, we focus on the network
  aspect of datacenter workloads. We present ECHO, a scalable and accurate modeling
  scheme that uses hierarchical Markov Chains to capture the network activity of large-scale
  applications in time and space. ECHO can also use these models to re-create representative
  network traffic patterns. We validate the model against real DC-scale applications,
  such as Websearch and show marginal deviations between original and generated workloads.
  We verify that ECHO captures all the critical features of DC workloads, such as
  the locality of communication and burstiness and evaluate the granularity necessary
  for this. Finally we perform a detailed characterization of the network traffic
  for workloads in DCs of tens of thousands of servers over significant time frames.
publication: '*Proceedings of the 2012 IEEE International Symposium on Workload Characterization
  (IISWC)*'
doi: 10.1109/IISWC.2012.6402896
---
