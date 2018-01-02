---
layout: archive
title:  "信息可视化笔记"
date:   2018-01-01 22:07:50 +0800
modified:
excerpt:"学习笔记"
tags: []
image: 
  feature: note.gif
  teaser:
---

在此展示我所触及的笔记


<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->

尝试着去做一下页面，或许你会有不一样的体验。