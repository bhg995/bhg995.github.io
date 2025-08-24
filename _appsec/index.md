---
layout: default
title: Application Security
description: About app security
permalink: /appsec/
---

<button><a href="/">Main Page</a></button>
<button><a href="/linux">Linux Servers</a></button>
<button><a href="/confman">Application Security</a></button>

# {{ page.title }} & Vulnerabilities

These reports were done as an assigment for the course [Application hacking and vulnerabilities](https://terokarvinen.com/sovellusten-hakkerointi/)

Sovellusten hakkerointi 2025 alkusyksy: [ICI012AS3A](https://opinto-opas.haaga-helia.fi/course/ICI012AS3A)-3002


{% for post in site.posts %}
{% if post.path contains '_posts/appsec/' %}
- [{{ post.title }}]({{ post.url }})- {{ post.date | date: "%B %d, %Y" }} 
{% endif %}
{% endfor %}
