# Modèle Linéaire Généralisé

Ce projet, réalisé dans le cadre de l’Executive Master Statistique & Intelligence Artificielle (Paris Dauphine – PSL), consiste à modéliser et prédire une variable cible à partir d'un jeu de données météorologiques collectées à Bâle, en Suisse. L'objectif principal est de mettre en œuvre des modèles linéaires généralisés (GLM) pour la classification, en exploitant les nombreuses variables disponibles tout en tenant compte des défis liés à la dimensionnalité et à la colinéarité.

L’analyse débute par une exploration approfondie des données, suivie d’une sélection rigoureuse des variables (basée sur la colinéarité, les p-valeurs et des ANOVA successives). Plusieurs modèles sont comparés : modèle logit, modèle avec sélection automatisée des variables, et modèles intégrant des composantes principales issues d’une analyse en composantes principales (ACP). La méthode du coude est utilisée pour sélectionner les composantes expliquant au moins 90 % de la variance.

Les performances (Accuracy, Sensitivity, Specificity, taux d’erreur en validation croisée et AUC) sont systématiquement évaluées sur l’ensemble des modèles obtenus, afin d’identifier la stratégie la plus robuste. Le projet expérimente également une approche bayésienne (rstanarm) pour évaluer l’apport des modèles probabilistes dans un contexte de données limitées.

L’ensemble des analyses, visualisations et scripts sont disponibles dans ce dépôt afin de favoriser la reproductibilité des résultats et d’ouvrir la discussion sur les choix méthodologiques. 
