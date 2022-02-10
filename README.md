# Ensemble des scripts réalisés dans le cadre du projet ModOAP

Le projet est dédié aux romans scolaires disponibles sur Gallica. D'autres outils sont disponibles sur le GitHub du projet : [https://github.com/MODOAP?tab=repositories](https://github.com/MODOAP?tab=repositories).

### Téléchargement et récupération des données
- BaOIA_table_des_matieres_gallica.ipynb : téléchargement des tables des matières via API de Gallica
- BaOIA_metadonnees_corpus.ipynb : création d'un fichier regroupant toutes les métadonnées de tous les documents du corpus à partir des fichiers json créés lors du téléchargement
- BaOIA_api_geonames.ipynb : recherche d'informations géographiques avec alignement sur l'API geonames

### Étude de contenu
- BaOIA_statistiques_entites_nommees.ipynb : calculs statistiques des entités extraites
- BaOIA_liste_informations_wikidata.ipynb : création d'une liste d'informations disponibles pour la récupération d'informations pour un alignement "personnalisé"
- BaOIA_concordance_entités_extraits.ipynb : création d'un tableur excel pour vérifier la pertinence des entités dans l'extrait dont elles sont tirées

### Visualisation
- BaOIA_statistiques_graphiques_metadonnees.ipynb : calculs statistiques et création de graphiques
- BaOIA_frise_chronologique.ipynb : création d'une frise chronologique avec évènements ou métadonnées
- BaOIA_carte_chaleur_regions.ipynb : création d'une carte de chaleur statistique par région française
- BaOIA_carte_chaleur_departements.ipynb : création d'une carte de chaleur statistique par département
