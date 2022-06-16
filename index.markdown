---
layout: default
title: Nicholas A. Danes, PhD
permalink: /
---

<figure>
 <img class="profile" src="/images/me.jpg" alt="Me!">
</figure>


Hello! My name is Nicholas Danes and I am a Computational Scientist at Colorado School of Mines. I am also a tech nerd, drummer, dog fan and more. You can learn more about me [here](/about).


<ul class="homepage-list" style="list-style:none;padding:1rem 0;">
{% for post in site.posts %}
  <li style="align-items:center;display:flex;flex-wrap:wrap;justify-content:space-between;margin-bottom:10px;">
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    <time style="font-size:90%;" datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %-d, %Y" }}</time>
  </li>
{% endfor %}
</ul>
