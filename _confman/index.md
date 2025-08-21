---
layout: default
title: Configuration Management
description: IaaS, Saltproject, Daemons and other fun stuff
permalink: /confman/
---

<a href="/">Main Page</a>

# {{ page.title }}

These reports were done as an assigment for the course [Configuration Management Systems](https://terokarvinen.com/2024/palvelinten-hallinta-2024p2/)

Configuration Management Systems course 2024 autumn: Palvelinten hallinta ICI001AS3A-3010

{% for post in site.posts %}
{% if post.path contains '_posts/confman/' %}
- [`{{ post.title }}`]({{ post.url }})- {{ post.date | date: "%B %d, %Y" }} 
{% endif %}
{% endfor %}