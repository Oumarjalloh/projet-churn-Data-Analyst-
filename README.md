# 📊 Analyse du Churn Client — Telco

## Contexte
Projet d'analyse data complet sur la prédiction du churn client
pour une entreprise de télécommunications.

## Objectifs
- Identifier les profils de clients à risque de départ
- Construire un modèle prédictif (Random Forest)
- Proposer des recommandations business actionnables

## Stack technique
Python · Pandas · Seaborn · Scikit-learn · Power BI · Git

## Résultats clés
- AUC-ROC : 0.84 (à adapter avec ton score réel)
- 26% de taux de churn global
- Les contrats mois/mois concentrent 3x plus de churners
- Les 6 premiers mois sont la période critique

## Structure du projet
- `data/` — Dataset source et fichiers nettoyés
- `notebooks/` — Notebooks Jupyter (nettoyage, EDA, modèle)
- `dashboard/` — Dashboard Power BI exporté en PDF

## Notebooks
| Notebook | Contenu |
|---|---|
| 01_nettoyage | Chargement et nettoyage des données |
| 02_exploration | Visualisations et insights EDA |
| 03_modele | Modèle Random Forest + évaluation |
