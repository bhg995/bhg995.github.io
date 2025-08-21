---
layout: default
title: Getting around with Linux
description: Debian 12
permalink: /linux/
---

<a href="/">Main Page</a>

# Linux Machine and Servers

These reports were done as an assigment for the course [Linux Servers](https://terokarvinen.com/2024/linux-palvelimet-2024p1-alkusyksy-ici003as2a-3010/).

Linux Palvelimet 2024 alkusyksy: ICI003AS2A-3010

{% for post in site.posts %}
  {% if post.path contains '_posts/linux/' %}
- [`{{ post.title }}`]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
  {% endif %}
{% endfor %}
