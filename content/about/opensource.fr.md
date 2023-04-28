---
title: Open source
linkTitle: Open source
description: OSRD et l'open source
weight: 200
---

L’open source est une **pratique de développement logiciel** dans laquelle le code source[^code-source] du logiciel est&nbsp;:
 - Généralement développé de manière ouverte et collaborative par des acteurs variés&nbsp;;
 - Accessible et gratuitement utilisable par tous&nbsp;;
 - Tout le monde est libre de proposer un changement ou créer un logiciel dérivé&nbsp;;
 - Redistribuable par tous.

En pratique, l'open source est à la fois un **cadre légal** pour le travail collaboratif et un **ensemble de pratiques**.

[^code-source]: Le code source est un ensemble de documents texte qui définit comment fonctionne une application. C'est le produit du travail de développeurs logiciels.

## Application à OSRD

Dans le contexte d'OSRD, ce modèle a de **multiples avantages**&nbsp;:
 - Les algorithmes et le savoir-faire développé est ouvert à tous.
 - Les coûts de développement et résultats sont mutualisés entre les différents acteurs.
 - Il permet de faciliter l'interopérabilité entre systèmes d'information en facilitant la standardisation et l'uniformisation.
 - Il permet de catalyser la collaboration d'acteurs aux objectifs communs.
 - Il permet à chaque acteur d'adapter librement le logiciel à ses besoins.
 - Il permet aux organismes de recherche publics de contribuer directement et de profiter du projet.
 - Il permet aux acteurs publics de répondre à leurs impératifs de transparence.

L'utilisation d'un projet open source comme catalyseur de collaboration industrielle a de nombreux antécédents&nbsp;:
 - **Blender** est un outil de modélisation, rendu, et animation 3D très complet, qui est récemment devenu une [plateforme de collaboration industrielle](https://fund.blender.org/) majeure pour l'industrie audiovisuelle.
 - **Linux** est un système d’exploitation (OS en anglais, alternative à Windows) qui équipe Google, Microsoft, Amazon, Apple, la plupart des sites internet, plateformes cloud, téléphones, routeurs, et bien plus. Toutes ces entreprises contribuent et se utilisent énormément Linux.
 - **Android** est une base commune (issue de Linux) pour la majorité des téléphones vendus. Les fabriquants contribuent régulièrement à Android.
 - **PostgreSQL**, **MySQL**, **SQLite** et d'autres bases de donnée open source dominent collectivement ce marché. Un acteur aux besoins inédits peut contribuer à un outil open source plutôt qu'en créer un nouveau.
 - À la fois **Firefox** et **Chrome** sont open source.
 - **WordPress** est le CMS (content management system) au coeur de 43&nbsp;% des sites internet en activité. Un grand nombre d'entreprises contribuent et produisent des extensions pour WordPress.
 - **Odoo** est un ERP (enterprise resource planning - planification des ressources d'entreprise) modulaire très complet dont la communauté est similaire à celle de Wordpress.

**Toutes ces projets ont en commun d'être essentiel à la bonne marche d'un grand nombre d'entreprises sans pour autant être un produit que vend l'entreprise**.

Ainsi, ces entreprises décident de collaborer avec leurs pairs ou leurs concurrents à des outils communs afin de faciliter les échanges et d'améliorer la qualité de leur service.

## Fonctionnement pratique

{{% alert color="info" %}}
Ce mode de fonctionnement n'est pas spécifique à l'open source : beaucoup d'entreprises adoptent un fonctionnement identique, à la différence près qu'il est maintenu privé.
{{% /alert %}}

En pratique, les logiciels libre sont développés via une [forge](https://github.com/DGEXSolutions/osrd)[^forge]. Cette forge donne accès au code source, un outil de gestion des bugs / tâches et un outil servant à intégrer des changements dans le code.
Tout le monde peut proposer un changement, signaler un bug ou proposer une tâche.

[^forge]: En informatique, une forge est un système de gestion et de maintenance collaborative de texte (de la documentation, des données alimentées collaborativement, des textes de loi1, etc.). Ces outils ont été créés pour les besoins du développement, qui reste aujourd'hui l'usage largement majoritaire. Voir [définition sur Wikipédia](https://fr.wikipedia.org/wiki/Forge_(informatique))

Les propositions de changement sont soumises à une **revue par les pairs**, semblable à celles de la communauté scientifique.
Les individus en charge de la revue des propositions (les reviewers/réviseurs) sont ceux qui sont les plus familiers avec les composants affectés par le changement.

Les changements sont intégrés par des mainteneurs sur la base du **consensus** entre réviseurs.
Les mainteneurs sont responsables de la cohérence technique du projet et obtiennent ce rôle par consensus.
L'intégration des changement n'est motivée que par leur viabilité technique&nbsp;: l'objectif des mainteneurs et réviseurs est de **s'assurer que le projet reste de bonne qualité**.
