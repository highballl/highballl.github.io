---
title: "Categories"
layout: archive
permalink: /categories
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}


<!-- {% assign posts = site.categories.frontend %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %} -->