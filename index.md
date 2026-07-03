---
layout: default
title: Corin Simcock
---

# Hi, I'm Corin

I'm a medical student at the University of Otago. This blog is just a place for me to write up projects that I find interesting.

## Posts

<ul class="posts">
{% for post in site.posts %}
  <li>
    <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
    <a href="{{ post.url | relative_url }}" class="no-underline"
	>{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
