---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

{% if author.googlescholar %}
  Mes publications peuvent également être trouvées sur mon <u><a href="{{author.googlescholar}}">profil Google Scholar</a>.</u>
{% endif %}

Liste des publications sur HAL:

 <details open>
  <summary>Classées par date</summary>
  <p> <IFRAME width="700" height="500" src="https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?idHal=elsa-piollet&CB_auteur=oui&CB_titre=oui&CB_article=oui&langue=Francais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/VisuCondenseSsCadre.css" FRAMEBORDER="0" scrolling="auto" ></IFRAME></p>
</details> 

 <details>
  <summary>Classées par type</summary>
  <p> <IFRAME width="700" height="500" src="https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?idHal=elsa-piollet&CB_auteur=oui&CB_titre=oui&CB_article=oui&langue=Francais&tri_exp=typdoc&tri_exp2=date_publi&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/VisuCondenseSsCadre.css" FRAMEBORDER="0" scrolling="auto" ></IFRAME></p>
</details> 

