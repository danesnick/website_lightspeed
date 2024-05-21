---
layout: default
title: Nicholas A. Danes, PhD
permalink: /
---
<figure>
 <img class="profile" src="/images/me.jpg" alt="Me!">
</figure>

My name is Nicholas A. Danes and I'm a Computational Scientist, helping researchers with their High Performance Computing support needs at [Colorado School of Mines](https://ciarc.mines.edu). I was born and raised in the Central Valley, California, but now living in Denver, Colorado.

In 2013, I completed a Bachelor of Science in Mathematics, with a minor in Computer Science at [CSU Bakersfield](https://csub.edu). In Late 2019, I completed my PhD in Computational and Applied Mathematics at [Colorado School of Mines](https://ams.mines.edu). After graduating, I worked in the industry as a Computational Engineer for less than a year, realizing I enjoyed more of the research computing/software aspect of my work, rather than the research itself, which led me take my current position as a Computational Scientist. You can see more details in my [resume](/resume)

I have a variety of hobbies and personal interests. Most recently (as of mid 2022), I've grown a strong interest in evidence-based health & fitness, dropping 17 lbs so far this year! I also play drums in a variety of [local bands](/bands) and have been playing since high school. Finally, I enjoy hanging out with my dogs & partner, cooking, and PC gaming. 

### Latest Blog Posts (Blog is currently on hiatus)
{% for post in site.posts limit:3 %}

* <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> -  <time style="font-size:90%;" datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %-d, %Y" }}</time>  
{% endfor %}

### More About Me

* [Bands I Play In](/bands)
* [My Resume](/resume)
* [Tech I use](/uses)


### Where Else to Find Me

* [Bandcamp](https://bandcamp.com/danesnick)
* [LinkedIn](https://linkedin.com/in/nicholas-danes-a82107237)
* [GitHub](https://github.com/danesnick)
* <a rel="me" href="https://mast.hpc.social/@ndanes">Mastodon</a>

### Contact
* Email: [hello@ndanes.com](mailto:&#104;&#101;&#108;&#108;&#111;&#64;&#110;&#100;&#97;&#110;&#101;&#115;&#46;&#99;&#111;&#109;)
