---
layout: project
title: Cushman & Wakefield
subtitle: Site de location et vente de locaux d'entreprise
category: En agence
tasks:
  - développement
  - cartographie
technologies:
  - ruby on rails
  - coffeescript
year_released: 2017
month_released: Février
date: 01/02/2017
website_url: https://immobilier.cushmanwakefield.fr/
image: assets/images/projects/cushman01.png
---

Cushman & Wakefield, agence immobilière spécialisée dans les locaux d'entreprise, avait besoin d'une nouvelle plateforme pour diffuser et gérer leurs annonces. Le projet s'est articulé entre différents acteurs :
- une société gérant les données et fournissant l'API permettant de les consulter
- une autre société, Studio HB (de laquelle j'étais partie prenante), pour réaliser le design de la plateforme, récupérer les données et les rendre accessibles.

Je me suis sur ce projet plus particulièrement chargée de l'une des fonctionnalités coeur du projet : l'**affichage des annonces**. Il s'agissait ici de lister, trier et filtrer les annonces de façon dynamique en vignettes et sur une carte.  

Il est aussi possible de dessiner une zone de sélection sur la carte, afficher les transports et points d'intérêts, afficher des info-bulles... Bref, une belle architecture javascript dynamique et une manipulation en profondeur de l'API de google maps.
