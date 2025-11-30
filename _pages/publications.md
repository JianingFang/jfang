---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can find the full list of articles on <u><a href="https://scholar.google.com/citations?user=yLkTvcsAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
