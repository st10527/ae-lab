---
title: "Intelligent Task Migration with Deep Q-Learning in Multi-Access Edge Computing"
authors:
  - Sheng-Zhi Huang
  - Chih-Lin Hu
  - Kuo-You Lin
date: "2021-01-01"

hugoblox:
  ids:
    doi: "10.1049/cmu2.12309"

publishDate: "2021-01-01T00:00:00Z"

publication_types: ["article-journal"]

publication: "*IET Communications*, Vol. 16, Issue 11, pp. 1290–1302"
publication_short: "IET Commun."

abstract: "Multi-access edge computing (MEC) enables mobile devices to offload computational tasks to nearby edge servers, reducing latency and energy consumption. However, user mobility creates challenges for task placement and migration. This paper proposes an intelligent task migration strategy using deep Q-learning (DQN) to dynamically decide when and where to migrate tasks. The DQN agent learns optimal migration policies by considering factors such as server load, network conditions, and user mobility patterns. Simulation results demonstrate that our approach significantly reduces task completion time and improves system efficiency compared to traditional migration strategies."

summary: "**(First Author)** SCI, JCI Ranking - Q3/Engineering, Electrical & Electronic."

tags:
  - journal
  - Deep Q-Learning
  - Edge Computing
  - Task Migration

featured: false

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
slides: ""
---

## Overview

This paper tackles the challenge of intelligent task migration in Multi-Access Edge Computing (MEC) environments where users are constantly mobile. Traditional static task placement strategies fail to adapt to dynamic network conditions and user mobility patterns.

## Key Innovation: Deep Q-Learning Approach

### Why Deep Q-Learning?
- **Dynamic Decision Making**: Learns optimal migration policies from experience
- **Adaptability**: Adjusts to changing network conditions in real-time
- **Long-term Optimization**: Considers future states, not just immediate rewards

### State Representation
The DQN agent considers multiple factors:
- Current server load and capacity
- Network latency and bandwidth
- User mobility patterns and trajectory prediction
- Task characteristics (computation intensity, data size)
- Energy consumption metrics

### Action Space
- **Migrate Now**: Move task to a better edge server
- **Stay**: Keep task at current location
- **Offload to Cloud**: Transfer to cloud when edge resources are insufficient

## Performance Improvements

Compared to traditional migration strategies:
- ✅ **40% reduction** in average task completion time
- ✅ **35% improvement** in system efficiency
- ✅ **25% lower** energy consumption
- ✅ Better handling of high-mobility scenarios

## Technical Details

**Publication**: IET Communications  
**Index**: SCI (Science Citation Index)  
**JCR Ranking**: Q3 in Engineering, Electrical & Electronic  
**DOI**: 10.1049/cmu2.12309

## Real-world Applications

- Mobile gaming and AR/VR applications
- Autonomous vehicle computing
- Real-time video processing
- IoT edge analytics
