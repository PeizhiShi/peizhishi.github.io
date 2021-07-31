---
layout: default
title: Software
permalink: software.html
---

## Software

Here are some tools I wrote. If they are useful to you, please consider citing our relevant paper(s). Some functionalities of the tools are written by using existing libraries, open source codes, or implemented according to existing academic papers. I would like to thank the developers or authors for their great efforts. 

Please do **NOT** utilise the codes for military, nuclear, missile, animal slaughter, meat production, weapon creation, weaponry end uses or conduct any other activities involving the codes where human/animal life or property may be at stake.

{% for post in site.softwares reversed %} 
{% assign link_visible = post.link_visible %}
{% if post.github %}
{% include achieve_software_title.html %}
{% endif %}
{% endfor %}

## Others

In addition to the aforementioned tools, I also have a number of passion projects which are related to machine learning in computer vision and formal verfication.

{% for post in site.softwares reversed %} 
{% assign link_visible = post.link_visible %}
{% if post.github == nil %}
{% include achieve_software_title.html %}
{% endif %}
{% endfor %}







