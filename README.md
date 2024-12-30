# Projet_Consommation_Electricite_Batiments

Pendant ce projet, mon rôle était de prédire les émissions de CO2 et la consommation totale d’énergie de certains bâtiments de la ville de Seattle aux Etats-Unis. L’objectif de Seattle à long terme est de devenir une ville neutre en émissions de carbone d’ici 2050.

Pour ce faire il était nécessaire d'implémenter un modèle de régression supervisée pour évaluer la prédiction des émissions de CO2.
Ce projet s'est déroulé en deux parties.

Dans un premier temps, il était nécessaire de traiter la base de données (traitement des valeurs manquantes, valeurs abérrantes, feature engineering, etc.) afin d'avoir des données exploitables pour la modélisation. Tout ce travail a été réalisé dans le notebook qui s'intitule : Pélec_01_notebook.ipynb.
Le notebook Pélec_02_code.ipynb présente les résultats de la modélisation choisie (meilleur modèle, analyse des résidus, feature importance, impact de la variable ENERGYSTARScore, etc.). La librairie Pycaret a été utiliser afin de sélectionner le meilleur modèle, c’est-à-dire celui fournissant les meilleures performances en terme de R2, tout en prenant soin d’implémenter une validation croisée pour éviter les problèmes liés au sur-apprentissage.

Le fichier Pélec_03_Présentation.pptx présente la démarche qui a été mise en œuvre tout au long du projet ainsi que les conclusions sur le choix du modèle final et les améliorations possibles.
