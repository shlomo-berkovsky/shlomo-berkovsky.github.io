---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find the up-to-date list of publications on my [Google Scholar](https://scholar.google.com.au/citations?user=o98HOrMAAAAJ) page.


#{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
