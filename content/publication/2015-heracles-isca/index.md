---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Heracles: Improving Resource Efficiency at Scale'
subtitle: ''
summary: ''
authors:
- David Lo
- Liqun Cheng
- Rama Govindaraju
- Parthasarathy Ranganathan
- admin
tags: []
categories: []
date: '2015-06-01'
lastmod: 2022-05-15T13:35:14-07:00
featured: false
draft: false
venue: ISCA'15 

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
publishDate: '2022-05-15T20:35:14.668102Z'
publication_types:
- '1'
abstract: User-facing, latency-sensitive services, such as websearch, underutilize
  their computing resources during daily periods of low traffic. Reusing those resources
  for other tasks is rarely done in production services since the contention for shared
  resources can cause latency spikes that violate the service-level objectives of
  latency-sensitive tasks. The resulting under-utilization hurts both the affordability
  and energy-efficiency of large-scale datacenters. With technology scaling slowing
  down, it becomes important to address this opportunity.We present Heracles, a feedback-based
  controller that enables the safe colocation of best-effort tasks alongside a latency-critical
  service. Heracles dynamically manages multiple hardware and software isolation mechanisms,
  such as CPU, memory, and network isolation, to ensure that the latency-sensitive
  job meets latency targets while maximizing the resources given to best-effort tasks.
  We evaluate Heracles using production latency-critical and batch workloads from
  Google and demonstrate average server utilizations of 90% without latency violations
  across all the load and colocation scenarios that we evaluated.
publication: '*Proceedings of the 42nd International Symposium on Computer Architecture
  (ISCA)*'
doi: 10.1145/2749469.2749475
---
