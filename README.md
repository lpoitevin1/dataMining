
# Auteurs
POITEVIN Louis 
numéro étudiant: 11410541

# European Soccer Database Analysis

Projet réalisé dans le cadre de mon master informatique parcours Data Sciences durant l'UE Data mining.
L'objectif de ce projet est de mettre en oeuvre une approche complète de fouille de données depuis le prétraitement des données jusqu'à l'évaluation de la méthode de fouille.
L'entière réalisation du code à été effectué avec Python3 sous Jupyter Notebook.

# Database 
La base de donnée utilisé est "database.sqlite" disponible à l'adresse suivant sur Kaggle : https://www.kaggle.com/hugomathien/soccer

Elle est consitué de :
* Match : Contient des données relatives aux matchs européen de 2008 à 2016 (+25000)
* Country : Contient la liste des pays concernés par ces matchs.
* League : Contient la liste des ligues pour chaque pays.
* Player : Contient la liste des joueurs européen.
* Player_Attributes : Contient les aptitudes techniques et physique des joueurs.
* Team : Contient la liste des equipes de chaque ligue.
* Team_Attributes : Contient les caractéristiques sportives propres aux équipes.

# Vidéo  

La vidéo de vulgarisation est disponible dans le repertoire /video. 
Une vidéo de 3 minutes ne me donnait pas l'opportunité de dévoiler une vue globale du projet donc j'ai décidé de me concentrer sur une analyse en particulier : Quels attributs d'équipe un entraineur devrait privilégier ?

# Pré-requis : 

## Jupyter notebook
via conda : 
<code>  conda install -c conda-forge jupyterlab </code>

via pip3 :
<code> pip3 install jupyterlab </code>

## Librairies utilisé :
### numpy, pandas, seaborn, matplotlib, pysqlite3
<code> pip3 install <nom_librairie> </code>

# Architecture projet 
L'arborescence du projet est simple avec deux fichiers notebook qui contient le code d'analyse des problématiques suivantes:
* Une équipe est-elle avantagée a domicile ?
* Choix strategiques pour composer la feuille de match d un entraineur.ipynb
* Un dossier data/ qui contient l'ensemble des données nécéssaire à l'execution du code sous Jupyter Notebook.
* Un dossier video/ qui contient la vidéo de vulgarisation 
# Démarrage 
* <code> cd /chemin/du/projet </code>
* <code> jupyter notebook </code>
