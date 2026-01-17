---
layout: default
title: Home
---

# Welcome to my Personal Website!

This is a personal academic website for hosting my portfolio projects, talking about current topics, and keeping an up to date resume. You can see all my personal contact information on the far left, and in the event you do wish to contact me you will find email to be the simplest approach. The navigation toolbar can be found in the top right next to the toggle for light or dark mode themes; Here you will find everything that is relevant to this page.

## Featured Portfolio Projects

Check out my recent work on the [Portfolio page](/portfolio.html), including data analysis projects, machine learning models, and more.

## Recent Blog Posts
<ul>
{% for post in site.posts limit:3 %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span>{{ post.date | date: "%B %d, %Y" }}</span>
  </li>
{% endfor %}
</ul>

