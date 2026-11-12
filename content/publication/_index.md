---
title: Publications
type: landing

design:
  spacing: "3.5rem"

sections:
  # 期刊論文 (Journal Papers)
  - block: collection
    id: journals
    content:
      title: 📚 Journal Papers
      text: Peer-reviewed international journal articles (IEEE OJ-COMS, IEEE Access, IET Communications, ITL).
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
      title: 🎤 Conference Papers
      text: International conference proceedings (IEEE Globecom, IEEE PIMRC, IEEE EDGE, IEEE VTS APWCS, IEEE GCCE, WOCC).
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
      title: 🏆 Patents
      text: Granted United States and R.O.C. (Taiwan) invention patents.
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
