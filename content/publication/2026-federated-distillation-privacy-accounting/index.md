---
title: "Privacy Accounting Determines the Screening Dimension: Knowledge Procurement for Federated Distillation at the Edge"
authors:
  - Sheng-Zhi Huang
date: "2026-10-01"

publishDate: "2026-10-01T00:00:00Z"

publication_types: ["manuscript"]

publication: "*Computer Networks* (Elsevier), under review (Manuscript #COMNET-D-26-09160)"
publication_short: "Under Review · Computer Networks (Elsevier)"

abstract: "An edge operator can improve its model by buying perturbed predictions from nearby devices; in our setting this costs under a fifth of a model upload in uplink traffic, even at full coverage. A device's cost per prediction and its privacy sensitivity are private and unverifiable, which seems to pose a two-dimensional screening problem. We show that the unit of privacy accounting decides whether it does. A device answers many queries per round from one dataset, so its releases must be accounted over the round; it then divides one budget between how many answers to upload and how faithful each is, and with costs linear in both, that division reduces its two private costs exactly to one number, its reservation price. A short menu then screens devices, without reports or audits. Under per-query accounting two devices' cost ranking can reverse with the amount purchased, so no scalar type need exist. The optimal finite menu is computable exactly in polynomial time, with a near-optimality certificate under a payment budget. Paying more buys coverage, not cleaner predictions. In simulation the menu raises profit by 16.7% over the best posted price, and four contracts capture nearly all of it; a protocol fixing one privacy budget for every device gives up 4–8%, and the best additive aggregation of the two costs, fitted in hindsight, still loses on every instance. In learning experiments run below the round-level noise scale, purchased knowledge beats a paid-noise control when the operator's labels are scarce and loses when abundant."

summary: "[(Sole & Corresponding Author)] Submitted to Computer Networks (Elsevier, Manuscript #COMNET-D-26-09160). Supported by National Science and Technology Council (NSTC 115-2622-E-032-006)."

tags:
  - under-review
  - Federated Distillation
  - Incentive Mechanism
  - Contract Theory
  - Local Differential Privacy
  - Privacy Accounting
  - Edge Computing

featured: false

links:
  - name: Zenodo Code & Data
    url: https://doi.org/10.5281/zenodo.24094577
    icon: brands/github

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects:
  - 2026-nstc-construction-aiot
slides: ""
---
