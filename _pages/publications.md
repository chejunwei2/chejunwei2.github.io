---
layout: archive
title: "Publications"
permalink: https://chejunwei2.github.io/publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{[site.author.googlescholar](https://scholar.google.com.hk/citations?user=z6DY2D0AAAAJ&hl=zh-CN)}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
