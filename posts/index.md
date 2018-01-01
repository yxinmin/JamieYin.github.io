---
layout: archive
title:  "文章"
date:   2017-11-30 22:07:50 +0800
modified:
excerpt:"学习笔记"
tags: []
image:
  feature: note.gif
  teaser:
  
---



在此展示我所触及的笔记

内容如下：信息可视化笔记 &  Web笔记

<div class="tiles">
{% for post in site.categories.posts %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 posts 的列出来-->

尝试着去做一下页面，或许你会有不一样的体验。