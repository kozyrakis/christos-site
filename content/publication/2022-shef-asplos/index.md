---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'ShEF: Shielded Enclaves for Cloud FPGAs'
subtitle: ''
summary: ''
authors:
- Mark Zhao
- Mingyu Gao
- admin
tags: []
categories: []
date: '2022-03-01'
lastmod: 2022-05-15T13:35:09-07:00
featured: false
draft: false
venue: ASPLOS'22

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
publishDate: '2022-05-15T20:35:09.201145Z'
publication_types:
- '1'
abstract: FPGAs are now used in public clouds to accelerate a wide range of applications,
  including many that operate on sensitive data such as financial and medical records.
  We present ShEF, a trusted execution environment (TEE) for cloud-based reconfigurable
  accelerators. ShEF is independent from CPU-based TEEs and allows secure execution
  under a threat model where the adversary can control all software running on the
  CPU connected to the FPGA, has physical access to the FPGA, and can compromise the
  FPGA interface logic of the cloud provider. ShEF provides a secure boot and remote
  attestation process that relies solely on existing FPGA mechanisms for root of trust.
  It also includes a Shield component that provides secure access to data while the
  accelerator is in use. The Shield is highly customizable and extensible, allowing
  users to craft a bespoke security solution that fits their accelerator's memory
  access patterns, bandwidth, and security requirements at minimum performance and
  area overheads. We describe a prototype implementation of ShEF for existing cloud
  FPGAs, map ShEF to a performant and secure storage application, and measure the
  performance benefits of customizable security using five additional accelerators.
publication: '*Proceedings of the 27th ACM International Conference on Architectural
  Support for Programming Languages and Operating Systems (ASPLOS)*'
doi: 10.1145/3503222.3507733
---
