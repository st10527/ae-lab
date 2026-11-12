---
title: 'Home'
date: 2023-10-24
type: landing

design:
  spacing: "5rem"

sections:
  # About Me
  - block: resume-biography
    id: about
    content:
      username: me
      text: ""
    design:
      spacing:
        padding: ["3rem", 0, "2rem", 0]

  # Research Interests
  - block: features
    id: research
    content:
      title: Research Interests
      text: ""
      items:
        - name: UAV Networks
          icon: paper-airplane
          description: Flying Ad-hoc Networks (FANETs), path planning, swarm intelligence, and heterogeneous UAV collaboration for data gathering.
          
        - name: Edge Computing
          icon: cpu-chip
          description: Multi-Access Edge Computing (MEC), intelligent task migration, Deep Q-Learning optimization, and mobile crowdsourcing.
          
        - name: Edge AI Applications
          icon: wrench-screwdriver
          description: "Smart construction site monitoring (w/ Civil Eng.), hydrological data analysis (w/ Water Resources), and intelligent evacuation systems (w/ Architecture)."
          
        - name: FinTech & AI
          icon: chart-bar
          description: AI/ML in financial systems, blockchain networks, big data analytics, and algorithmic trading strategies.
    design:
      columns: "2"
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  # Experience & Honors
  - block: markdown
    id: experience
    content:
      title: Experience & Honors
      text: |
        ### Professional Experience
        
        | Period | Position | Organization |
        |--------|----------|-------------|
        | 2023 - Present | Assistant Professor | Tamkang University |
        | 2022 - 2023 | Visiting Scholar (NSTC Program) | Iowa State University, USA |
        | 2018 | Lecturer | National Chengchi University |
        | 2017 - 2023 | Research Assistant | NSTC Research Projects |
        
        ### Academic Service & International Conferences
        
        | Year | Role | Event / Venue |
        |------|------|---------------|
        | 2026 | Technical Program Co-Chair | International Workshop on Mobile IoT (MIoT 2026), IEEE Ubi-Media 2026, Penang, Malaysia |
        | 2025 | Technical Program Co-Chair & Session Chair | International Workshop on Mobile IoT (MIoT 2025), IEEE Ubi-Media 2025, Bangkok, Thailand |
        | 2022 | Conference Registration Chair | IEEE World Congress on Services (IEEE SERVICES 2022), Barcelona, Spain |
        | Ongoing | Journal Reviewer | *Journal of Applied Science and Engineering (JASE)* (Scopus/ESCI) |
        
        ### Awards & Honors
        
        | Year | Award |
        |------|-------|
        | 2019 | Silver Medal - 7th Information Application Innovation Competition |
        | 2018 | **Champion** - HP Enterprise AI Hackathon (Taiwan) |
        | 2018 | NCU Outstanding Innovation Team Award |
        | 2017 | Merit Award - 10th Chien-Li-Ma Startup Competition |
        | 2016 | Excellence Award - Ministry of Economic Affairs Fresh Competition |
    design:
      columns: 1
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  # Featured Publications
  - block: collection
    id: publications
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        featured_only: true
      count: 4
    design:
      view: card
      columns: 2
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  # Teaching
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |
        ### Undergraduate Courses
        
        | Course | Description |
        |--------|-------------|
        | Programming Language (C) | Fundamentals of C programming |
        | Logic Design Lab | Digital circuit design and implementation |
        | Enterprise Application Practice | Industry-oriented software development |
        | Open Source Software Practice | Git, Linux, and open-source tools |
        
        ### Graduate Courses (English-Taught)
        
        | Course | Description |
        |--------|-------------|
        | Software-Centric Technologies | Modern software engineering practices |
        | Introduction to Digital Systems | Digital system design fundamentals |
        | Cloud Security Practice | Cloud computing security and practices |
        | Distributed Networks | P2P, blockchain, and distributed systems |
        
        ### Courses I Can Teach
        
        **Basic:** Computer Programming, Data Structure, Computer Networks, Machine Learning Introduction
        
        **Advanced:** Wireless Sensor Networks, Edge Computing, Optimization Theory, Deep Learning, Queueing Theory
    design:
      columns: 1
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  # Student Supervision
  - block: markdown
    id: students
    content:
      title: Student Supervision
      text: |
        ### Current Students (在學學生)
        
        **Graduate Students (碩士生)**
        
        | Name | Program | Research Topic |
        |------|---------|----------------|
        | 王佳美 (Gabriella Alicia Setiawan) | 資工系全英碩士班 | Cross-Lingual Knowledge Distillation & Federated Distillation in Wireless Edge Networks *(IEEE PIMRC 2026)* |
        | 黃祥銘 (Shiang-Ming Huang) | 資工系碩士班 | 車載網路結合 Actor-Critic / MADDPG 與 Edge Computing 的智慧中繼與任務調度 *(IEEE APWCS 2026)* |
        
        ---
        
        ### Join My Research Team! (招生中)
        
        I am actively recruiting motivated students interested in:
        - **UAV Systems & Path Planning** - Algorithm design for drone swarms
        - **Edge AI & IoT** - Embedded systems and real-time computing
        - **FinTech Applications** - AI/ML in financial data analysis
        - **Wireless Networks** - 5G/6G and satellite communications
        
        ---
        
        ### Student Awards (學生獲獎)
        
        🥉 [**2025 ICPC Taiwan PUPC Bronze Medal**](/award/2025-icpc-pupc/)  
        Ting Yang Lim, KAI EN LIN, Chen-Yu Chen
        
        🏆 [**2025 TKU CSIE Project Competition - Merit Award**](/award/2025-csie-project/)  
        歐陽林、張福明、沈千淦 — Campus International Friendship Matching System
        
        ---
        
        ### Research Projects & Industry-Academia Collaboration (研究計畫與產學合作)
        
        📡 [**NSTC Industry-Academia Project: Edge AIoT Real-Time Construction Safety Early Warning System**](/project/2026-nstc-construction-aiot/)  
        **營建工地邊緣 AIoT 即時工安預警系統：感知推理與斷網通訊之整合與場域驗證**  
        *Grant No.: NSTC 115-2622-E-032-006 (2026/11 – 2027/10) | Role: PI (w/ Co-PI Prof. Ming-Hsiu Tsai, Dept. of Civil Engineering) | Partner: 任泰技術顧問有限公司*
        
        🏗️ [**On-Premise Real-Time Edge AI Monitoring System for Smart Construction**](/project/2025-smart-construction-edge-ai/)  
        **智慧工地與場域安全之全地端即時 AI 監控系統**  
        *2025 – 2026 | Role: PI | Partner: 千溢科技股份有限公司* — Lightweight YOLO with Knowledge Distillation on NVIDIA Jetson Orin Nano for 24/7 site safety monitoring.
        
        ---
        
        ### Past Projects (歷年獲獎專案)
        
        My previous student projects have won multiple awards including:
        - HP AI Hackathon Taiwan Champion (2018)
        - NCU Outstanding Innovation Team (2018)
        - Information Application Innovation Silver Medal (2019)
    design:
      columns: 1
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  # Contact
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |
        📧 **Email:** 167320@o365.tku.edu.tw
        
        🏢 **Office:** Department of Computer Science & Information Engineering  
        Tamkang University, New Taipei City, Taiwan
        
        🔗 **Links:**  
        [ORCID](https://orcid.org/0000-0003-3735-0613)
        
        ---
        
        *Feel free to contact me if you are interested in research collaboration or joining my lab!*
    design:
      columns: 1
      spacing:
        padding: ["3rem", 0, "3rem", 0]
---