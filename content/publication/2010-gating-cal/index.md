---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Power Management of Datacenter Workloads Using Per-Core Power Gating
subtitle: ''
summary: ''
authors:
- Jacob Leverich
- Matteo Monchiero
- Vanish Talwar
- Parthasarathy Ranganathan
- admin
tags:
- System architectures
- integration and modeling
- Energy-aware systems
categories: []
date: '2009-07-01'
lastmod: 2022-05-15T13:35:19-07:00
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
publishDate: '2022-05-15T20:35:19.101681Z'
publication_types:
- '2'
abstract: While modern processors offer a wide spectrum of software-controlled power
  modes, most datacenters only rely on Dynamic Voltage and Frequency Scaling (DVFS,
  a.k.a. P-states) to achieve energy efficiency. This paper argues that, in the case
  of datacenter workloads, DVFS is not the only option for processor power management.
  We make the case for per-core power gating (PCPG) as an additional power management
  knob for multi-core processors. PCPG is the ability to cut the voltage supply to
  selected cores, thus reducing to almost zero the leakage power for the gated cores.
  Using a testbed based on a commercial 4-core chip and a set of real-world application
  traces from enterprise environments, we have evaluated the potential of PCPG. We
  show that PCPG can significantly reduce a processor's energy consumption (up to
  40%) without significant performance overheads. When compared to DVFS, PCPG is highly
  effective saving up to 30% more energy than DVFS. When DVFS and PCPG operate together
  they can save up to almost 60%.
publication: '*IEEE Computer Architure Letters (CAL)*'
doi: 10.1109/L-CA.2009.46
---
