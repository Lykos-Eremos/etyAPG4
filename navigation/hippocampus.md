---
layout: page
landing: list
title: 海马体
permalink: /hippocampus/
---
<div style="size=0.8em;color:#9b9b9b; margin-bottom:2em;">「灰质」上的所有文章. 前往<a href="{{site.baseurl}}/dentgyr">齿状回</a>（切换分类视图）.</div>
  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
        <div class="post-list-title">
          <a class="post-link" style='color:#869cfc' href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
        </div >
      </li>
    {% endfor %}
  </ul>