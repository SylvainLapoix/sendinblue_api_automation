Tentative d'automatisation de la gestion du mailing et des bases de contact via l'API Sendinblue.

# Python

Sur la base des recettes de référence du guide de [l'API fourni par Sendinblue](https://developers.sendinblue.com/reference/getcontacts-1), nous visons à l'automatisation des principales actions requises pour la gestion de contacts et des campagnes mail ou SMS via Sendinblue.


## Contacts

### Requête de base

- [x] récupération de tous les contacts
- [x] récupération de toutes les listes
- [x] créer ou màj un contact
- [x] ajouter des contacts existants à une liste
- [x] supprimer un contact d'une liste
- [x] importer des contacts
- [x] exporter sortie de get_lists en .csv

### Recette 1 : importer des nouveaux contacts dans une liste "nouveaux_arrivants"

1. réconcilier base nouveaux arrivants avec les IDs des listes correspondantes ;
2. nester par groupe en .scsv ;
3. importer chaque groupe avec l'ID de sa liste

### Recette 2 : transférer l'intégralité des contacts d'une liste à une autre

1. récupérer mail / IDs d'une liste ;
2. ajouter les contacts à la nouvelle liste ;
3. les supprimer de l'ancienne liste.


## Mailing

*- à venir -*

# R

L'API est également requêtable en R. Nous verrons dans un second temps s'il est opportun de porter les recettes pour intégrer le requêtage API au workflow de traitement de données ou s'il est plus simple d'articuler les deux langages suivant les usages.