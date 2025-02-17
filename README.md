# Mini-projet-2-Placement

(En cours)

Mini projet permettant de mettre en œuvre des codes de Machine/Deep Learning sur un dataset d'insertion professionnelle des étudiants.

Le fichier csv de données à été téléchargé depuis Kaggle : https://www.kaggle.com/datasets/ruchikakumbhar/placement-prediction-dataset

l'objectif est de prédire l'insertion ou non d'un étudiant à l'aide de plusieurs informations comme le nombre de projets et de stages effectués, le nombre de certifications, sa note globale...

J'ai proposé trois solutions de classification : 

- Random Tree (accuracy : 78%, roc_auc : 85%)
- Random Forest (accuracy : 79%, roc_auc : 87%)
- Neural Network MLP (accuracy : 80%, roc_auc : 88%)

Les résultats obtenus apportent donc satisfaction, nous permettant de poursuivre notre étude, notamment sur le soutien à apporter aux étudiants. 

J'ai alors essayé de déterminer les variables les plus importantes selon chaque modèle, permettant d'avoir des pistes pour venir en aide aux étudiants qui ont moins de chance d'être insérés. 