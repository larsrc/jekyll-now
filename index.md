---
layout: post
title:  "Monachium"
ref: homepage
---

# Welcome to Monachium, the München Belegarth group!

You've found the site for the most fast, fun, and furious sport to invade München in centuries!
We are an group that meets for good natured fighting.
We hail from all countries from over the world and as well as all genders.

## Fighting dates

The 2017 fighting season was our best ever, but now winter has come.
Come back in 2018 for even more fighting - and the first-ever [European Belegarth event](http://battlevaria.monachium.org/)!
Join [our mailing list](https://groups.google.com/forum/#!forum/belegarth-munich/join) 
or [follow us on Facebook](http://fb.monachium.org/)!

## Posts

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
