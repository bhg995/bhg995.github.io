---
layout: default
title: Getting around with Linux
description: Debian 12
permalink: /linux/
---

<button><a href="/">Main Page</a></button>
<button><a href="/confman">Configuration Management</a></button>
<button><a href="/appsec">Application Security</a></button>

# Linux Machine and Servers

These reports were done as an assigment for the course [Linux Servers](https://terokarvinen.com/2024/linux-palvelimet-2024p1-alkusyksy-ici003as2a-3010/).

Linux Palvelimet 2024 alkusyksy: [ICI003AS2A](https://opinto-opas.haaga-helia.fi/course/ICI003AS2AE)-3010

{% for post in site.posts %}
  {% if post.path contains '_posts/linux/' %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
  {% endif %}
{% endfor %}
