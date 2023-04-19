---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=6cdYPtMAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</u>

{% include base_path %}

(In Review / Submitted)
---
  {% for post in site.submitted reversed %}
    {% include archive-single.html %}
  {% endfor %}

(Published)
---
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
