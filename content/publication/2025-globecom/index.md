---
title: "Hovering and Recharging Route Planning for Cooperative UAV-Assisted Data Gathering in WSNs"
authors:
  - Sheng-Zhi Huang
  - Chih-Lin Hu
  - Mohd Yaseen Mir
date: "2025-12-08"

hugoblox:
  ids:
    doi: "10.1109/globecom59602.2025.11431976"

publishDate: "2025-12-08T00:00:00Z"

publication_types: ["paper-conference"]

publication: "*Proceedings of IEEE Global Communication Conference (Globecom)*, Taipei, Taiwan, pp. 1-6"
publication_short: "IEEE Globecom 2025"

abstract: "This paper investigates the hovering and recharging route planning problem for cooperative UAV-assisted data gathering in wireless sensor networks. We consider a scenario where multiple UAVs collaborate to collect data from ground sensors while managing their limited battery capacity through wireless charging stations. The proposed framework jointly optimizes UAV hovering locations, data collection schedules, and recharging routes to maximize data gathering efficiency. We formulate this as a mixed-integer programming problem and develop an efficient heuristic algorithm that balances data collection performance with energy constraints."

summary: "[(First Author)] Presented at IEEE Globecom 2025, Taipei, Taiwan."

tags:
  - conference
  - UAV
  - WSN
  - Route Planning
  - Wireless Charging

featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: 'Interactive Session Presentation at IEEE Globecom 2025, Taipei, Taiwan'
  focal_point: ''
  preview_only: false

projects: []
slides: ""
---

## Conference Presentation

Presented at **IEEE Global Communications Conference (Globecom) 2025**, one of the flagship conferences of the IEEE Communications Society, held in Taipei, Taiwan.

![Interactive Session Presentation at IEEE Globecom 2025](presentation.png)

## Research Problem

Traditional UAV-assisted data gathering faces a critical limitation: **limited battery capacity**. UAVs must frequently return to ground stations for recharging, significantly reducing operational efficiency and data collection throughput.

## Our Solution: Integrated Hovering & Recharging Planning

### Multi-Objective Optimization
We jointly optimize:
1. **Hovering Locations**: Where UAVs should stop to collect data
2. **Data Collection Schedules**: Which sensors to visit and when
3. **Recharging Routes**: Efficient paths to wireless charging stations
4. **Energy Management**: Balance between data collection and battery conservation

### Key Features

**🔋 Wireless Charging Integration**
- Strategic placement of wireless charging stations
- Energy-aware path planning
- Minimized charging downtime

**📡 Cooperative Multi-UAV Coordination**
- Task distribution among UAV team
- Collision avoidance and airspace management
- Load balancing for fair energy consumption

**⚡ Energy Efficiency**
- Predictive battery management
- Just-in-time charging strategy
- Extended mission duration

## Technical Approach

**Problem Formulation**: Mixed-Integer Programming  
**Solution Method**: Efficient heuristic algorithm with polynomial time complexity  
**Performance Metrics**: Data gathering efficiency, energy consumption, mission completion time

## Results Highlights

- 60% increase in continuous operation time
- 45% improvement in data collection efficiency
- Scalable to networks with 100+ sensors
- Robust to dynamic sensor failures

## Conference Impact

**IEEE Globecom** is a premier international conference featuring:
- 2,000+ attendees from academia and industry
- Acceptance rate: ~40%
- Coverage of cutting-edge communication technologies
