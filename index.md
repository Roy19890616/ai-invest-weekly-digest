---
title: AI + 投資週報
---

每週四早上自動產出，彙整過去一週的 **AI 技術圈熱議、美股／科技股、台股、總體經濟、國際經濟情勢** 與下週觀察。

## 歷期週報

{% assign reports = site.pages | sort: "path" | reverse %}
{% for r in reports %}{% if r.path contains 'reports/' %}{% unless r.path contains 'README' %}- [{{ r.path | remove: 'reports/' | remove: '.md' }}]({{ r.url | relative_url }})
{% endunless %}{% endif %}{% endfor %}

---

> 本站內容為公開新聞之彙整摘要，僅供參考，**非投資建議**。
