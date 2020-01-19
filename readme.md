Ce projet a été réalisé dans le cadre de la formation [Data Analyst](https://openclassrooms.com/fr/paths/65-data-analyst), sur la plateforme OpenClassrooms.

## Scénario

> Vous êtes intégré à une nouvelle équipe de chercheurs de la Food and Agriculture Organization of the United Nations (FAO), l'un des organes qui compose l'ONU et dont l'objectif est d' « aider à construire un monde libéré de la faim ».
Votre équipe est chargée de réaliser une étude de grande ampleur sur le thème de la sous-nutrition dans le monde.
Le problème de la faim est complexe et peut avoir de multiples causes, différentes selon les pays. L’étape préliminaire de cette étude sera donc d’établir un “état de l’art” des recherches déjà publiées, mais également de mener une étude statistique destinée à orienter les recherches vers des pays particuliers, et de mettre en lumière différentes causes de la faim. Ainsi, une poignée de data analysts (dont vous !) a été sélectionnée pour mener cette étape préliminaire. Lors de la première réunion, vous avez été désigné pour mettre une place la base de données que votre équipe pourra requéter (en SQL) à souhait pour réaliser cette étude statistique.

<br />

### :arrow_forward: [Slides de présentation](présentation.pdf)

### :notebook: [Notebook : Préparation et analyse des données](1_analyse_de_donnee/analyse_donnee.ipynb)

### :notebook: [Notebook : Création de la base de donnée MySQL](/2_creation_bdd/creation_bdd.ipynb)

-----------------------------------------

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

L'utilisateur doit entrer une liste de noms de pays et de produits.

*Ce notebook utilise la base de donnée `sqlite3`*.
