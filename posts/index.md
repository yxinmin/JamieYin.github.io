---
layout: archive
title:  "文章"
date:   2017-11-30 22:07:50 +0800
modified:
excerpt:"学习笔记"
tags: []
image:
  feature: post1.gif
  teaser: 
---
在此展示我所触及的笔记

<div class="tiles">
{% for post in site.categories.posts %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 posts 的列出来-->

### [RWD](https://jamieyin.github.io/posts/rwd/web%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0/)
### [信息可视化笔记]

尝试做一下自己没做过的事情，或许你会有不一样的发现。