# Gdelt2018-GGGROS
## Analyse de l’année 2018 via la base de données GDELT

L’objectif du projet est de concevoir un système qui permet d’analyser l’evolution des relations entre les differents pays, en étudiant le ton des mentions (positives/negatives) dans les articles médias de chaque pays.

L'exercice auquel nous devions répondre est détaillé à l'adresse suivante :
http://andreiarion.github.io/projet2018.html

Ce Github contient la réponse apportée par les étudiants suivant :
Matthieu Roussel, Thierry Golder, Alba Ordoñez, Joël Géhin, Pierre Gelade, Guillaume Soufflet (ordre random)




Précisions sur le projet attendu

Fonctionnalités de base :
- Afficher le nombre d’articles/évènements qu’il y a eu pour chaque triplet (jour, pays de l’évènement, langue de l’article).
- Pour un acteur donné en paramètre, afficher les événements (valeurs de la table events) qui y font référence (dans les derniers 6 mois).
- Trouver les sujets (acteurs) qui ont eu le plus d’articles positifs/negatifs pour chaque triplet (mois, pays, langue de l’article).
- Trouver quels sont les acteurs/pays/organisations qui divisent le plus (par exemple ont eu une perception positive dans une partie du globe et une perception negative dans le rest du monde). Permettez une agrégation par jour/mois/annee.

Fonctionnalité supplémentaire :
- Vous devez proposer et implementer une fonctionnalité supplémentaire qui nous permettra de mieux comprendre l’évolution des relations entre les différents pays, en étudiant le ton des mentions (positives/negatives) dans les articles médias de chaque pays.
Par example: en donnant le nom de 2 acteurs/pays, afficher l’évolution du ton des articles qui contiennent les deux acteurs/pays.

Contraintes :
- Vous devez utiliser au moins 1 technologie vue en cours en expliquant les raisons de votre choix (SQL/Cassandra/MongoDB/Spark/Neo4j).
- Vous devez concevoir un système distribué et tolérant aux pannes (le système doit pouvoir continuer après la perte d’un noeud).
- Vous devez pré-charger une année de données dans votre cluster
- Vous devez utiliser AWS pour déployer le cluster.



