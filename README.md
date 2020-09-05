# Clustering sur des données textuelles

L’objectif de ce projet est de réaliser un clustering des workers (employés) et un clustering des expériences à travers les outils de Data Science en text mining.

Nous disposons d’un dataset *worker_profession.csv*. Il est composé de deux colonnes :

- worker_id : l’ID du worker
    
- list profession : la liste des professions de ce worker.

A chaque profession correspond un nombre de mois d’expérience, et la donnée est parsée comme suit :
`profession_1 |nb_de_mois_xp_1;profession_2 |nb_de_mois_xp_2` etc...

Nous utilisons des outils de text-mining (TFIDF, etc...), de la data visualisation et des analyses de données pour finalement faire du biclustering bipartite, SpectralClustering, etc...
