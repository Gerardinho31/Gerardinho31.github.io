---
layout: default
title: "Humanités numériques & histoire de l'art : reconnaissance automatisée des œuvres de la famille Pedoya dans les églises du Midi toulousain"
description: "Développement d'un système de reconnaissance automatisée des médaillons de plafond d'églises du Midi toulousain attribués aux peintres piémontais Pedoya (XIXe siècle), combinant détection géométrique (Transformée de Hough) et classification par deep learning (ResNet-50) sur un corpus de 3 759 images — aboutissant à un outil capable d'analyser des photographies panoramiques d'édifices religieux."

image: "/assets/img/Base de données.png"
tools: "Python, PyTorch, ResNet-50"
date: 2025-11-23
---

# Projet Machine learning Pedoya
Ce projet applique les méthodes de l'intelligence artificielle à un défi d'histoire de l'art : identifier automatiquement les médaillons de plafond réalisés par les peintres piémontais Pedoya dans les édifices religieux du Midi toulousain au XIXe siècle. Mené en trois phases itératives, le travail combine transfer learning, vision par ordinateur classique (Transformée de Hough pour la détection des formes circulaires) et classification neuronale profonde (ResNet-50), sur un corpus "Gold Standard" de 3 759 images constituées et validées par expertise historique. Le système doit relever un double défi : distinguer les médaillons narratifs du décor architectural environnant, puis différencier le style Pedoya de celui de peintres contemporains (Ceroni, Bosia…). L'aboutissement du projet est un outil terrain baptisé Smart Scanner, capable d'analyser des photographies panoramiques d'église en un pipeline automatisé — de la photo brute à l'attribution stylistique. Ce travail illustre le potentiel des humanités numériques pour la recherche patrimoniale.

## Architecture des Données

![Schéma de données]({{ "/assets/img/Base de données.png" | relative_url }})

## Outils et Méthodes
- **PyTorch** pour la modélisation en Deep Learning
- **Computer Vision** : prétraitement d'images et data augmentation
- **Evaluation** : précision, rappel, et matrice de confusion

*Le rapport complet "Rapport_Synthese_ML_Pedoya--Version finale.pdf" se trouve dans le projet original.*
