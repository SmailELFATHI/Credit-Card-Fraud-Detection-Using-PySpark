# Mise en place d’infrastructure Big data pour la Détection de fraude de la carte bancaire


Dans ce projet, j'ai mis en place mise en  place d'une  infrastructure Big data pour la Détection de fraude de la carte bancaire en utilisant  Hadoop et Spark ML. Il peut décider du nombre de  fraudes à examiner en filtrant les prédictions de mon modèle.

L'augmentation des ressources du cluster lors d’entrainement des modèles accélère considérablement les tâches, de sorte que ma solution évolue avec de plus grandes quantités de données.

Le projet a été développé selon la méthodologie CRISP-DM.
Utilisation l’échantillonnage stratifié et la validation croisée pour estimer le fiabilité d’un modèle.

 Les résultats de ce projet peuvent être exploités dans le cadre d'autres projets ayant comme objectif la résolution des problèmes réels de détection de fraude

## Méthodologie

Système distribués:

Hadoop (HDFS).

Spark (MLIB, Python).

IPython Notebook.

Le processus CRISP-DM

Les algorithmes d’apprentissage machine supervisée:

 Naive Bayes, Régression Logistique, Arbre de décision, Forêt aléatoire, Machine à Vecteurs de Support, Réseaux de neurones.

Prédiction et Evaluation de Forêt Aléatoire:

Échantillonnage stratifié, Validation Croisée, Réglage de des hyper-paramètres (Tuning).

## Compréhension de donnée

95 007 enregistrements de transactions par carte
De 2010-01-01 à 2010-12-31

298 enregistrements frauduleux étiquetés

58 variables au total.

Catégorie: fraude(Booléen)(Cible)

56 Variables numérique  au total (Prédicteurs)

date: date

Intervalle du temps 3, 7, 14, 28 jours
