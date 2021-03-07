---
layout: default
title:  "Outils numérique du gouvernement du Canada (ébauche)"
lang: fr
altLang: en
altLangPage: overview
---
{% assign dataVariable = site.playbookData[page.lang] %}
{% assign dataSource = site.data[dataVariable] %}
<section class="dpgn-section-overview">

## Aperçu (ébauche)

Fournit des outils pour aider le gouvernement du Canada dans la transformation numérique et la prestation de services accrue, y compris en devenant plus agile, ouvert et axé sur l'utilisateur. Inclut des vues spécifiques aux tâches et des fonctions interactives pour faciliter la recherche des conseils pertinents et pour les appliquer au travail quotidien.
{: .dpgn-overview-start}

Les outils numériqueGC est également l’occasion d’expérimenter avec de nouvelles approches tout en réutilisant le plus que possible et en fournissant des composants réutilisables pour que les autres puissent les utiliser (voir [Approches expérimentales et composants réutilisables]({{ site.baseurl }}/docs/fr/approches-experimentales-composants-reutilisables.html)).
{: .dpgn-overview-start}

{% include views-vues.html lang=page.lang %}

<section class="dpgn-overview-end">

### À propos des outils numériqueGC

<section class="dpgn-overview-end">
  
#### Améliorer les services gouvernementaux à l’ère numérique

Notre objectif est de fournir aux Canadiens des services publics faciles à utiliser et dignes de confiance. Ces outils numériqueGC, ainsi que les normes numériques du gouvernement du Canada sur lequels ce guide est fondé, constituent le fondement du virage du gouvernement du Canada vers une plus grande souplesse, une plus grande ouverture et une plus grande attention sur l’utilisateur. 

Les outils numérique du gouvernement du Canada est disponible sous la [licence du gouvernement ouvert du Canada](https://ouvert.canada.ca/fr/licence-du-gouvernement-ouvert-canada), sauf indication contraire.

</section>

<section class="dpgn-overview-end">
 
#### Approche de mise en œuvre

L'approche du développement et de la diffusion des outils numériqueGC sera similaire à celle de la Boîte à outils de l'expérience Web et de HTML5, où les outils numériqueGC évolue constamment sur GitHub et où des clichés stables de ce travail sont publiés sous forme de versions officielles sur Canada.ca. Cela permet au guide numérique d'être agile et de s'améliorer constamment sur GitHub tout en offrant une version stable à travers Canada.ca sur laquelle on peut compter pour obtenir des conseils.

Les réactions de la communauté et les contributions aux outils numériqueGC sont encouragées, les réviseurs désignés pour chaque partie du guide numérique étant chargés d'examiner, de répondre, de demander des changements (au besoin) et d'approuver ou de refuser les commentaires et les contributions. Les examinateurs principaux sont des personnes provenant des secteurs de politiques connexes et des domaines d'expertise, et sont également chargés de contribuer au contenu et de s'engager auprès de leurs communautés respectives.

Pour s'assurer que les outils numériqueGC soit aussi facile à utiliser que possible, les contributeurs / réviseurs travailleront avec leurs communautés respectives pour déterminer comment rendre les outils numériqueGC plus applicable à leur travail quotidien, y compris pour quelles tâches / scénarios personnalisés les [vues des outils numériqueGC]({{ site.baseurl }}/docs/{{ page.lang }}/vues{{ site.RenderedFileExtension }}) doivent être fournies.

</section>
</section>
