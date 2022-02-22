# Ensemble des scripts réalisés dans le cadre du projet ModOAP

Le projet ModOAP est dédié aux romans scolaires disponibles sur Gallica. D'autres outils sont disponibles sur le GitHub du projet : [https://github.com/MODOAP?tab=repositories](https://github.com/MODOAP?tab=repositories).

### Téléchargement et récupération des données
- ```BaOIA_table_des_matieres_gallica.ipynb``` : téléchargement des tables des matières des documents via l'API de Gallica.

### Étude de contenu
- ```BaOIA_statistiques_entites_nommees.ipynb```: calculs statistiques des entités nommées extraites des documents sous format brut.
- ```BaOIA_liste_informations_wikidata.ipynb``` : permet de récupérer toutes les informations disponibles dans Wikidata à partir d'un mot clé de recherche.
- ```BaOIA_alignement_lieux_wikidata.ipynb``` : permet de récupérer toutes les informations relatives à des lieux via des requêtes à Wikidata. Outil nécessaire à la création des cartes de chaleur.

### Visualisations
- ```BaOIA_carte_chaleur_regions.ipynb``` : création d'une carte de chaleur statistique par région française.
- ```BaOIA_carte_chaleur_departements.ipynb``` : création d'une carte de chaleur statistique par département.
