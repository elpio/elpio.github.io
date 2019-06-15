---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  En cours de mise à jour. En attendant, vous pouvez trouver mes article sur mon <u><a href="{{author.googlescholar}}">profil Google Scholar</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
