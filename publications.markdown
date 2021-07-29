---
layout: default
title: Publications
permalink: publications.html
---

## Publications


{% for post in site.projects reversed %} 
{% assign link_visible = post.link_visible %}
{% assign display_authors = true %}
{% if post.paper_published %}
{% include achieve_project_title.html %}
{% endif %}
{% endfor %}







