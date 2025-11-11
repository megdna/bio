---
layout: page
permalink: /posts
title: Posts
---
<div class="notice">Subscribe to <a href="{{ site.url }}/feed" target="_blank" data-goatcounter-click="feed">feed</a> for updates on our projects. View all in <a href="{{ site.url }}/archive">archive</a>.</div>

{% for post in site.posts %}
<article>
  {% if post.image %}<img alt="{{ post.alt }}" src="{{ post.image | absolute_url }}">{% endif %}
  <p><b><a href="{{ post.url | absolute_url }}">{{ post.title }}</a></b></p>
  <p>{{ post.description }}</p>
  <p><cite>{{post.date | date: '%b %d, %Y'}} - {% capture words %}{{ post.content | number_of_words }}{% endcapture %}{% unless words contains "-" %}{{ words | plus: 250 | divided_by: 250 | append: " minute read" }}{% endunless %}</cite></p>
</article>
{% endfor %}