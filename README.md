## Clone

```$ git clone https://github.com/thimyxuan/taxis-pickup-zone-clustering.git```

## Dépendances

```$ pip install library_name```

Pour utiliser ce projet vous aurez besoin d'installer les librairies ci-dessous.

## Stack technique

- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Sklearn

## Sujet

Uber souhaite réduire le temps d'attente des clients avant d'être pris en charge par un taxi.

Pour ce faire, il veut créer une fonctionnalité qui fournit à ses chauffeurs une carte indiquant les zones dynamiques suivant le jour et l'heure.

Dans cette étude, nous nous intéressons aux activités des taxis Uber dans la ville de New York en 2014 et 2015. 

Nous utilisons les techniques de machine learning non supervisé pour identifier les zones dynamiques à New York et présentons les résultats sur une carte.

## Problématique

Le but : 

- Utiliser les techniques de machine learning non supervisé de clustering pour mettre en évidence des clusters
- Visualiser les clusters sur une carte avec un filtrage par jour et par heure

## Plan 

PARTIE 1 - Préparation des données 
- Rassembler les données 2014
- Ajout de colonnes relatives à la date

PARTIE 2 - Modèle KMeans
- Cibler un jour de la semaine
- Déterminer le nombre optimal de clusters k
- Entraînement du modèle & prédictions
- Résultats et visualisation
- Généralisation à tous les jours de la semaine

PARTIE 3 - Modèle DBScan
- Cibler un jour de la semaine
- Déterminer le paramètre epsilon 
- Entraînement du modèle & prédictions
- Résultats et visualisation
- Généralisation à tous les jours de la semaine

PARTIE 4 - Comparaison et conclusion