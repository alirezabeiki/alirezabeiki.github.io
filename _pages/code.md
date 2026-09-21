---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
---

{% include base_path %}

Placeholder content: software, scripts, and repositories will be listed here.
{: .notice}

{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}

## Featured repositories

A manually curated list can go here — for example:

- [Project One](https://github.com/academicpages) — short one-line description.
- [Project Two](https://github.com/academicpages) — short one-line description.
