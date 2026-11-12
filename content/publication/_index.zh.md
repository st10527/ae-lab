---
title: 著作發表
type: landing

design:
  spacing: "3.5rem"

sections:
  # ───────────────────────── Filter by Year ─────────────────────────
  - block: markdown
    id: year-filter
    content:
      title: ""
      text: |
        <div class="aelab-year-filter max-w-5xl mx-auto p-5 sm:p-6 bg-white dark:bg-slate-900/90 rounded-2xl border border-slate-200 dark:border-slate-800 shadow-md">
          <div class="flex flex-col md:flex-row md:items-center justify-between gap-4 pb-4 border-b border-slate-100 dark:border-slate-800">
            <div class="flex items-center gap-3">
              <div class="w-10 h-10 rounded-xl bg-primary-100 dark:bg-primary-900/50 text-primary-700 dark:text-primary-300 flex items-center justify-center font-bold text-lg">
                📅
              </div>
              <div>
                <h3 class="text-xl font-bold text-slate-900 dark:text-white tracking-tight">
                  著作年度篩選
                </h3>
                <p class="text-sm text-slate-500 dark:text-slate-400">
                  預設顯示近五年發表（2022–2026）· 點擊可切換特定年度或檢視歷年全部
                </p>
              </div>
            </div>
            <div id="filter-status-pill" class="inline-flex items-center self-start md:self-auto px-4 py-1.5 rounded-full text-sm font-semibold bg-primary-50 dark:bg-primary-950/60 text-primary-700 dark:text-primary-300 border border-primary-200/60 dark:border-primary-800/60">
              顯示中：近五年 (14 篇)
            </div>
          </div>

          <div class="flex flex-wrap items-center gap-2.5 pt-4" id="pub-year-buttons">
            <button type="button" data-filter="recent5" class="pub-year-btn active">
              ⭐ 近五年 (2022–2026)
            </button>
            <button type="button" data-filter="all" class="pub-year-btn">
              歷年全部 (24)
            </button>
            <span class="w-px h-6 bg-slate-200 dark:bg-slate-700 mx-1 hidden sm:inline-block"></span>
            <button type="button" data-filter="2026" class="pub-year-btn">2026 (7)</button>
            <button type="button" data-filter="2025" class="pub-year-btn">2025 (4)</button>
            <button type="button" data-filter="2024" class="pub-year-btn">2024 (1)</button>
            <button type="button" data-filter="2023" class="pub-year-btn">2023 (1)</button>
            <button type="button" data-filter="2022" class="pub-year-btn">2022 (1)</button>
            <button type="button" data-filter="earlier" class="pub-year-btn">2021 以前 (10)</button>
          </div>
        </div>

        <script>
        (function() {
          function initPubYearFilter() {
            var buttons = document.querySelectorAll('.pub-year-btn');
            var items = document.querySelectorAll('.pub-list-item.view-citation');
            var sections = [
              document.getElementById('under-review'),
              document.getElementById('journals'),
              document.getElementById('conferences'),
              document.getElementById('patents')
            ].filter(Boolean);
            var statusPill = document.getElementById('filter-status-pill');

            if (!buttons.length || !items.length) return;

            function applyFilter(filter) {
              var count = 0;
              buttons.forEach(function(btn) {
                if (btn.getAttribute('data-filter') === filter) {
                  btn.classList.add('active');
                } else {
                  btn.classList.remove('active');
                }
              });

              items.forEach(function(item) {
                var yStr = item.getAttribute('data-year') || '';
                var y = parseInt(yStr, 10);
                var match = false;
                if (filter === 'all') {
                  match = true;
                } else if (filter === 'recent5') {
                  match = y >= 2022;
                } else if (filter === 'earlier') {
                  match = y <= 2021;
                } else {
                  match = (yStr === filter);
                }

                if (match) {
                  item.style.display = '';
                  count++;
                } else {
                  item.style.display = 'none';
                }
              });

              sections.forEach(function(sec) {
                var secItems = sec.querySelectorAll('.pub-list-item.view-citation');
                var hasVisible = false;
                secItems.forEach(function(it) {
                  if (it.style.display !== 'none') hasVisible = true;
                });
                sec.style.display = hasVisible ? '' : 'none';
              });

              if (statusPill) {
                var isZh = document.documentElement.lang && document.documentElement.lang.indexOf('zh') !== -1;
                var text = '';
                if (filter === 'recent5') {
                  text = isZh ? '顯示中：近五年 (2022–2026) · ' + count + ' 篇' : 'Showing: Past 5 Years (2022–2026) · ' + count + ' items';
                } else if (filter === 'all') {
                  text = isZh ? '顯示中：歷年全部 · ' + count + ' 篇' : 'Showing: All Publications · ' + count + ' items';
                } else if (filter === 'earlier') {
                  text = isZh ? '顯示中：2021 及以前 · ' + count + ' 篇' : 'Showing: 2021 & Earlier · ' + count + ' items';
                } else {
                  text = isZh ? '顯示中：' + filter + ' 年度 · ' + count + ' 篇' : 'Showing: Year ' + filter + ' · ' + count + ' items';
                }
                statusPill.textContent = text;
              }
            }

            buttons.forEach(function(btn) {
              btn.onclick = function() {
                applyFilter(this.getAttribute('data-filter'));
              };
            });

            applyFilter('recent5');
          }

          if (document.readyState === 'loading') {
            document.addEventListener('DOMContentLoaded', initPubYearFilter);
          } else {
            initPubYearFilter();
          }
        })();
        </script>
    design:
      columns: 1
      spacing:
        padding: ["1.5rem", 0, "0.5rem", 0]

  # 審查中論文 (Manuscripts Under Review)
  - block: collection
    id: under-review
    content:
      title: 📝 審查中論文 (Manuscripts Under Review)
      text: 已投稿並正於國際頂級期刊同儕審查中（IEEE Communications Letters、Computer Networks、IEEE IoT-J）之最新研究手稿。
      filters:
        folders:
          - publication
        tags:
          - under-review
      sort_by: 'Date'
      sort_ascending: false
      count: 0
      offset: 0
    design:
      view: citation
      columns: 1
      css_class: "bg-amber-50/60 dark:bg-amber-950/20 border-b border-amber-200/50 dark:border-amber-900/30"

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
