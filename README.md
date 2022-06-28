## NSY107
#Introduction
Pour ce projet, deux buts principaux étaient fixés :
1.	Tout en prenant en considération les ensembles de données équilibrés et non-équilibré, on avait pour premier but de mesurer les performances des modèles implémentés.
2.	Pour les modèles utilisés, nous allons comparer leurs performances.
Pour réaliser les buts cités ci-dessus, deux expériences ont été effectuées pour la sélection, la formation et l'évaluation des modèles, l’une en utilisant un ensemble de données équilibrés et l’autre avec un ensemble de données déséquilibré.
#Modèles implémentés
Dans nos expériences, nous allons utiliser deux principalement deux types d’architectures :
Long Short-Term Memory (LSTM) et Deep Graph Convolutional Neural Networks (DGCNN).
Par conséquent, trois modèles seront implémentés :
Les modèles implémentés sont les suivants :
1.	Model-1, un DGCNN à 1 couche ;
2.	Model-2, un DGCNN à 2 couches ;
3.	LSTM, un réseau LSTM suivi d'une couche entièrement connectée qui reçoit le dernier vecteur d'état caché du réseau LSTM et envoie le résultat à une couche sigmoïde pour une classification binaire
