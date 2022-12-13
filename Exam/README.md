# Exercice 1 :
## 1. Un entrepôt de données peut être modélisé soit par un schéma en étoile, soit par un schéma en flocon. Décrivez brièvement les similitudes et les différences des deux modèles, puis analysez leurs avantages et inconvénients l'un par rapport à l'autre.
Parlons d'abord des similitudes entre un schéma en étoile et un schéma en flocon:
- Les deux modèles sont des modèles de données multidimensionnelles.
- Les deux modèles sont des modèles de données dénormalisés.
- Les deux modèles utilisent des tables relationnelles.

Les différences entre les deux modèles sont les suivantes:
- Le schéma en étoile est un modèle de données dénormalisé qui ne conserve pas le niveau de décomposition des données.
- Le schéma en étoile contient en son centre une table de faits et des tables de dimensions, alors que le schéma en flocon part sur une approche plus hiérarchique en utilisant des tables qui contiennent des informations générales qui sont détaillées dans des tables plus petites.
- L'avantage du schéma en étoile est qu'il est plus simple à mettre en place et à maintenir dans un premier temps, mais il est moins flexible que le schéma en flocon.
## 2. C’est quoi la différence entre OLAP et OLTP ?
OLTP (Online Transaction Processing) est un système de traitement de transactions qui permet de gérer les transactions de l'entreprise, tels que des achats, des ventes, des réservations, etc...

OLAP (Online Analytical Processing) est un système de traitement analytique de simulations ou de tendances sur un Hypercube qui permet de gérer les données de l'entreprise au moment d'un chargement ou de la mise à jour du cube. Il est utilisé pour les analyses afin d'extraire les donnéees souhaitées du cube. 

OLTP est donc utilisé pour les transactions de base de données, tandis que OLAP est utilisé pour les analyses et les rapports.
## 3. C’est quoi ETL ?
ETL (Extract, Transform, Load) est un processus qui permet d'extraire des données de sources multiples (BDD, fichiers, etc...) grâce à de multiples techniques (Push, Pull, etc...), de les transformer pour les rendre cohérentes et fiables et enfin de les charger dans un entrepôt de données. Il est utilisé pour la mise à jour périodique et répétée des données, en tout sécurité afin de ne pas perturber le OLTP.

On utilise en général l'ETL en amont d'une analyse OLAP, afin de mettre à jour les données de l'entrepôt de données et vérifier leur cohérence et intégrité.