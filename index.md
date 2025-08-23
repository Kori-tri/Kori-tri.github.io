---
layout: single
title: ホーム
permalink: /
---

## 近況

{% assign items = site.news | sort: 'date' | reverse %}
<ul>
{% for post in items limit: 12 %}
  <li><strong>{{ post.date | date: "%Y.%m.%d" }}</strong> {{ post.title }} — {{ post.excerpt | strip_html }}</li>
{% endfor %}
</ul>

---

- 所属：岡山大学 環境生命自然科学研究科
- 研究：貯穀害虫（コクヌストモドキ）を用いた行動生態／交尾後の選択 ほか
