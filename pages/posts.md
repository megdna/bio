---
layout: post
permalink: /posts
title: Posts
---
<div class="notice">Subscribe to <a href="{{ site.baseurl }}/feed" target="_blank" data-goatcounter-click="feed" data-umami-event="feed">feed</a> for updates on our projects.</div>

{% for post in site.posts %}
<section>
  {% if post.image %}<img alt="{{ post.alt }}" src="{{ post.image | prepend: site.baseurl | prepend: site.url }}">{% endif %}
  <h4><a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a></h4>
  <p>{{ post.description }}</p>
  <cite>{{post.date | date: '%b %d, %Y'}} - {% capture words %}{{ post.content | number_of_words }}{% endcapture %}{% unless words contains "-" %}{{ words | plus: 250 | divided_by: 250 | append: " minute read" }}{% endunless %}</cite>
</section>
{% endfor %}