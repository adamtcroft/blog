---
layout: home
title: Welcome to My Blog
---

# Welcome to My Blog!

Hello and welcome to my personal blog. This site is where I share my thoughts, projects, and experiences.

## Recent Posts

Check out my latest articles below or browse the [archives](/archives) for more content.

{% for post in site.posts limit:5 %}
  <div class="post-preview">
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
    <p>{{ post.excerpt }}</p>
    <a href="{{ post.url | relative_url }}">Read more...</a>
  </div>
{% endfor %}

## About Me

I'm passionate about technology, writing, and sharing knowledge. Feel free to [contact me](/contact) if you have any questions or comments!

