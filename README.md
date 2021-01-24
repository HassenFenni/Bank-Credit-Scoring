# Projet : Scoring d'un client d'une banque en vue de l'octroi d'un crédit

Analyse, traitement et nettoyage des données de trois banques différentes pour créer un modèle d'apprentissage automatique qui permet de prédire si un client donné est capable de rembourser ou non son prêt bancaire et le déployer sur une plateforme web avec Python. 


## Methodology

1. Business understanding
- CRISP_DM
- IMB_MASTER_PLAN
2. Features Engineering
- Résoudre le problème des champs manquants
- Encoder les Variable qualitatives
3. Features Selection
- Remise à l'échelle des données numériques
- Resoudre le probleme des variables corrélées
- Test de pearson
- Cercle de corrélation
4. Dimensionality reduction
- ACP : Matrice variance-covariance / SVD(Singular Value Decomposition) / POD(Proper Orthogonal Oecomposition)
5. Segmentation
- KMeans / CAH / DBSCAN
6. Classification
- KNN / RandomForest / Decision Tree / Logistic Regression / Naive bayes / LightGBM / XGBoost / CATBoost / ADAboost
7. Dashboarding
- MVT(Model View Template)
  - BACK END (Pandas,Numpy,SKlearn)
  - FRONT END (Plotly,Dash,Flusk)
- Hébergement de sites WEB (Heroku ou PythonEveryWhere)

