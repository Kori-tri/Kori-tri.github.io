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

- 所属：東京大学 大学院総合文化研究科（予定／在籍）
- 研究：貯穀害虫（コクヌストモドキ等）を用いた行動生態／交尾後の選択 ほか
