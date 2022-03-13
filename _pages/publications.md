---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
For a full list of my publications, please visit <a href="https://scholar.google.com/citations?user=1S79G5AAAAAJ&hl=en">my Google Scholar profile</a>.
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-paper.html %}
{% endfor %}
