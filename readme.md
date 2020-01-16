
Ce projet a été réalisé dans le cadre de la formation [Data Analyst](https://openclassrooms.com/fr/paths/65-data-analyst), sur la plateforme OpenClassrooms.

Voir le fichier [présentation.pdf](présentation.pdf), utilisé comme support lors de la soutenance.

## Sujet

Faire une étude sur la sous-nutrition dans le monde. Pour se faire, réaliser l'analyse de données issues du [site](http://www.fao.org/faostat/fr/#data) de la FAO (Food and Agriculture Organization of the United Nations).

## Organisation des sources


Le dossier contient 4 sous-dossiers :

### 1_analyse_de_donnee

Il contient le **notebook jupyter** qui permet de préparer les données et qui contient les réponses *aux questions 1 à 14*.

Les données analysées sont dans le fichier `/data`.

### 2_creation_bdd

Le **notebook jupyter** contenu dans ce dossier prépare la base de données (en répondant *aux questions 15 à 18*).

Il exécute ensuite les requêtes SQL des questions 19 et 20.

Les données utilisées se trouvent dans `/data`.

### 3_base_de_donnee

Ce dossier contient la base de données `sqlite3`. Les tables sont aussi enregistrées au format `csv`.

Ces fichiers sont générés par le notebook précédent.

### 4_outil_interactif

C'est un **notebook** supplémentaire, que j'ai trouvé intéressant à développer. Il permet de produire un document markdown contenant des statistiques qui sont générées automatiquement. 

L'utilisateur doit juste entrer une liste de noms de pays et de produits.

*Ce notebook utilise la base de donnée `sqlite3`*.
