---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

A complete publication listing can be found on [Pubmed](https://www.ncbi.nlm.nih.gov/myncbi/robert.bowman.1/bibliography/public/).  See select publications below.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=VW5XhW0AAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
