---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Pocket: Elastic Ephemeral Storage for Serverless Analytics'
subtitle: ''
summary: ''
authors:
- Ana Klimovic
- Yawen Wang
- Patrick Stuedi
- Animesh Trivedi
- Jonas Pfefferle
- admin
tags: []
categories: []
date: '2018-10-01'
lastmod: 2022-05-15T13:35:11-07:00
featured: false
draft: false
venue: OSDI'18

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
publishDate: '2022-05-15T20:35:11.715802Z'
publication_types:
- '1'
abstract: Serverless computing is becoming increasingly popular, enabling users to
  quickly launch thousands of short-lived tasks in the cloud with high elasticity
  and fine-grain billing. These properties make serverless computing appealing for
  interactive data analytics. However exchanging intermediate data between execution
  stages in an analytics job is a key challenge as direct communication between serverless
  tasks is difficult. The natural approach is to store such ephemeral data in a remote
  data store. However, existing storage systems are not designed to meet the demands
  of serverless applications in terms of elasticity, performance, and cost. We present
  Pocket, an elastic, distributed data store that automatically scales to provide
  applications with desired performance at low cost. Pocket dynamically rightsizes
  resources across multiple dimensions (CPU cores, network bandwidth, storage capacity)
  and leverages multiple storage technologies to minimize cost while ensuring applications
  are not bottlenecked on I/O. We show that Pocket achieves similar performance to
  ElastiCache Redis for serverless analytics applications while reducing cost by almost
  60%.
publication: '*Proceedings of the 13th USENIX Conference on Operating Systems Design
  and Implementation (OSDI)*'
---
