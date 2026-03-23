---
layout: default
title: "Analyse des collaborations intersciences des unités de recherches toulousaines"
description: "Cartographie par analyse de réseaux des collaborations interdisciplinaires entre unités de recherche toulousaines (2019–2025), à partir de trois dispositifs de financement (MSHS-T, TIRIS, Défis-clés Occitanie), pour évaluer l'état des relations intersciences entre SHS et sciences exactes, expérimentales et du vivant au sein de la COMUE."
image: "/assets/img/Reseau_global_collaborations_interlaboratores.png"
tools: "R, Gephi, IRaMuTeQ"
date: 2026-03-19
---

# Analyse MSHS-T

Le travail s’appuie sur l’exploitation de plusieurs dispositifs de financement (MSHS-T, TIRIS, Défis-Clés) couvrant la période 2019–2025, considérés comme des indicateurs des dynamiques de collaboration. Une base de données relationnelle a été construite et nettoyée afin de modéliser les liens interlaboratoires à partir des participations aux projets, en veillant notamment à corriger les biais liés aux participations multiples.

L’analyse repose principalement sur des méthodes d’analyse de réseaux : calcul de mesures de centralité (degré, intermédiarité), détection de communautés, analyse de l’homophilie et calcul de l’indice E-I afin de qualifier le degré d’ouverture interdisciplinaire des laboratoires. Une attention particulière a été portée aux laboratoires SHS afin d’évaluer leur position dans ces réseaux.

Enfin, des visualisations de graphes (notamment via des algorithmes de spatialisation type ForceAtlas) ont été produites pour cartographier les structures relationnelles et rendre lisibles des interactions complexes. Ce travail aboutit à une cartographie fine de l’écosystème intersciences toulousain, mettant en évidence les logiques de structuration, les acteurs clés et les dynamiques de collaboration.

## Aperçu Visuel

![Réseau MSHS-T]({{ "/assets/img/Reseau_global_collaborations_interlaboratores.png" | relative_url }})

## Technologies utilisées
- **R** pour le traitement des données et l'analyse des réseaux
- **Gephi** pour les visualisation graphiques
- **IRaMuTeQ** pour l'analyse léximotrique

*Le code source complet et les rapports de ce projet sont disponibles dans le dossier `Analyse MSHS-T` de mon répertoire.*

## 📈 Résultats et Apports
*(À compléter : décrivez ici vos conclusions sur les collaborations intersciences à Toulouse)*
