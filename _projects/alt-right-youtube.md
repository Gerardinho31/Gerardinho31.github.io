---
layout: default
title: "Analyse des discours de l'alt-right sur YouTube : Hollywood comme cible de la 'guerre culturelle'"
description: "Analyse d’un corpus de 48 000 vidéos YouTube issues de chaînes conservatrices afin de cartographier les dynamiques discursives et d’engagement, notamment autour de la « guerre culturelle » et de la représentation d’Hollywood comme élite hostile."
image: "/assets/img/co-occurence_nuage_alt_right.png"
tools: "SQL, Python, Iramuteq"
date: 2026-02-20
---

# Analyse de l'alt-right sur Youtube

Ce projet analyse le rôle des chaînes YouTube conservatrices dans la structuration des discours politiques en ligne, en particulier autour des thématiques de polarisation et de « guerre culturelle ». À partir d’un corpus de grande ampleur (48 000 vidéos et près de 500 000 commentaires issus de 14 chaînes entre 2014 et 2024), l’étude mobilise une base de données DuckDB enrichie (transcriptions, embeddings, scores de sentiment/toxicité). L’objectif est de comprendre comment ces acteurs construisent des communautés et des récits politiques, notamment en mobilisant Hollywood comme symbole d’une élite progressiste perçue comme hostile. L’analyse s’inscrit dans une approche combinant sciences sociales et data science, en s’appuyant sur des méthodes descriptives, textuelles et quantitatives. Elle met en évidence le rôle central de l’hostilité et des griefs partagés dans la fidélisation des audiences, ainsi que les stratégies discursives inspirées des codes des influenceurs. Le projet propose ainsi une cartographie structurée de cet écosystème médiatique, en identifiant ses principaux acteurs, ses thématiques dominantes et ses dynamiques d’engagement.

## Visualisation Lexicométrique

![Nuage de mots]({{ "/assets/img/co-occurence_nuage_alt_right.png" | relative_url }})
![Classification hiérarchique ascendante]({{ "/assets/img/Classification_hierarchique_ascendante_alt_right.png" | relative_url }})

## Technologies utilisées
- **SQL** pour la récupération des données sur Youtube et leur gestion dans différentes tables
- **IRaMuTeQ** pour l'analyse lexicométrique des corpus de textes et les visualisations graphiques (AFC, classification ascendante hierarchique)
- **Python** pour le nettoyage et l'analyse des données (extraction des entités nommées, visualisations graphiques)

*Le code source complet de ce projet est disponible dans le dossier `Analyse de l'alt-right sur Youtube` de mon répertoire.*

## 📈 Résultats et Apports
*(À compléter : décrivez ici vos principales conclusions sur la guerre culturelle et Hollywood)*
