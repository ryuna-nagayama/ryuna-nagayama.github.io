---
page_id: about
layout: about
title: about
permalink: /
subtitle: Ph.D. student @ <a href='https://www.u-tokyo.ac.jp/en/'>UTokyo</a>

profile:
  align: right
  image: Oriprof.jpg
  image_circular: false # crops the image to make it circular
  more_info: > #<p>Science Building 1, The University of Tokyo</p> #<p>7-3-1, Hongo, Bunkyo-ku</p> #<p>Tokyo, Japan, 113-8654</p>

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

I am a 3rd-year Ph.D. student in the [Ito group](https://webpark2072.sakura.ne.jp/laben/) at [Department of Physics](https://www.phys.s.u-tokyo.ac.jp/en/), [Graduate School of Science](https://www.s.u-tokyo.ac.jp/en/), [the University of Tokyo](https://www.u-tokyo.ac.jp/en/index.html).

I have interests in nonequilibrium thermodynamics, optimal transport, and a vast and elegant structure hidden behind what is now visible to us.

I also love origami as a hobby. 
