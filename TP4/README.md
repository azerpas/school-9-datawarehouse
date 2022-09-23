## 1. Faites resumé detaillé sur l'architecture de Data Warehouse
Un datawarehouse est composé de 3 couches :
- Le niveau inférieur est la base de données relationnelle qui contient les données brutes. On récupère des données à l'aide d'ERP ou d'ETL.
- Le niveau intermédiaire est le datawarehouse où on retrouve le serveur OLAP (Online Analytical Processing) relationnel et OLAP multidimensionnel.
- Le niveau supérieur est le serveur de présentation qui permet de visualiser les données, c'est la couche client.
## 2. Que-ce que vous avez compris des tables de dimensions et de faits ?
- Les tables de faits sont des tables qui contiennent des informations sur les faits d'affaires, souvent exprimés en valeurs numériques. 
- Les tables de dimensions sont des tables qui contiennent des informations sur le contexte des faits d'affaires. Elles sont souvent exprimées en valeurs catégorielles grâce à des attributs.
## 3. Faites un résumé sur les types d'un Data Warehouse
Il existe principalement 2 types de datawarehouse :
- Le magasin de données (datamart) qui est un datawarehouse centralisé et qui contient une partie des données. On s'intéresse à un seul sujet d'analyse.
- Les entrepôts de données d'entreprise (EDW) parmis lesquels:
    - Le bus de magasins de données (datamart bus) qui permet de centraliser les données de plusieurs datawarehouse grâce à une approche *bottom-up*.
    - Le hub-and-spoke qui permet de centraliser les données de plusieurs datawarehouse grâce à une approche *top-down*.
    - Le fédéré qui permet de centraliser les données de plusieurs datawarehouse grâce à une approche *hybride*.