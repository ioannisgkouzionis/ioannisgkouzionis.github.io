---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Selected journal articles and conference papers. The full research record is available on [Google Scholar]({{ site.author.googlescholar }}) and [ORCID]({{ site.author.orcid }}).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
