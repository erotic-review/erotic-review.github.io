---
title: "erotic-review へようこそ"
---

# erotic-review とは  
素人目線で最新AV作品をレビュー・比較するブログです。  
毎週2本のペースでレビューを公開予定。詳細は下の記事からどうぞ！

## 最新記事一覧

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>— {{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
