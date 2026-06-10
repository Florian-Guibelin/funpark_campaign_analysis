# **Analyse campagne promotionnelle FUNPARK**



## Présentation du projet



Ce projet est une étude de cas fictive basée sur des données simulées représentant l'activité d'un groupe nommé FUNPARK, exploitant plusieurs parcs d'attractions dans différents pays.



Face à une baisse de fréquentation, l'entreprise met en place une campagne promotionnelle visant à attirer davantage de visiteurs. L'objectif de ce projet est de reproduire une analyse marketing réaliste et d'évaluer l'impact de cette campagne sur les comportements d'achat des clients.



### Objectifs



Nettoyer et préparer les données.

Étudier les profils des clients et leurs comportements d'achat.

Évaluer l'impact de la campagne promotionnelle.

Identifier les segments de clientèle les plus contributeurs aux revenus.

Formuler des recommandations à partir des résultats obtenus.



### Structure du projet



funpark\_campaign\_analysis/

│

├── data/

│   ├── raw/          # Données brutes

│   └── processed/    # Données nettoyées

│

├── notebooks/

│   ├── 01\_data\_cleaning.ipynb

│   └── 02\_analysis.ipynb

│

├── .gitignore

├── requirements.txt

└── README.md



### Démarche



#### 1\. Nettoyage des données



Le notebook 01\_data\_cleaning.ipynb comprend :



* l'exploration du jeu de données;
* la standardisation des variables;
* la conversion des types;
* le traitement des valeurs manquantes;
* la recherche des doublons;
* la détection des valeurs aberrantes.



#### 2\. Analyse 



Le notebook 02\_analysis.ipynb est consacré :



* à l'analyse des profils clients;
* à l'étude des comportements d'achat;
* à l'évaluation de l'impact de la campagne promotionnelle;
* à la réalisation de tests statistiques;
* à la formulation de recommandations.



### Principaux résultats



#### Impact de la campagne



La dépense moyenne par transaction apparaît plus élevée après la campagne promotionnelle.

Les distributions des dépenses suggèrent une augmentation globale des montants dépensés.

Toutefois, les tests statistiques ne mettent pas en évidence de différence significative des revenus moyens avant et après la campagne.

De plus, aucun impact significatif sur l'activité quotidienne n'a pu être démontré.



#### Analyse des segments clients



Les billets FAMILLE représentent une part limitée des ventes mais génèrent une part importante des revenus grâce à une dépense moyenne plus élevée.

Les clients VIP contribuent fortement aux revenus malgré un volume de ventes plus faible.

Les billets STANDARD constituent la principale source de revenus en raison de leur poids dans les ventes.



Les revenus de FUNPARK reposent donc principalement sur :



* un effet volume pour les clients STANDARD ;
* un effet valeur pour les clients VIP.



#### Limites de l'étude



Les données décrivent des transactions et non l'affluence réelle des parcs.

Certaines informations importantes susceptibles d'influencer l'activité (météo, saisonnalité, événements externes) ne sont pas disponibles.

Des données complémentaires seraient nécessaires afin d'évaluer plus précisément l'efficacité de la campagne.



#### Recommandations



Maintenir et valoriser l'offre VIP.

Renforcer l'attractivité des offres destinées aux familles.

Améliorer la collecte des données afin de faciliter les analyses futures.





### Compétences mobilisées



#### Préparation et nettoyage des données



* Traitement des valeurs manquantes
* Détection des doublons
* Gestion des valeurs aberrantes
* Conversion et standardisation des variables



#### Analyse exploratoire



* Statistiques descriptives
* Analyse des distributions
* Segmentation des clients
* Analyse des revenus par catégorie de clients



#### Visualisation des données



* Diagrammes en barres
* Histogrammes
* Diagrammes en boîte (boxplots)
* Interprétation des résultats graphiques



#### Analyse statistique



* Tests d'hypothèses
* Comparaison de groupes
* Interprétation des résultats statistiques



#### Outils



* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

