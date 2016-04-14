---
layout: archive
permalink: /bracelets-belts/
title: "Leather bracelets and belts"
excerpt: &excerpt "Gallery of leather bracelets and belts."
subtitle: *excerpt
modified: 2016-04-14
image: 
  teaser: stories/art/bracelets-belts/DSC02155.jpg
  thumb: stories/art/bracelets-belts/DSC02155.jpg
tags: [leather, bracelet, belt]
fullwidth: true
featured: 
ads: false
work: "Leather"
---

<ul class="th-grid">
{% for post in site.categories.bracelets-belts %}
  <li style="width: 200px;">
    <a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">
      <img class="load" src="{{ site.img }}/images/stories/art/bracelets-belts/DSC02155.jpg" data-original="{{ site.img }}/images/{{ post.image.thumb }}" alt="">
      <noscript><img src="{{ site.img }}/images/{{ post.image.thumb }}" alt=""></noscript>
    </a>
  </li>
{% endfor %}
</ul>
