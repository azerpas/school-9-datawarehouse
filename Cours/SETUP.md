# Setup d'un DW
- [Techniques](#techniques-pour-mettre-en-place-un-dw)
- [Réalisation d'un DW en 5 étapes](#cinq-étapes-importantes-pour-la-réalisation-dun-dw)
- [Principales applications autour d'un ED](#principales-applications-autour-dun-ed)

# Techniques pour mettre en place un DW
Évolution des besoins et des sources: *démarche itérative*
# 3 techniques pour mettre en place un DW
## Top-Down
Concevoir entrepôt intégralement: *connaître à l'avance les dimensions et les faits*

**Objectif**: livrer solution saine par méthodes et tech éprouvées des BDD

### Avantages 
- Architecture intégrée
- Réutilisation des données
- Pas de redondance
- Vision claire
### Inconvénients
- Méthode lourde
- Méthode contraignante
- Demande du temps
<img width="589" alt="top down" src="https://user-images.githubusercontent.com/19282069/207076632-05b296cc-c17c-41c1-939a-9bf77aff4963.png">

## Bottom-Up
Créer datamarts un par un puis les regrouper

**Objectif**: Solution pour faciliter et accélerer requêtes d'analyse

### Avantages
- Simple
- Rapide
- Efficace à court terme
### Inconvénients
- Pas efficace à long terme
- Volume de travail d'intégration pour obtenir un entrepôt de données
- Risque de redondances

<img width="605" alt="bottom up" src="https://user-images.githubusercontent.com/19282069/207076816-0ef11ce5-74af-4b21-a0ae-7a5c00d6c359.png">

## Middle-Out
Concevoir intégralement le DW, puis créer des divisions plus petites et gérables

### Avantages
- Meilleur des 2 approches
- Développement modèle de manière itérative
- Développement d'une infra lourde seulement si nécessaire
### Inconvénients
- Implique parfois compromis de découpage

<img width="566" alt="image" src="https://user-images.githubusercontent.com/19282069/207078432-6861c9a9-7fe9-485e-99f7-76c55f02e742.png">

# Cinq étapes importantes pour la réalisation d'un DW
## 1. Conception
### Définir la finalité du DW
- Quelle activité de l'entreprise faut-il piloter ?
- Quel est le process à modéliser ?
- Qui sont les décideurs ?
- Quels sont les faits numériques ?
- Quelles sont les dimensions ?
### Définir modèle de données
- Étoile / Flocon
- Cube
- Vues matérialisées
## 2. Acquisition des données
**Pour** l'alimentation ou la maj du DW
- MAJ régulière: Besoin d'un outil pour automatiser

**ETL (Extract, Transform, Load)**

### Extraction
- Sources multiples (BDD, fichiers, ...)
- Techniques multiples (Push, Pull)
- Périodique et répétée
- Difficile: sans perturber OLTP apps

### Transformation
Rendre les données:
- Cohérentes
- Fiables

## 3. Définition des aspects techniques de la réalisation
### Contraintes
- Logicielles
- Matérielles
- Humaines

## 4. Définition des modes de restitution
- But du process d'entreposage
- Conditionne svt la conception du DW
- Toutes les analyses nécessaires doivent être réalisables
### Types d'outils
- Outils de requêtage
- Outils d'analyse
- Outils de datamining

## 5. Stratégies d'administration, évolution, maintenance
Toutes les strat à mettre en palce pour l'administration, l'évolution et la maintenance du DW

# Principales applications autour d'un ED
- Rapports divers (Reporting)
- Dashboards
- Analyse en ligne diverses (OLAP)
- Fouille de données (Data Mining)
- Visualisation de données (Data Visualization)