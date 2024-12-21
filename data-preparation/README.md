# Data-for-Good---Electricity-Capacity

## Data Preparation


### Changelog :


Date : 20/12/2024 

- Upload des fichiers de code, de data nécessaires au traitement des données et la base finale (WORLD_ENERGY_HISTORY_electricity_capacity_prod.csv).

- Modification des packages :

    * **utils.utils :** 
        - Ajout des fonctions get_energy_type, pivot_dates, et GroupMaker.
        - Modification du chemin d'importation de la classe 'CountryTranslatorFrenchToEnglish' : utils.sdp_data.translation -> utils.translation


    * **utils.translation :** 
        - Mise à jour du dictionnaire 'translations_dictionnary' (ajout des nouvelles entrées et des formats, cf [rapport des nouvelles données](https://docs.google.com/document/d/1_N6c9uZ6bc9ptzN9NkBEj9vqvyBwxVPTkWuqwVx49rI/edit?tab=t.0)).

- Ajout d'entrées dans la table 'country_groups.csv' :

    * zone,World,Micronesia
    * zone,World,Northern Mariana Islands
    * zone,World,Tuvalu
    * zone,World,U.S. Territories
    * zone,Asia and Oceania,Micronesia
    * zone,Asia and Oceania,Northern Mariana Islands
    * zone,Asia and Oceania,U.S. Territories
    * zone,Asia and Oceania,Tuvalu


