# Projet_DSSS_2023

Projet ENSAE Data Science et Sciences Sociales de Théo et Camille, portant sur le traitement des crises migratoires dans les journaux français. 

Ce répertoire contient l'ensemble des base de données et notebooks nécessaires à la conduite du projet. 

### Base de données
Les bases de données sont stockées dans le dossier `data` :
- `data/fullcorpus20210725_DATE.csv` : ensemble des données jusqu'en 2021
- `data/data_aug.csv` : données webscrappées de l'année 2022

### Notebooks de travail
Dans l'ordre logique de conduite de l'étude, vous trouverez :
- `data_processing.ipynb` : notebook de nettoyage des données contenant les articles
- `stat_desc.ipynb` : notebook d'analyse descriptive de la base de données
- `Dataset_France.ipynb` : notebook d'analyse du vocabulaire sous forme de wordclouds
- `LDA_script.ipynb` : notebook d'implémentation d'un Analyse Latente de Derichlet
- `Sentiment Analysis.ipynb` : notebook d'analyse de sentiments des articles avec CamemBERT
- `Humanitaire-securitaire.ipynb` : notebook d'analyse des cadrages humanitaire et sécuritaire avec un classifieur baysien

### Résultats, bases intermédiaires et images
Les résultats et bases intermédiaires sont stockés dans le dossier `data_cleaned`, les images dans le dossier `images`