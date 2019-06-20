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

Une liste de mes publications sur HAL peut également être trouvée <a href="https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?auteur_exp=Elsa+Piollet&CB_auteur=oui&CB_titre=oui&CB_article=oui&CB_typdoc=oui&langue=Francais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/VisuCondenseSsCadre.css">ici</a>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
