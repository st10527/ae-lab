---
title: Publications
type: landing

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
  #     view: citation
  #     columns: 1
  
  # 期刊論文 (Journal Papers)
  - block: collection
    id: journals
    content:
      title: 📚 Journal Papers
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
  
  # 專利 (Patents)
  - block: collection
    id: patents
    content:
      title: 🏆 Patents
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