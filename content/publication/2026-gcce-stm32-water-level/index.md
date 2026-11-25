---
title: "Lightweight Semantic Water-Level Inference on STM32 for Edge Flood Monitoring"
authors:
  - Tzu-Hsiang Weng
  - Sheng-Zhi Huang
author_notes:
  - ""
  - "Corresponding Author"
date: "2026-10-01"

publishDate: "2026-10-01T00:00:00Z"

publication_types: ["paper-conference"]

publication: "*Proceedings of 2026 IEEE Global Conference on Consumer Electronics (IEEE GCCE 2026)* (Accepted / To Appear)"
publication_short: "IEEE GCCE 2026 (To Appear)"

abstract: "This paper presents a lightweight semantic water-level inference model for STM32-based edge flood monitoring, formulated as four-state inference over stable, rising, flood, and receding states. To reduce temporal leakage under scarce-event conditions, an event-aware training setting is adopted, where lower-magnitude events support training and augmentation while a flood event is held out for evaluation. A 17-feature depth-3 decision tree student is trained using confidence-weighted hard-label distillation from a CatBoost teacher and exported as portable C99 code for STM32 deployment. Full-stream replay validation over 2,878 cleaned water-level samples shows 100% implementation agreement with the PC-side reference implementation and an average on-board inference latency of approximately 79 µs."

summary: "[(Corresponding Author)] Accepted at IEEE GCCE 2026 (forthcoming in IEEE Xplore). Knowledge-distilled depth-3 decision tree on STM32 with ~79 µs average inference latency."

tags:
  - conference
  - Edge AI
  - STM32
  - Water-Level Monitoring
  - Semantic Inference
  - Decision Tree
  - Embedded Deployment

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

## Publication Status

Accepted for presentation at **2026 IEEE Global Conference on Consumer Electronics (IEEE GCCE 2026)** and forthcoming in the official conference proceedings.
