# Introduction aux bases de données NoSQL - MongoDB
MongoDB est une base de données **NoSQL** open source qui stocke des données sous forme de **documents JSON**. Il offre une flexibilité et une scalabilité supérieures par rapport aux bases de données relationnelles traditionnelles, et est conçu pour être facile à utiliser et à développer.

ces bases sont plus rapides pour certaines opérations.

# Installation
1. Aller sur le site officiel et [télécharger mongoDB](https://www.mongodb.com/try/download/community).
2. Installer le logiciel sur votre machine (custom) : `C:\mongodb\` (sous Windows)
3. avant de lancer mongodb, aller dans le dossier d'installation : `C:\mongodb\`
    * creer un dossier `data/db/` : qui va recevoir les données de notre db
    * creer un dossier `log/`
    * creer un dossier `config` et ajouter le fichier `mongodb.conf`
```
dbpath = C:\mongodb\data
port = 27017
logpath = C:\mongodb\logs
```

