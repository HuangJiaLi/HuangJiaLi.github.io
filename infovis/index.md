---
layout: archive
title: "信息可视化作品集"
date: 2018-1-1T14:25:45-04:00
modified:
excerpt: 
tags: []
image: 
  feature: 
  teaser:
---
在此展示在此展示——关于信息可视化作品
<a href="https://huangjiali.github.io/infovis/visualization/QiMo/" target="_blank">![ZongTu.png](https://huangjiali.github.io/images/ZongTu.png)</a>


<div class="tiles">
{% for post in site.categories.visualization %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 visualization 的列出来-->
