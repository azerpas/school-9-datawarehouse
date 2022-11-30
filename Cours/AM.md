# Analyse multidimensionnelle
- Obtenir infos déjà agrégées selon besoins users
## Modélisation multidimensionnelle
- Temps
- Localisation
- ...

## HyperCube OLAP
Hypercube à *N* dimensions

### OLAP (Online Analytical Processing)
Opérations réalisées sur hypercube
-> Calcules réalisés pendant chargement ou MAJ du cube

### Composantes du cube
- *Cellule* : occurence du fait
- *Dimension* : axes d'analyse, ensemble de valeurs
- *Indicateurs* : valeurs mesurées
- *Hierarchie* : spécifiées par dimension, hiérarchie de valeurs

### Architecture
<img width="586" alt="image" src="https://user-images.githubusercontent.com/19282069/204814533-f99e9df3-1360-4634-b991-a34b003c59f2.png">

## Implémentations du OLAP
### ROLAP (Relational OLAP)
- Cube stocké dans SGBDR
- En étoile
#### Avantages
- Facile à implémenter
- Peu coûteux
- Evolution facile
- Gros stockage
#### Inconvénients
- Performance faible

### MOLAP (Multidimensional OLAP)
Matrices à plusieurs dimensions
- Colonnes : axes et indicateurs
- Lignes : cellules
#### Avantages
- Performance élevée
#### Inconvénients
- Difficile à implémenter

### HOLAP (Hybrid OLAP)
Solution mixte
#### Avantages
- Compromis coût-performance