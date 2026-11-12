---
title: '首頁'
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
      name: 黃聖智 (Sheng-Zhi Huang)
      role: 助理教授
      affiliation: 淡江大學 資訊工程學系
      headings:
        about: 實驗室主持簡介
        experience: 主要經歷
        education: 學歷背景
        interests: 研究專長
      text: |
        我是淡江大學資訊工程學系助理教授，主持 **智慧邊緣實驗室 (Autonomous Edge LAB, AE LAB)**。主要研究領域涵蓋無人機隨意網路（FANETs / UAV Networks）、多接取邊緣運算（MEC）、邊緣人工智慧（Edge AI）、無線通訊系統以及金融科技（FinTech）等方向。博士畢業於國立中央大學通訊工程學系（2023），並曾獲國科會千里馬計畫（Graduate Students Study Abroad Program）補助，赴美國愛荷華州立大學（Iowa State University）擔任訪問學者（2022–2023）。
      experience:
        - position: 助理教授
          company: 淡江大學 資訊工程學系
          period: 2023 – 迄今
        - position: 訪問學者 (國科會千里馬計畫)
          company: 美國愛荷華州立大學 (Iowa State University)
          period: 2022 – 2023
        - position: 兼任講師
          company: 國立政治大學
          period: 2018
      education:
        - degree: 通訊工程學系 博士
          institution: 國立中央大學
          period: 2016 – 2023
        - degree: 通訊工程學系 學士
          institution: 國立中央大學
          period: 2012 – 2016
      interests:
        - 無人機網路與飛行隨意網路 (FANETs)
        - 多接取邊緣運算 (MEC) 與任務卸載
        - 空天地一體化網路 (SAGIN)
        - 邊緣人工智慧與深度強化學習 (Edge AI / DRL)
        - 金融科技 (FinTech)
        - 營建工地邊緣 AIoT 安全防護
      button:
        text: 聯絡我們 / 加入 AE LAB
        url: "#contact"
    design:
      name:
        size: md
      avatar:
        size: large
        shape: circle
      css_class: "aelab-hero"
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  # ───────────────────────── At a glance ─────────────────────────
  - block: stats
    id: stats
    content:
      title: ""
      items:
        - statistic: "21"
          description: 著作發表
          sub_metric: 期刊 · 國際會議 · 發明專利
          icon: hero/document-text
        - statistic: "4"
          description: 期刊論文
          sub_metric: IEEE OJ-COMS · IEEE Access · IET
          icon: hero/book-open
        - statistic: "2"
          description: 發明專利
          sub_metric: 美國專利 · 中華民國專利
          icon: hero/light-bulb
        - statistic: "2"
          description: 產官學合作計畫
          sub_metric: 國科會產學計畫 · 企業產學合作
          icon: hero/briefcase
    design:
      layout: compact
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  # ───────────────────────── Research ─────────────────────────
  - block: research-areas
    id: research
    content:
      title: 研究領域
      subtitle: 網路邊緣的自主協同系統
      text: "AE LAB 專注於無人機、車載系統與物聯網設備在無線網路邊緣的**感知、運算與自主協同**，並致力於將學術成果落地轉化為具備實戰驗證之系統。"
      items:
        - name: 無人機網路 (UAV Networks)
          description: 多無人機協同資料收集、路徑與充電排程規劃、空中無線能量傳輸 (WPT) 與 3D 延遲容忍網路 (DTN)。
          icon: hero/paper-airplane
          gradient: from-blue-600 to-indigo-700
          topics: [FANETs, 無線能量傳輸, 飛行路徑規劃, WSNs]
        - name: 邊緣運算與邊緣智慧 (Edge AI)
          description: 多接取邊緣運算 (MEC)、深度強化學習任務卸載與動態遷移、聯邦學習與跨模型知識蒸餾。
          icon: hero/cpu-chip
          gradient: from-sky-500 to-blue-700
          topics: [MEC, 深度強化學習, 聯邦知識蒸餾, 博弈論]
        - name: 車載通訊與 V2X (Vehicular Networks)
          description: 多躍車聯網中繼節點選取、車間協同影音串流分發、資料驅動之行車安全風險評估。
          icon: hero/truck
          gradient: from-teal-500 to-cyan-700
          topics: [V2X-MEC, Actor-Critic, 行車安全預警]
        - name: 智慧工地邊緣 AIoT (Smart Construction)
          description: 全地端邊緣 AIoT 工安即時預警系統 — 輕量化視覺感知推論、弱網與斷網自癒通訊整合 (與土木工程學系跨領域合作)。
          icon: hero/wrench-screwdriver
          gradient: from-indigo-600 to-slate-800
          topics: [邊緣 AIoT, YOLO 知識蒸餾, 斷網韌性通訊, 實務場域驗證]
    design:
      layout: cards
      css_class: "bg-slate-50 dark:bg-slate-900/40"

  # ───────────────────────── Selected Publications ─────────────────────────
  - block: collection
    id: publications
    content:
      title: 精選著作發表
      text: 實驗室近期研究代表作。完整期刊、國際會議論文與專利清單請見 [完整著作目錄](publication/)。
      filters:
        folders:
          - publication
        featured_only: true
      count: 3
      archive:
        enable: true
        text: 檢視全部著作發表 (21) →
        link: publication/
    design:
      view: card
      columns: 3
      show_read_time: false

  # ───────────────────────── Projects ─────────────────────────
  - block: collection
    id: projects
    content:
      title: 研究計畫
      text: 獲核定之國科會產學計畫與企業產學研發合作。
      filters:
        folders:
          - project
      count: 4
    design:
      view: card
      columns: 2
      show_read_time: false
      css_class: "bg-slate-50 dark:bg-slate-900/40"

  # ───────────────────────── Service ─────────────────────────
  - block: markdown
    id: service
    content:
      title: 學術服務
      text: |
        <div class="aelab-service">

        | 年度 | 擔任職位 | 會議 / 期刊 |
        |------|---------|-------------|
        | 2026 | 技術議程共同主席 (Technical Program Co-Chair) | International Workshop on Mobile IoT (MIoT 2026), IEEE Ubi-Media 2026, 馬來西亞檳城 |
        | 2025 | 技術議程共同主席 & 會議主席 (Co-Chair & Session Chair) | International Workshop on Mobile IoT (MIoT 2025), IEEE Ubi-Media 2025, 泰國曼谷 |
        | 2022 | 會議註冊主席 (Conference Registration Chair) | IEEE World Congress on Services (IEEE SERVICES 2022), 西班牙巴塞隆納 |
        | 常任 | 期刊審查委員 (Journal Reviewer) | *Journal of Applied Science and Engineering (JASE)* |

        </div>
    design:
      columns: 1

  # ───────────────────────── Teaching ─────────────────────────
  - block: features
    id: teaching
    content:
      title: 授課課程
      text: 淡江大學資工系大學部與全英語碩士班課程
      items:
        - name: 程式語言 (C)
          icon: code-bracket
          description: 大學部必選修 · C 語言核心架構與進階指標
        - name: 邏輯設計實驗
          icon: cpu-chip
          description: 大學部必修 · 數位邏輯電路實作與除錯
        - name: 企業應用實務
          icon: building-office-2
          description: 大學部選修 · 企業導向軟體開發與專案實作
        - name: 開源軟體實務
          icon: command-line
          description: 大學部選修 · Git 版本控制、Linux 與開源生態
        - name: 以軟體為中心之技術
          icon: squares-2x2
          description: 全英語碩士班 · 現代軟體架構與工程實務
        - name: 數位系統導論
          icon: circle-stack
          description: 全英語碩士班 · 數位系統架構原理與設計
        - name: 雲端安全實務
          icon: shield-check
          description: 全英語碩士班 · 雲端運算環境與容器安全實作
        - name: 分散式網路
          icon: globe-alt
          description: 全英語碩士班 · P2P 網路、區塊鏈與分散式系統
    design:
      columns: "4"
      css_class: "bg-slate-50 dark:bg-slate-900/40"

  # ───────────────────────── Students & Mentorship ─────────────────────────
  - block: markdown
    id: students
    content:
      title: 學生指導與獲獎榮譽
      text: |
        <div class="aelab-students">

        #### 指導研究生

        | 學生姓名 | 學位學程 | 研究主題 |
        |----------|---------|---------|
        | 王佳美 Gabriella Alicia Setiawan | 資工系碩士班 (全英語學程) | 無線邊緣網路之跨語言知識蒸餾與聯邦蒸餾 *(IEEE PIMRC 2026)* |
        | 黃祥銘 Shiang-Ming Huang | 資工系碩士班 | 車聯網邊緣運算之 Actor-Critic / MADDPG 中繼選取與任務排程 *(IEEE APWCS 2026)* |

        #### 學生競賽獲獎榮譽

        | 年度 | 競賽名稱 / 獲獎獎項 | 獲獎專案 / 獲獎學生 |
        |------|-------------------|-------------------|
        | 2025 | 🥉 [**ICPC Taiwan PUPC 程式競賽 銅牌獎**](award/2025-icpc-pupc/) | 林庭洋、林楷恩、陳品宇 |
        | 2025 | 🏆 [**淡江大學資工週系級專題競賽 佳作**](award/2025-csie-project/) | 校園國際交友配對系統 · 歐陽林、張福明、沈千淦 |

        </div>
    design:
      columns: 1

  # ───────────────────────── Join us ─────────────────────────
  - block: cta-card
    id: join
    content:
      title: 歡迎加入 AE LAB — 誠徵碩士生與專題生
      text: |
        實驗室積極招募對**無人機通訊與自主飛行**、**邊緣運算與 Edge AI**、**B5G/6G 無線網路**以及**智慧營建 AIoT** 感興趣的同學！提供國科會產學計畫與企業產學實作資源，並全力輔導參與 IEEE 頂級國際學術會議發表。
      button:
        text: 聯絡黃聖智老師
        url: mailto:167320@o365.tku.edu.tw
        icon: hero/envelope
    design:
      card:
        css_class: "bg-gradient-to-br from-blue-700 via-indigo-800 to-slate-900 text-white"

  # ───────────────────────── Contact ─────────────────────────
  - block: contact-info
    id: contact
    content:
      title: 聯絡方式
      subtitle: 歡迎學術交流、產學合作或學生加入實驗室諮詢。
      visit_title: 實驗室位置
      connect_title: 聯絡社群
      address:
        lines:
          - 智慧邊緣實驗室 (AE LAB)
          - 淡江大學 資訊工程學系
          - 251301 新北市淡水區英專路 151 號
      email: 167320@o365.tku.edu.tw
      social:
        - icon: brands/orcid
          url: https://orcid.org/0000-0003-3735-0613
        - icon: brands/github
          url: https://github.com/st10527
      map_url: https://maps.google.com/?q=Tamkang+University
      show_form: false
---
