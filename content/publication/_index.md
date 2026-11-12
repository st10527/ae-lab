---
title: Publications
type: landing

design:
  spacing: "4rem"

sections:
  # 準備投稿/已提交的文章 (Submitted Papers) - 若有新投稿可取消註解並加上 submitted 標籤
  # - block: collection
  #   id: submitted
  #   content:
  #     title: 📝 Submitted / Under Review
  #     subtitle: Papers currently under review or in preparation
  #     filters:
  #       folders:
  #         - publication
  #       tags:
  #         - submitted
  #     sort_by: 'Date'
  #     sort_ascending: false
  #     count: 0
  #     offset: 0
  #   design:
  #     view: card
  #     columns: 3
  #     show_read_time: false
  
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
      view: card
      columns: 3
      show_read_time: false
  
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
      view: card
      columns: 3
      show_read_time: false
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
      view: card
      columns: 2
      show_read_time: false
---
