# Partie 1 : Etude de cas 
## Exercice 1 : Modélisation d’un SI décisionnel
Nous  voulons  modéliser  un  entrepôt  des  données  qui  permet  d’analyser  les  ventes  d’une 
entreprise  de  restauration  rapide.  Le  principe  est  de  mesurer  les  ventes  grâce  aux  quantités 
vendues  et  aux  bénéfices,  en  fonction  des  ventes  réalisées  par  jour,  dans  un  restaurant  donné, 
pour un aliment donné.  
L’objectif  est  de  pouvoir  analyser  les  ventes  par  jour,  par  semaine,  par  mois  et  par  année.  Les 
restaurants peuvent être regroupés en fonction de leur ville et de leur pays. 
### 1. Énumérez  trois  principaux  types  de  schémas  couramment  utilisés  pour  modéliser  les entrepôts de données.
- Schéma en étoile
- Schéma en flocon
- Schéma en constellation
### 2. Identifier les dimensions et les mesures.
- Dimensions : temps, restaurant, aliment
- Mesures : quantité vendue, bénéfice
### 3. Concevoir un modèle en étoile pour ce DW.
![modele_etoile](./1_3.png)
### 4. Modifier  ce  modèle  en  un  modèle  en  flocon  de  neige  pour  modéliser  explicitement  les hiérarchies  des  dimensions  représentant  le  temps  et  la  localisation  géographique  des magasins.