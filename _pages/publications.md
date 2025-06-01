---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
author.googlescholar:true
---


You can also find my full publication list on my [Google Scholar](https://scholar.google.com/citations?user=WKfT0REAAAAJ&hl=en)


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
