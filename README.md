Ce projet a pour objectif principal d'obtenir une compréhension approfondie de la relation entre le trafic aérien et les conditions météorologiques en temps réel, en utilisant des données massives (Big Data) et des techniques d'analyse avancées.

1. Analyser l'influence des conditions météorologiques sur le trafic aérien : En étudiant les données météorologiques en corrélation avec les données de trafic aérien, le projet vise à comprendre comment les conditions météorologiques, telles que les tempêtes, les brouillards épais, etc., affectent les opérations aériennes. Cela peut avoir un impact sur la sécurité et l'efficacité des vols.

2. Identifier les pays les plus touchés : Le projet a pour but de déterminer quels pays européens sont les plus touchés par des conditions météorologiques défavorables en relation avec le trafic aérien. Cette information peut être utile pour les autorités aéroportuaires et les compagnies aériennes dans la gestion des opérations.

Les étapes : 

1- Collecte de données en temps réel :

collecter des données en temps réel à partir de deux sources de données différentes :

OpenSky API : Cette API fournira des informations sur le nombre de vols dans l'espace aérien, ainsi que des détails sur le pays d'origine de chaque vol.

OpenWeatherMap API : Cette API fournira des données météorologiques par pays.

2- ingestion des données : ( apache kafka ) 

3- traitement données : spark ml , pyspark.
Première analyse: trouver une corrélation entre les données météorologiques et le nombre de vols,c'est-à- dire expliquer comment les données météorologiques influencent le nombre de vols.
Deuxième analyse: nous allons utiliser les données de vol et les données météorologiques pour identifier les pays européens qui sont les plus touchés par les conditions météorologiques défavorables.

4- visualisation des résultats.
