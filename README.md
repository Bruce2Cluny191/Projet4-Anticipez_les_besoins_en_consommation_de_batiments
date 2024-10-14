# Anticipez les besoins en consommation de bâtiments

<img src="https://user.oc-static.com/upload/2019/02/24/15510245026714_Seattle_logo_landscape_blue-black.png" />

## Contexte
La ville de Seattle vise à devenir neutre en émissions de carbone d'ici 2050. Pour atteindre cet objectif, l'équipe se concentre sur la consommation et les émissions des bâtiments non résidentiels. Des relevés ont été effectués en 2016, mais leur coût élevé incite à prédire les émissions de CO2 et la consommation d'énergie des bâtiments non mesurés, en utilisant les données structurelles des bâtiments.

## Objectif du Projet
- Prédire les émissions de CO2 et la consommation totale d'énergie des bâtiments non résidentiels.
- Évaluer l'intérêt de l'ENERGY STAR Score pour la prédiction des émissions.

## Étapes du Projet

### 1. Analyse Exploratoire
- Nettoyage des données pour éliminer les observations aberrantes et les outliers.
- Sélection des variables pertinentes : type de bâtiment, usage principal, nombre de bâtiments, nombre d'étages, surface totale, âge, et éventuellement l'ENERGY STAR Score.

### 2. Modélisation
- Test de différents modèles de prédiction : KNeighbors, Ridge, SVM, kRR, RandomForest, AdaBoost, GradientBoosting.
- Optimisation des modèles par validation croisée.
- Comparaison des performances avec et sans l'ENERGY STAR Score.

### 3. Résultats
- Modèle choisi pour la consommation d'énergie : Gradient Boosting avec `learning_rate = 0.2` et `n_estimators = 72`.
- Modèle choisi pour les émissions de CO2 : Gradient Boosting avec `learning_rate = 0.2` et `n_estimators = 50`.
- Conclusion sur l'inefficacité de l'ENERGY STAR Score dans ce contexte.

## Livrables
- [Pham-Van_Yann_1_notebook_exploratoire_052023.ipynb](https://github.com/Bruce2Cluny191/Projet4-Anticipez_les_besoins_en_consommation_de_batiments/blob/main/Pham-Van_Yann_1_notebook_exploratoire_052023.ipynb) : Un notebook d'analyse exploratoire.
- Deux notebooks de prédiction :
  - [Pham-Van_Yann_2_notebook_prediction_052023.ipynb](https://github.com/Bruce2Cluny191/Projet4-Anticipez_les_besoins_en_consommation_de_batiments/blob/main/Pham-Van_Yann_2_notebook_prediction_052023.ipynb) : émissions de CO2,
  - [Pham-Van_Yann_2_notebook_prediction_052023.ipynb](https://github.com/Bruce2Cluny191/Projet4-Anticipez_les_besoins_en_consommation_de_batiments/blob/main/Pham-Van_Yann_2_notebook_prediction_052023.ipynb) : consommation d'énergie.
- [Pham-Van_Yann_4_presentation_052023.pdf](https://github.com/Bruce2Cluny191/Projet4-Anticipez_les_besoins_en_consommation_de_batiments/blob/main/Pham-Van_Yann_4_presentation_052023.pdf) : Une présentation pour la soutenance.

## Contact
Pour toute question, veuillez me contacter sur [LinkedIn](https://www.linkedin.com/in/chasseur2valeurs/).
