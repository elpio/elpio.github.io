---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

{% if author.googlescholar %}
  En cours de mise à jour. En attendant, vous pouvez trouver mes article sur mon <u><a href="{{author.googlescholar}}">profil Google Scholar</a>.</u>
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
