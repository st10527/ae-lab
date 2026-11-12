---
title: 'Home'
date: 2023-10-24
type: landing

design:
  spacing: "6rem"

sections:
  # ───────────────────────── Hero / Biography ─────────────────────────
  - block: resume-biography-3
    id: about
    content:
      username: me
      text: ""
      headings:
        about: Research Profile
        education: Education
        interests: Research Interests
      button:
        text: Join AE LAB
        url: "#contact"
    design:
      name:
        size: md
      avatar:
        size: large
        shape: circle
      css_class: "aelab-hero"
      spacing:
        padding: ["2rem", 0, "3rem", 0]

  # ───────────────────────── At a glance ─────────────────────────
  - block: stats
    id: stats
    content:
      title: ""
      items:
        - statistic: "21"
          description: Publications
          sub_metric: Journals · Conferences · Patents
          icon: hero/document-text
        - statistic: "4"
          description: Journal Articles
          sub_metric: IEEE OJ-COMS · IEEE Access · IET
          icon: hero/book-open
        - statistic: "2"
          description: Patents
          sub_metric: United States & Taiwan (R.O.C.)
          icon: hero/light-bulb
        - statistic: "2"
          description: Funded Projects
          sub_metric: NSTC & Industry Collaboration
          icon: hero/briefcase
    design:
      layout: compact
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  # ───────────────────────── Research ─────────────────────────
  - block: research-areas
    id: research
    content:
      title: Research Areas
      subtitle: Autonomous systems at the network edge
      text: "AE LAB studies how drones, vehicles, and IoT devices can **sense, compute, and cooperate** at the edge of wireless networks — and turns these ideas into deployable systems with industry and cross-disciplinary partners."
      items:
        - name: UAV Networks
          description: Cooperative multi-UAV data gathering, path & recharging planning, in-flight wireless power transfer, and 3D aerial delay-tolerant networking.
          icon: hero/paper-airplane
          gradient: from-blue-600 to-indigo-700
          topics: [FANETs, Wireless Charging, Route Planning, WSNs]
        - name: Edge Computing & Edge AI
          description: Multi-access edge computing, task offloading & migration with deep reinforcement learning, and federated / knowledge distillation over wireless links.
          icon: hero/cpu-chip
          gradient: from-sky-500 to-blue-700
          topics: [MEC, Deep RL, Federated Distillation, Game Theory]
        - name: Vehicular & V2X Networks
          description: Multi-hop V2X relay selection, cooperative media distribution among vehicles, and data-driven driving-safety risk prediction.
          icon: hero/truck
          gradient: from-teal-500 to-cyan-700
          topics: [V2X-MEC, Actor-Critic, Driving Safety]
        - name: AIoT for Smart Construction
          description: On-premise edge AIoT for real-time site safety — lightweight vision models, sensing gateways, and resilient disconnected communication (with Civil Engineering).
          icon: hero/wrench-screwdriver
          gradient: from-indigo-600 to-slate-800
          topics: [Edge AIoT, YOLO, Knowledge Distillation, Field Validation]
    design:
      layout: cards
      css_class: "bg-slate-50 dark:bg-slate-900/40"

  # ───────────────────────── Selected Publications ─────────────────────────
  - block: collection
    id: publications
    content:
      title: Selected Publications
      text: Recent research highlights from AE LAB. See the [full publication list](publication/) for all journals, conferences, and patents.
      filters:
        folders:
          - publication
        featured_only: true
      count: 3
      archive:
        enable: true
        text: All publications (21) →
        link: publication/
    design:
      view: card
      columns: 3
      show_read_time: false

  # ───────────────────────── Projects ─────────────────────────
  - block: collection
    id: projects
    content:
      title: Research Projects
      text: Funded research and industry–academia collaborations.
      filters:
        folders:
          - project
      count: 4
    design:
      view: card
      columns: 2
      show_read_time: false
      css_class: "bg-slate-50 dark:bg-slate-900/40"

  # ───────────────────────── Experience ─────────────────────────
  - block: resume-experience
    id: experience
    content:
      title: Experience
      username: me
    design:
      date_format: "2006"
      is_education_first: false

  # ───────────────────────── Service & Honors ─────────────────────────
  - block: markdown
    id: service
    content:
      title: Academic Service
      text: |
        <div class="aelab-service">

        | Year | Role | Event / Venue |
        |------|------|---------------|
        | 2026 | Technical Program Co-Chair | International Workshop on Mobile IoT (MIoT 2026), IEEE Ubi-Media 2026, Penang, Malaysia |
        | 2025 | Technical Program Co-Chair & Session Chair | International Workshop on Mobile IoT (MIoT 2025), IEEE Ubi-Media 2025, Bangkok, Thailand |
        | 2022 | Conference Registration Chair | IEEE World Congress on Services (IEEE SERVICES 2022), Barcelona, Spain |
        | Ongoing | Journal Reviewer | *Journal of Applied Science and Engineering (JASE)* |

        </div>
    design:
      columns: 1

  - block: resume-awards
    id: honors
    content:
      title: Honors & Awards
      username: me

  # ───────────────────────── Teaching ─────────────────────────
  - block: features
    id: teaching
    content:
      title: Teaching
      text: Undergraduate and English-taught graduate courses at Tamkang University
      items:
        - name: Programming Language (C)
          icon: code-bracket
          description: Undergraduate · Fundamentals of C programming
        - name: Logic Design Lab
          icon: cpu-chip
          description: Undergraduate · Digital circuit design and implementation
        - name: Enterprise Application Practice
          icon: building-office-2
          description: Undergraduate · Industry-oriented software development
        - name: Open Source Software Practice
          icon: command-line
          description: Undergraduate · Git, Linux, and open-source tools
        - name: Software-Centric Technologies
          icon: squares-2x2
          description: Graduate (English-taught) · Modern software engineering practices
        - name: Introduction to Digital Systems
          icon: circle-stack
          description: Graduate (English-taught) · Digital system design fundamentals
        - name: Cloud Security Practice
          icon: shield-check
          description: Graduate (English-taught) · Cloud computing security
        - name: Distributed Networks
          icon: globe-alt
          description: Graduate (English-taught) · P2P, blockchain, and distributed systems
    design:
      columns: "4"
      css_class: "bg-slate-50 dark:bg-slate-900/40"

  # ───────────────────────── Students ─────────────────────────
  - block: markdown
    id: students
    content:
      title: Students
      text: |
        <div class="aelab-students">

        #### Current Graduate Students

        | Name | Program | Research Topic |
        |------|---------|----------------|
        | 王佳美 Gabriella Alicia Setiawan | M.S., CSIE (English-taught) | Cross-lingual knowledge distillation & federated distillation in wireless edge networks *(IEEE PIMRC 2026)* |
        | 黃祥銘 Shiang-Ming Huang | M.S., CSIE | Actor-Critic / MADDPG relay selection and task scheduling in V2X-MEC *(IEEE APWCS 2026)* |

        #### Student Awards

        - 🥉 [**2025 ICPC Taiwan PUPC — Bronze Medal**](award/2025-icpc-pupc/) · Ting Yang Lim, KAI EN LIN, Chen-Yu Chen
        - 🏆 [**2025 TKU CSIE Project Competition — Merit Award**](award/2025-csie-project/) · 歐陽林、張福明、沈千淦 — Campus International Friendship Matching System

        </div>
    design:
      columns: 1

  # ───────────────────────── Join us ─────────────────────────
  - block: cta-card
    id: join
    content:
      title: Join AE LAB — 招收碩士生與專題生
      text: |
        We are looking for motivated students interested in **UAV systems**, **Edge AI & IoT**, **wireless networks (5G/6G)**, and **AI for smart construction**. Hands-on projects with NSTC and industry partners, and opportunities to publish at IEEE conferences.
      button:
        text: Contact Prof. Huang
        url: mailto:167320@o365.tku.edu.tw
        icon: hero/envelope
    design:
      card:
        css_class: "bg-gradient-to-br from-blue-700 via-indigo-800 to-slate-900 text-white"

  # ───────────────────────── Contact ─────────────────────────
  - block: contact-info
    id: contact
    content:
      title: Contact
      subtitle: Feel free to reach out for research collaboration or joining the lab.
      visit_title: Visit Us
      connect_title: Connect
      address:
        lines:
          - Autonomous Edge LAB (AE LAB)
          - Dept. of Computer Science & Information Engineering
          - Tamkang University
          - No. 151, Yingzhuan Rd., Tamsui Dist.
          - New Taipei City 251301, Taiwan
      email: 167320@o365.tku.edu.tw
      social:
        - icon: brands/orcid
          url: https://orcid.org/0000-0003-3735-0613
        - icon: brands/github
          url: https://github.com/st10527
      map_url: https://maps.google.com/?q=Tamkang+University
      show_form: false
---
