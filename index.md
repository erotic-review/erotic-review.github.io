---
title: "erotic-review へようこそ"
---

# erotic-review とは  
素人目線で最新AV作品をレビュー・比較するブログです。  
毎週2本のペースでレビューを公開予定。詳細は下の記事からどうぞ！

## 最新記事一覧

<ul>
  {% for post in paginator.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>— {{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>

<nav>
  {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path }}">← 新しい記事へ</a>
  {% endif %}
  {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path }}">古い記事へ →</a>
  {% endif %}
</nav>
