# CustomerChurnPrediction
Un modèle de base pour prédire le désabonnement de la clientèle

La fidélisation client est un enjeu majeur pour toute entreprise ayant un modèle basé sur des abonnements ou des interactions récurrentes. Le churn (taux d’attrition) représente le pourcentage de clients quittant une entreprise sur une période donnée. Dans le cadre de la Française des Jeux (FDJ), qui propose des services de jeux en ligne et de paris sportifs, comprendre les facteurs du churn est crucial pour optimiser l'engagement et prévenir la perte de clients.

Ce document propose une analyse détaillée du churn client, en identifiant les variables influentes et en suggérant des actions préventives.

Je vais construire un modèle de base pour prédire la perte de clients en utilisant le [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn). Je vais utiliser des algorithmes de classification pour modéliser les clients qui sont partis, en utilisant des outils Python tels que pandas pour la manipulation de données et matplotlib pour les visualisations.

## étapes impliquées pour prédire la perte de clients
- Importation des bibliothèques
- Chargement du jeu de données
- Analyse exploratoire des données
- Valeurs aberrantes par la méthode IQR
- Nettoyage et transformation des données
    - Encodage one-hot
    - Rangement des colonnes
    - Scaling des fonctionnalités
    - Sélection des fonctionnalités
- Prédiction en utilisant la régression logistique
- Prédiction en utilisant le classificateur SVM
- Prédiction en utilisant le classificateur d'arbres de décision
- Prédiction en utilisant le classificateur KNN
