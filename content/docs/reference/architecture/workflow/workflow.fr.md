---
title: "Flux des opérations"
linkTitle: "Flux des opérations"
weight: 43
description: Schéma des opérations de l'application
---

Les processus de l'application sont décrit dans le diagramme suivant. Les éléments en cercle sont des données et les rectangles sont des opérations. L'idée est de conserver ce graphe sous la forme d'un [DAG](https://fr.wikipedia.org/wiki/Graphe_orient%C3%A9) afin de pouvoir facilement réévaluer les éléments lorsque les données d'entrée changent.

![Workflow schema](../workflow.fr.svg)
