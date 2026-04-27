# ecommerce-sales-analysis
Analyse exploratoire de données e-commerce — tendances des ventes, segmentation client et tableau de bord KPI

# Contexte du projet
Dans un environnement e-commerce, les entreprises collectent une grande quantité de données sur: les clients, leurs comportements de navigation, leurs achats, leur satisfaction
L’objectif de ce projet est d’exploiter ces données pour mieux comprendre le comportement des clients et identifier des leviers d’optimisation commerciale et opérationnelle.

# Présentation du dataset
Ce jeu de données complet contient 5 000 transactions e-commerce provenant d’une plateforme turque de vente en ligne, couvrant la période de janvier 2023 à mars 2024. L’ensemble de données fournit des informations détaillées sur la démographie des clients, le comportement d’achat, les préférences produits et les indicateurs d’engagement.
 **Source :** [E-Commerce Customer Behavior and Sales Dataset](https://www.kaggle.com/)

# Quelques Questions explorées :
- Quel est le profil de la clientèle (segmentation RFM) ?
- Quelles sont les tendances de ventes mensuelles et saisonnières ?
- Quelles catégories de produits génèrent le plus de chiffre d'affaires ?
- Quels marchés ou régions sont les plus performants ?
- Le temps passé sur le site influence-t-il les achats ?
- Les délais de livraison influencent-ils la satisfaction ?
- Les promotions augmentent-elles les ventes ?
- Les clients fidèles dépensent-ils plus ?

# Outils & Technologies utilisées
Python — pandas, numpy
Matplotlib / Seaborn
Notebook — Jupyter
scikit-learn

# Principaux résultats

  # Profil des clients
* La clientèle est majoritairement composée de clients récurrents (59,8 %), contre 40,2 % de nouveaux clients
* Le niveau de dépense est quasiment similaire entre les deux groupes (985 € pour les clients récurrents contre 978 € pour les nouveaux), ce qui montre que la fidélisation n’entraîne pas encore une augmentation significative du panier moyen
* Les clients âgés de 30 à 40 ans représentent le segment le plus contributeur en chiffre d’affaires, suivis par la tranche des 40 à 50 ans
  # Comportement de navigation
* Le mobile est le principal canal d’achat, représentant près de 56 % des transactions, devant le desktop (34 %) et la tablette (10 %)
* La durée de session semble avoir un impact limité sur le montant des achats : les sessions courtes (0 à 15 minutes) génèrent un panier moyen proche de celui des sessions intermédiaires
* En revanche, les sessions plus longues (45 à 60 minutes) sont associées à des montants d’achat plus faibles, ce qui peut refléter une hésitation ou des difficultés dans le parcours utilisateur
  # Satisfaction client
* Le lien entre le délai de livraison et la note attribuée reste modéré, mais des délais plus longs ont tendance à dégrader la satisfaction
* Le modèle de classification (Random Forest) permet de prédire les clients satisfaits avec une précision globale de 70 %
* Le modèle identifie bien les clients satisfaits, mais reste moins performant pour détecter les clients insatisfaits
  # Produits & revenus
* L’analyse porte sur 5 000 transactions, pour un chiffre d’affaires total d’environ 4,9 millions d’euros sur 15 mois
* Le panier moyen s’élève à 983 €, avec une forte variabilité selon les clients
* Les catégories Electronics, Food et Toys figurent parmi les plus présentes dans les ventes

- 
# Valeur business
Les analyses réalisées permettent de dégager plusieurs leviers concrets pour améliorer la performance de la plateforme :
* Les clients âgés de 30 à 50 ans concentrent une part importante du chiffre d’affaires. Ce segment mérite donc une attention particulière, notamment à travers des campagnes marketing ciblées et des offres personnalisées.
* Le mobile représente aujourd’hui le principal canal d’achat, avec plus de la moitié des transactions. L’optimisation de l’expérience mobile (navigation, rapidité, tunnel de paiement) constitue donc un enjeu prioritaire pour maximiser les conversions.
* Les clients récurrents ne dépensent pas davantage que les nouveaux clients. Cela suggère un potentiel d’amélioration du côté de la fidélisation, par exemple via des programmes de récompense ou des avantages exclusifs.
* Les sessions longues sont souvent associées à des paniers plus faibles. Ce comportement peut traduire une hésitation ou des difficultés dans le parcours d’achat. Il serait pertinent de simplifier la navigation ou de mieux guider l’utilisateur (recommandations, relances, etc.)
* Enfin, le modèle prédictif permet d’identifier efficacement les clients satisfaits, mais reste limité pour détecter les clients insatisfaits. Un modèle plus équilibré permettrait d’anticiper les risques et de mettre en place des actions préventives.


# Structure du projet
Data cleaning
Exploratory Data Analysis (EDA)
Data visualization
Machine learning model




