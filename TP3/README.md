## 1. Faites un petit résumé sur les données multidimensionnelles
Les données multidimensionnelles comme l'indique leur nom sont des données qui sont organisées en plusieurs dimensions. Elles sont utilisées pour des analyses sur plusieurs critères de données.
## 2. Proposez un exemple de Data Warehouse (sujet, historique, sources et enquêtes)
Un exemple de Data Warehouse est le suivant : Un Datawarehouse pour un réseau social
### 2.1. Sujet
- Suivi du marché: Taux de rétention, taux d'acquisition, taux de conversion, etc.
- Suivi des utilisateurs: Nombre de messages, nombre de commentaires, nombre de likes, nombre de partages, nombre de followers, nombre de personnes suivies, etc.
- Suivi des contenus: Contenu qui a le plus de succès, contenu qui a le moins de succès, etc.
### 2.2. Historique
- Les données sont stockées dans un Datawarehouse depuis le début de l'activité du réseau social.
### 2.3. Sources
- Les données sont récupérées depuis les bases de données du réseau social.
### 2.4. Requêtes
- Quel est le taux de rétention des utilisateurs ?
- Quel est le taux d'acquisition des utilisateurs ?
- Quel est le taux de conversion des utilisateurs ?
- Quel est le nombre de messages par utilisateur ?
- Quel est le nombre de commentaires par utilisateur ?
## 3. Faites un résumé détaillé sur l’OLAP et l’OLTP
### 3.1. OLAP
Online Analytical Processing, ou OLAP, est un système de traitement des données qui permet d'analyser des données multidimensionnelles. Il permet de faire des analyses sur plusieurs critères de données. C'est un systèmes avec des requêtes simples et rapides. La base de données est fréquemment mise à jour, il convient ainsi de faire attention à l'intégrité des données.
### 3.2. OLTP
Online Transaction Processing, ou OLTP, est un système de traitement des données qui permet de gérer des transactions. Il permet de faire des requêtes complexes et lentes. La base de données est rarement modifiée, ainsi on y trouve des données avec une forte intégrité.
## 4. Cherchez et proposez un exemple de représentation de données avec l’application de différentes opérations OLAP
Si on reprend l'exemple des réseaux sociaux, on va pouvoir utiliser cette **Granulité des dimensions**:
- Utilisateur → Sexe → Age → Profession
- Géographie → Pays → Ville → Quartier
- Contenu → Type → Catégorie → Sous-catégorie
## 5. Faites un résumé sur la modélisation et la conception d’une Data Warehouse
- Définition des besoins
    - Définition des objectifs
    - Définition des dimensions
    - Définition des faits
    - Choix de la granularité des faits
- Définition des sources de données
- Définition du modèle de données
    - Niveau conceptuel (modélisation multidimensionnelle)
    - Niveau logique (modélisation relationnelle)
- Définition des processus de chargement