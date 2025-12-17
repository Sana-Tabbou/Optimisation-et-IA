# Détection de fraudes sur les transactions bancaires

## Contexte du projet
Ce projet s’inscrit dans le cadre du mini-projet du module **Intelligence Artificielle et Optimisation**.  
L’objectif est de concevoir une application basée sur l’Intelligence Artificielle permettant de détecter des fraudes dans des transactions bancaires.

La détection de fraude est un problème complexe en raison du **déséquilibre important des classes**, les transactions frauduleuses étant très minoritaires par rapport aux transactions normales.

---

## Objectifs
- Exploiter un jeu de données réel de transactions bancaires
- Analyser et traiter un jeu de données fortement déséquilibré
- Mettre en œuvre des modèles de Machine Learning et de Deep Learning
- Utiliser des métriques d’évaluation adaptées à la détection de fraudes
- Analyser les résultats obtenus et proposer des améliorations

---

## Jeu de données
Le jeu de données utilisé est issu de Kaggle :

Credit Card Fraud Detection  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Description
- Transactions par carte bancaire
- Données anonymisées (variables V1 à V28 issues d’une Analyse en Composantes Principales)
- Variables principales :
  - `Time` : temps écoulé depuis la première transaction
  - `Amount` : montant de la transaction
  - `Class` : 0 = transaction normale, 1 = fraude

 Le fichier `creditcard.csv` dépasse 100 Mo et ne peut pas être stocké sur GitHub.  
Il doit être téléchargé manuellement depuis Kaggle et placé dans le dossier `data/`.

---