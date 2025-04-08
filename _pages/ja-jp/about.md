---
page_id: about
layout: about
title: 概要
permalink: /
subtitle: 博士課程学生 @ <a href='https://www.u-tokyo.ac.jp/ja/'>UTokyo</a>

profile:
  align: right
  image: Oriprof.jpg
  image_circular: false # crops the image to make it circular
  more_info: > #<p>113-8654</p><p>東京都文京区本郷7-3-1</p><p>東京大学本郷キャンパス理学部1号館</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<h1 class="post-title">
  {% if site.title == 'blank' %}
    <span class="font-weight-bold">{{ site.first_name }}</span> {{ site.middle_name }}{{ site.last_name }} <span style="font-size: 0.9em;">{{ site.japanese_name }}</span>
  {% else %}
    {{ site.title }}
  {% endif %}
</h1>
<p class="desc">{{ page.subtitle }}</p>

<h2 class="desc"><span class="contact-icons">{% include social.liquid %}</span></h2>

私は、[東京大学](https://www.u-tokyo.ac.jp/ja/) [大学院理学系研究科](https://www.s.u-tokyo.ac.jp/ja/) [物理学専攻](https://www.phys.s.u-tokyo.ac.jp/) [伊藤研究室](https://webpark2072.sakura.ne.jp/lab/)の大学院生（博士後期課程2年）です。

非平衡熱力学と最適輸送理論、そして今見えているものの背後にあるより巨大な構造に興味があります。

趣味は折紙です。いずれ過去に創作した作品をまとめて公開する予定です。
