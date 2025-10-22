# Data Scientist Junior

#### Compétences techniques : Python, SQL, Machine Learning, Statistiques

🌏 Curieux et méthodique, j'aime relever les défis posés par des problématiques métiers variées.

👉 Mon [CV]() et mon [profil LinkedIn](https://www.linkedin.com/in/théojean/)

## Formation
- Master en Mathématiques Appliquées & Statistiques | Université Clermont-Auvergne, FRANCE (_2022-2024_)
- Licence en Mathématiques & Informatique | Université de Pau et des Pays de l'Adour, FRANCE (_2020-2022_)
- DUT en Statistique et Informatique Décisionnelle (STID) | IUT de Pau, FRANCE (_2018-2020_)

## Expériences Professionnelles

**Data Scientist @ Caisse d'Épargne Auvergne Limousin, Alternance (sept 2023 - sept 2024)**
- Mise en place d'un projet de machine learning visant à prédire la souscription à l'assurance habitation par les clients.
- Développement de tableaux de bord dynamiques sur Excel pour le suivi et l'analyse des tendances saisonnières et de la performance des activités promotionnelles.

**Data Analyst @ TotalEnergies, Stage (avr 2023 - août 2023)**
- Analyse statistique de l'évolution des courbes de déclin de production pétrolière avec Python.
- Intégration de nouveaux indicateurs dans Power BI pour le suivi de la performance.

**Data Quality Manager @ TotalEnergies, Stage (avr 2020 - juil 2020)**
- Développement d'un outil de contrôle de la qualité des données avec Power BI.
- Implémentation de macros Excel pour l'automatisation.

## Projets
Voici mon premier projet de machine learning réalisé sur mon temps libre.
&nbsp;
### Prédiction de l'attrition bancaire
---------

Développement d'un modèle de détection du risque d'attrition adapté au secteur bancaire. L'analyse et la construction du modèle ont été réalisées dans un notebook Jupyter, permettant un suivi détaillé de l'avancement. Par la suite, j'ai créé un tableau de bord interactif avec Streamlit pour visualiser les résultats par client, améliorant ainsi le suivi des risques d'attrition.

Nom du dépôt : ML_Project_BankChurners

*Classification binaire / Métrique f1-score / Boosting / POO*

![Dashboard_picture](/asset/img/Dashboard.png)
![Dashboard_picture](/asset/img/Dashboard2.png)
Vous pouvez retrouver le tableau de bord [ici](https://bankchurners-dashboard.streamlit.app).

**Données**

Un jeu de données de plus de 10 000 clients bancaires, incluant leurs caractéristiques personnelles et comportementales, avec pour variable cible le fait que le client reste fidèle ou parte à la concurrence.

**Approche**

- Analyse exploratoire pour découvrir le comportement des variables selon différents critères.
- Sélection des variables pertinentes en combinant les variables importantes de plusieurs modèles de classification.
- Développement et optimisation de deux modèles de boosting : XGBoost et GradientBoosting.
- Analyse des erreurs de prédiction.

**Résultats**

- Sélection du modèle XGBoost pour sa rapidité et sa robustesse.
- Performance très équilibrée, avec un F1-score de 91%.