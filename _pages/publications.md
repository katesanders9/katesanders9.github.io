---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

  This page includes a selection of my publications. You can find a full list on <u><a href="https://scholar.google.com/citations?user=VJFrfM0AAAAJ">my Google Scholar profile</a>.</u>

{% if author.googlescholar %}

{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html type="mylist" %}
{% endfor %}
