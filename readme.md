*Ce projet a été réalisé dans le cadre de la formation [Data Analyst](https://openclassrooms.com/fr/paths/65-data-analyst), sur la plateforme OpenClassrooms.*

### Introduction

Ce projet a pour but d'explorer les données de la FAO (Food and Agriculture Organization of the United Nations) afin de mettre en lumière différentes causes de la faim dans le monde.

Pour ce faire, j'ai récupéré depuis le site de la FAO des données sur tous les pays du monde concernant la disponibilité, l'importation et l'exportation de différentes denrées alimentaires, ainsi que la population globale et sous-alimentée.

J'ai nettoyé, fusionné et transformé ces données afin de créer une base de données MySQL composée de cinq tables. L'explorer m'a permis de trouver des éléments de réponse concernant la faim dans le monde.
J'ai notamment découvert certaines ressources alimentaires qui étaient mal réparties et utilisées.

<br />

:arrow_forward: [Slides de présentation](présentation.pdf)

:notebook: [Notebook : Préparation et analyse des données](1_analyse_de_donnee/analyse_donnee.ipynb)

:notebook: [Notebook : Création de la base de donnée MySQL](/2_creation_bdd/creation_bdd.ipynb)

<br />

-----------------------------------------

### Organisation des sources

Le dossier contient 4 sous-dossiers :

#### 1_analyse_de_donnee

Il contient le **notebook jupyter** qui permet de préparer les données et qui contient les réponses *aux questions 1 à 14*.

Les données analysées sont dans le fichier `/data`.

#### 2_creation_bdd

Le **notebook jupyter** contenu dans ce dossier prépare la base de données (en répondant *aux questions 15 à 18*).

Il exécute ensuite les requêtes SQL des questions 19 et 20.

Les données utilisées se trouvent dans `/data`.

#### 3_base_de_donnee

Ce dossier contient la base de données `sqlite3`. Les tables sont aussi enregistrées au format `csv`.

Ces fichiers sont générés par le notebook précédent.

#### 4_outil_interactif

C'est un **notebook** supplémentaire, que j'ai trouvé intéressant à développer. Il permet de produire un document markdown contenant des statistiques qui sont générées automatiquement. 

L'utilisateur doit entrer une liste de noms de pays et de produits.

*Ce notebook utilise la base de donnée `sqlite3`*.
