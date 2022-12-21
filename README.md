# Incidents de sécurité et régularité des trains sur le réseau de la SNCF

Bienvenue sur le Github présentant notre projet python comptant pour le module **Python pour la Data-Science** de l'ENSAE.

## Justification et Objectifs

La Société Nationale des Chemins de fer Français (SNCF) est l'entreprise ferroviaire publique française, officiellement créée par convention entre l'État et les compagnies de chemin de fer préexistantes, en application du décret-loi du 31 août 1937. Elle est notamment présente dans les domaines du transport de voyageurs, du transport de marchandises et réalise la gestion, l'exploitation et la maintenance du réseau ferré national appartenant à l'État. (*Wikipédia*)

Contrôlant une grande partie du transport public national (notamment le réseau ferroviaire), dont la vitalité dans la vie quotidienne des français et dans le déroulement des activités économiques n'est plus à démontrer. C'est donc à juste titre que le moindre incident ou le moindre raté sur le réseau du transport ferroviaire d'une part, peut bouleverser la routine des citoyens usagers quotidiens des transports et d'autre part peut générer une avalanche de manifestations de mécontentement.

Nous nous penchons à travers notre projet intitulé **Incidents de et régularité des trains de la SNCF**, comptant pour le module de **Python pour la datascience** de l'**ENSAE**, sur les incidents de sécurité ayant été répertoriéS au cours des dernière années mais également sur l'épineuse question de la régularité des trains.

Le long de ce projet, nous avons essentiellement : 
+ présenté le réseau de la SNCF en France continentale en l'occurence les gares et leurs fréquentations ;
+ présenté les incidents de sécurité survenus sur le réseau durant les dernières années ;
+ passé en revue les performance de la SNCF en terme de ponctualité (les TER en l'occurence) ;
+ analysé les sentiments des citoyens à travers les *tweets** ;
+ élaboré un modèle de prévision des taux de régularité sur les prochaines années à l'aide d'un processus `ARIMA`.


## Récapitulatif des notebooks et autres fichiers présents sur notre Github
+ **rendu_final** : rendu final résumant  tout ce qui a été fait
+ **presentation-reseau-sncf** : présentation des gares de la SNCF en France
+ **frequentation-gares** : Présentation et visualisation des données sur la fréquentation des gares de la SNCF 
+ **Decouverte_base_incidents**: prépare la base de données sur les incidents: récupération de la base, description de la base, nettoyage et traitement des valeurs manquantes
+ **Preprocessing_Regularite**: prépare la base de données sur la regularite : récupération de la base, description de la base, nettoyage et traitement des valeurs manquantes, aggregation de données
+ **Analyse_descriptive_Regularite** : Présentation et visualisation des données sur la regularité 
+ **incidents_de_sécurité**: visualisation des données sur les incidents 
+ **analyse_tweet**: brève analyse des sentiments sur la SNCF à partir des tweets récupérés.
+ **prevision_taux_regularite_ter** : Prévision du taux de régularité des TER à partir d'un processus `ARIMA`

## Membres de l'équipe
+ BIAOU Ghislain 
+ GANSOU Jivanos
+ CHOHO Yann 
