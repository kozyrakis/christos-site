---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'FARM: A Prototyping Environment for Tightly-Coupled, Heterogeneous Architectures'
subtitle: ''
summary: ''
authors:
- Tayo Oguntebi
- Sungpack Hong
- Jared Casper
- Nathan Bronson
- admin
- Kunle Olukotun
tags:
- coprocessors
- prototyping
- FPGA communication
- HyperTransport
- accelerators
- coherent FPGA
categories: []
date: '2010-05-01'
lastmod: 2022-05-15T13:35:18-07:00
featured: false
draft: false
venue: FCCM'10

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
publishDate: '2022-05-15T20:35:18.763460Z'
publication_types:
- '1'
abstract: Computer architectures are increasingly turning to parallelism and heterogeneity
  as solutions for boosting performance in the face of power constraints. As this
  trend continues, the challenges of simulating and evaluating these architectures
  have grown. Hardware prototypes provide deeper insight into these systems when compared
  to simulators, but are traditionally more difficult and costly to build. We present
  the Flexible Architecture Research Machine (FARM), a hardware prototyping system
  based on an FPGA coherently connected to a multiprocessor system. FARM substantially
  reduces the difficulty and cost of building hardware prototypes by providing a ready-made
  framework for communicating with a custom design on the FPGA. FARM ensures efficient,
  low-latency communication with the FPGA via a variety of mechanisms, allowing a
  wide range of applications to effectively utilize the system. FARM’s coherent FPGA
  includes a cache and participates in coherence activities with the processors. This
  tight coupling allows for realistic, innovative architecture prototypes that would
  otherwise be extremely difficult to simulate. We evaluate FARM by providing the
  reader with a profile of the overheads introduced across the full range of communication
  mechanisms. This will guide the potential FARM user towards an optimal configuration
  when designing his prototype.
publication: '*Proceedings of the  18th IEEE International Symposium on Field-Programmable
  Custom Computing Machines (FCCM)*'
doi: 10.1109/FCCM.2010.41
---
