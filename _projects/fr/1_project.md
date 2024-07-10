---
page_id: project_1
layout: page
title: Holographie numérique
description: Améliorer la surveillance du plancton avec l'IA
img: assets/img/project1/holo.jpg
importance: 1
category: work
related_publications: false
---

---

> ## Informations
>
> ---
>
> - `Type de projet` : Thèse
> - `Rôle` : Doctorante
> - `Période` : 2020-2023
> - `Partenaires` : ISEA, IRD, IFREMER
> - `Thèmes de recherche` : détection d'objets, tracking, classification, segmentation d'instances, reconstruction d'images, modèles génératifs, imagerie 3D.

## Présentation

---

#### `Le plancton : une ressource vitale à surveiller`

L'eau, une ressource vitale, abrite une biodiversité exceptionnelle, dominée par le plancton qui représente plus de 98% de la biomasse marine. Le plancton est crucial pour la chaîne alimentaire et le climat, produisant plus de la moitié de l'oxygène terrestre et absorbant une grande partie du dioxyde de carbone. Cependant, son déclin depuis la seconde révolution industrielle menace la vie sur Terre, rendant l'étude de son abondance et de sa distribution cruciale pour la préservation des écosystèmes marins. Par ailleurs, certaines espèces de plancton produisent des toxines contaminant les ressources marines, posant des risques pour la santé humaine. Ainsi, surveiller régulièrement le plancton est essentiel pour garantir la sécurité alimentaire et la santé publique.

#### `Méthodes Traditionnelles et leurs Limites`

Les méthodes traditionnelles d'étude du plancton, utilisant des filets, des bouteilles de prélèvement ou des pompes, sont laborieuses et endommagent souvent les organismes fragiles. Ces techniques manuelles sont insuffisantes pour appréhender l'écosystème planctonique dans sa globalité, nécessitant des méthodes plus efficaces et automatisées.

Des instruments d'imagerie optique et holographique tels que SIPPER, ISIIS, IFCB et LISST-Holo2 ont été développés pour analyser le plancton in situ et en laboratoire. Ces dispositifs permettent d'étudier des particules de tailles variées, déployées sur diverses plateformes comme les ROVs, les mouillages fixes et les AUVs. Cependant, ces dispositifs sont généralement très coûteux, énergivores et ne peuvent pas être déployés à grande échelle. De plus, la quantité de données produites par ces systèmes est telle que seules des méthodes avancées de vision par ordinateur permettent de les traiter efficacement.

#### `Vers un système low-cost de surveillance`

Pour multiplier les zones d'étude, il est nécessaire de disposer d'instruments à la fois performants et bon marché. L'holographie numérique, nécessitant une source de lumière et une caméra, offre des instruments peu coûteux avec une grande profondeur de champ, permettant d'imager des objets microscopiques sans les endommager.
Le traitement des hologrammes est cependant complexe et exige des algorithmes itératifs, souvent difficiles à réaliser en temps réel sur des systèmes embarqués à faible consommation. Même si les méthodes d'apprentissage profond proposent des solutions pour la classification des hologrammes, leur intégration dans des systèmes in situ reste un défi en raison des contraintes de calcul et de stockage.

#### `Contributions de la Recherche`

Ce projet de recherche couvre la conception de l'instrument holographique, la création de nouveaux pipelines de traitement et de modèles de deep learning adaptés à l'holographie, répondant aux contraintes des utilisateurs finaux et favorisant l'évolution des dispositifs d'imagerie planctonique.

---

# Articles associés

<div class="publications">

{% bibliography -q @*[project=phd] %}

</div>
