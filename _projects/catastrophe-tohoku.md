---
layout: default
title: "La triple catastrophe du Tôhoku"
description: "Analyse du traitement médiatique de la triple catastrophe du Tôhoku dans la presse française entre 2011 et 2021."
image: "/assets/img/tohoku-analyse.png"
tools: "Python, NLP, Topic modeling, analyse lexicométrique"
date: 2025-01-18
---

# La triple catastrophe du Tôhoku

Ce projet porte sur le traitement médiatique de la triple catastrophe japonaise du 11 mars 2011 — séisme, tsunami et accident nucléaire de Fukushima Daiichi — dans la presse nationale française. En m'appuyant sur un corpus constitué via Europresse (du 11 mars 2011 au 30 novembre 2023), j'ai distingué trois périodes d'analyse : un corpus général, un corpus « à chaud » et un corpus « post-événements », afin d'étudier l'évolution de la couverture dans le temps. L'hypothèse centrale est que les médias français ont surreprésenté la dimension nucléaire au détriment des catastrophes naturelles — tsunami et séisme — pourtant responsables de l'écrasante majorité des victimes. Cette approche s'appuie sur des travaux en sociologie des médias (Joffe, 2003 ; Moirand, 2007) qui montrent comment les « signaux de risque » véhiculés par les images et les symboles amplifient la perception du danger dans l'opinion publique. Pour tester cette hypothèse, j'ai mobilisé des méthodes de Natural Language Processing (NLP) afin d'analyser quantitativement les thématiques dominantes dans le corpus de presse. Ce travail croise ainsi histoire des médias, sociologie du risque et traitement automatique du langage, illustrant comment un événement complexe peut être réduit à un seul de ses aspects par le prisme médiatique.

## Visualisation

![Analyse Tôhoku]({{ "/assets/img/tohoku-analyse.png" | relative_url }})
![Analyse Tôhoku]({{ "/assets/img/Repartition_chronologiques_quotidiens_Tohoku.png" | relative_url }})

## Technologies utilisées
- **Python** Scraping de corpus d'articles via Europresse, Traitement du langage naturel (NLP), Topic Modeling
- **IRaMuTeQ** Analyse lexicométrique

*Le code source complet de ce projet est disponible dans le dossier `La triple catastrophe du Tôhoku` de mon répertoire.*
