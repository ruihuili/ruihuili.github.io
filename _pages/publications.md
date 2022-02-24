---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find my recent publications on [Google Scholar](https://scholar.google.com/citations?user=N_FtHksAAAAJ&hl=en).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
