---
title: "Joint Knowledge–Redundancy Allocation for Federated Distillation over Lossy IoT Uplinks"
authors:
  - Sheng-Zhi Huang
  - Kun-Yu Lin
  - Mohd Yaseen Mir
date: "2026-08-28"

publishDate: "2026-08-28T00:00:00Z"

publication_types: ["manuscript"]

publication: "*IEEE Internet of Things Journal*, under review (Manuscript #IoT-73465-2026)"
publication_short: "Under Review · IEEE Internet of Things Journal"

abstract: "Collaborative learning at the network edge increasingly exchanges predictions on a shared reference set rather than model parameters, a form suited to the narrow uplinks of Internet of Things deployments, with the server buying a knowledge quota from each device under a budget. Such designs assume the allocated quota is the delivered quota, which lossy uplinks do not honor: a dropped packet erases a reference sample's prediction outright, so the server distills from a randomly truncated teacher and, under heavy loss, many runs never leave their initialization. Biasing participation toward reliable devices cannot help when every link is equally impaired, so the remedy must act on delivery. We let devices encode their predictions with random linear network coding, so that any large enough set of arriving packets rebuilds a device's complete current contribution, and let redundancy and knowledge volume compete for one budget. The decoding probability changes curvature exactly once, confining efficient operation to a concave branch on which allocation reduces to a generalized water-filling. The resulting service meets a 99% per-vector reliability target unreachable by uncoded transmission at any cost, at up to 3.4 times lower cost than replication and with no server state, and gains 0.108 on CIFAR-100 and 0.053 on Tiny-ImageNet over uncoded transmission at a loss rate of 0.8. A cache of stale predictions matches that accuracy, which we report rather than suppress. All-or-nothing decoding is also sensitive to loss correlation, and re-tuning redundancy for bursty erasure recovers at most a fifth of the shortfall."

summary: "[(First & Corresponding Author)] Submitted to IEEE Internet of Things Journal (Manuscript #IoT-73465-2026). In collaboration with NIT Srinagar and Tamkang University."

tags:
  - under-review
  - Federated Distillation
  - Edge Computing
  - Internet of Things
  - Network Coding
  - Packet Erasure
  - Resource Allocation

featured: false

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
slides: ""
---
