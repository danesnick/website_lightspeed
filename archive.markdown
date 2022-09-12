---
layout: page
title: Blog Archive
permalink: /archive
---

I've archived my blog for now. Below you can see posts I've written between 2020-2022.

<ul class="homepage-list" style="list-style:none;padding:1rem 0;">
{% for post in site.posts %}
  <li style="align-items:center;display:flex;flex-wrap:wrap;justify-content:space-between;margin-bottom:10px;">
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    <time style="font-size:90%;" datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %-d, %Y" }}</time>
  </li>
{% endfor %}
</ul>
