---
title: "On-Premise Real-Time Edge AI Monitoring System for Smart Construction & Site Safety (智慧工地與場域安全之全地端即時 AI 監控系統)"
summary: "Industry-Academia Collaboration with Chien-Yi Technology Co., Ltd. — Deploying lightweight YOLO models with Knowledge Distillation on NVIDIA Jetson Orin Nano for 24/7 real-time construction safety monitoring."
date: 2025-08-01
tags:
  - Edge AI
  - Smart Construction
  - Model Compression
  - Knowledge Distillation
  - Industry-Academia Collaboration
---

## Project Overview (計畫概述)

* **Project Type:** Industry-Academia Collaboration (產學合作計畫 — 智慧場域 AI 感知系統)
* **Industry Partner:** Chien-Yi Technology Co., Ltd. (千溢科技股份有限公司)
* **Principal Investigator:** Prof. Sheng-Zhi Huang (黃勝志 助理教授)

---

## Industrial Challenges (產業痛點與挑戰)

Construction sites operate under harsh environmental conditions where external network bandwidth is often unstable and suffers from high latency. Traditional cloud-based AI video analytics struggle to meet the strict real-time requirements of **instant occupational safety early warning**, while also raising privacy and security concerns regarding off-site video streaming.

營建工地環境特殊，網路頻寬不穩且具高延遲風險，傳統雲端 (Cloud-based) AI 辨識方案難以滿足「即時工安預警」需求，且存在影像外流之隱私疑慮。

---

## Technical Solutions (技術解決方案)

1. **On-Premise Edge AI Architecture (全地端邊緣智能架構)**
   * Deployed **NVIDIA Jetson Orin Nano** embedded computing platforms to establish a fully on-premise monitoring system.
   * Video streams are processed and inferred directly on-site, drastically reducing dependence on external network bandwidth and eliminating transmission latency.
2. **Model Compression & Acceleration (模型輕量化與知識蒸餾)**
   * Targeted critical construction site safety hazards, including missing hardhats, missing high-visibility vests, and unauthorized intrusion into hazardous zones.
   * Adopted **YOLO-series** object detection integrated with **Knowledge Distillation** and **Model Pruning** techniques to port complex deep learning models onto resource-constrained edge devices, achieving **30+ FPS** real-time detection performance.

---

## Impact & Contributions (具體貢獻與效益)

This project empowers the partner enterprise with automated digital monitoring capabilities, transforming passive manual inspections into proactive **24/7 real-time safety warnings**, effectively reducing workplace accident risks and serving as a demonstration site for digital transformation in the construction industry.
