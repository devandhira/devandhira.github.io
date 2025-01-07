---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


Preprints
=====
* A Proof of Ramanujan's Classic π Formula ([arXiv Link](https://arxiv.org/abs/2411.15803))
  * Thang Pang Ern, Devandhira Wijaya Wangsa
