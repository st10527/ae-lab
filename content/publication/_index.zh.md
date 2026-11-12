---
title: 著作發表
type: landing

design:
  spacing: "3.5rem"

sections:
  # 期刊論文 (Journal Papers)
  - block: collection
    id: journals
    content:
      title: 📚 期刊論文 (Journal Papers)
      text: 經同儕審查之國際學術期刊論文（IEEE OJ-COMS、IEEE Access、IET Communications、ITL 等）。
      filters:
        folders:
          - publication
        tags:
          - journal
      sort_by: 'Date'
      sort_ascending: false
      count: 0
      offset: 0
    design:
      view: citation
      columns: 1
  
  # 會議論文 (Conference Papers)
  - block: collection
    id: conferences
    content:
      title: 🎤 國際會議論文 (Conference Papers)
      text: 國際頂級與主要學術會議論文（IEEE Globecom、IEEE PIMRC、IEEE EDGE、IEEE VTS APWCS、IEEE GCCE、WOCC 等）。
      filters:
        folders:
          - publication
        tags:
          - conference
      sort_by: 'Date'
      sort_ascending: false
      count: 0
      offset: 0
    design:
      view: citation
      columns: 1
      css_class: "bg-slate-50 dark:bg-slate-900/40"
  
  # 專利 (Patents)
  - block: collection
    id: patents
    content:
      title: 🏆 發明專利 (Patents)
      text: 已獲核准公開之美國專利（US Patent）與中華民國發明專利。
      filters:
        folders:
          - publication
        tags:
          - patent
      sort_by: 'Date'
      sort_ascending: false
      count: 0
      offset: 0
    design:
      view: citation
      columns: 1
---
