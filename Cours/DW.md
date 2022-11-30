# Data warehousing - Introduction

BDD construite par copie de données provenant de sources de données multiples pour répondre à des besoins d'analyse.

# Big Data

Domaine pluri-disciplinaire qui traite de la gestion de données de grande taille et de leur analyse. 

## Décomposé en 4 disciplines

### 1. Math-Info
Souvent identifiée comme *Data Science*.
- Apprentissage numérique (ML)
- Statistiques

### 2. Informatique distribué
Analyse de données large échelle.
- Schéma Map-Reduce: calcul distribué

### 3. Informatique parallèle
Analyse de données à haute performance.
- PC multi-coeurs ou cluster de GPU

### 4. Conception et exploitation de bases de données (NoSQL)
Stocker des données structurées complexes ou de simples fichiers.

# Différences entre Data Warehouse et système transactionnel
## BD transactionnelle
- Données en temps réel
- Questions sur données identifiées
## Data Warehouse
- Questions statistiques sur données statiques

# Implémentation d'un Data Warehouse avec un SGBDR
- Vues concrètes
- Dénormalisation

# Modélisation logique de données
## Modèle en étoile
Dénormalisé pour haut niveau de performance des requêtes

<img width="356" alt="image" src="https://user-images.githubusercontent.com/19282069/204807141-a93c0ebf-fde5-4170-8951-1b6a7f469970.png">

## Modèle en flocon
Dénormalisé mais conserve niveau de décomposition des données
<img width="370" alt="image" src="https://user-images.githubusercontent.com/19282069/204807273-3cff2bd8-82ae-42d0-97b4-a24aeb99b4c3.png">

## Modèle en constellation
Collection de tables de faits de dimensions communes
<img width="338" alt="image" src="https://user-images.githubusercontent.com/19282069/204808617-ece03aa5-f693-464c-9cdf-57d98d1fcf93.png">

# ETL (Extract, Transform, Load)
Copie de données de tables système transactionnelles vers tables de données de Data Warehouse