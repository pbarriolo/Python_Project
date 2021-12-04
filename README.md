# Python_Project :chat:
token pablito: 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

Analyse de la répartition des lieux de tournage à Paris 

!!Toujours tout détailler ce qu’on fait!!

Claire : Partie 1 du I
Pablo : Partie 2
Adèle : Partie 2 du I

I/ Vue d’ensemble de la répartition géographique des lieux de tournages

étudier la BDD sous tous ses angles 

Lieux de tournage à Paris 
https://opendata.paris.fr/explore/dataset/lieux-de-tournage-a-paris/table/? disjunctive.type_tournage&disjunctive.nom_tournage&disjunctive.nom_realisateur&disjunctive.no m_producteur&disjunctive.ardt_lieu&dataChart&fbclid=IwAR1fIzMdQJFL8WPnwV_rZUwjBmeKQE 4d5JHIELippsvERKLKmelPysytMqg 

1) Statistiques descriptives
Plot des différentes attributs : localisation en fonction du type de tournage, année de tournage?…

2) Régression de la localisation sur le type de tournage 
spécifier localisation? régresser en fonction des arrondissements/groupes d’arrondissements, indicatrice sur chaque groupe, trouver un bon moyen de les regrouper (20 groupes?)
conclu : influence de la localisation ?
arrondissement ou y a le plus de tournages?
plotter par arrondissement

bien différencier les tournages hors de paris

Classification supervisée


II/ Lieux culturels et touristiques : facteur d’attraction des productions cinématographiques ? 

Grand Paris Express et lieux culturels 
https://www.data.gouv.fr/fr/datasets/grand-paris-express-et-lieux-culturels-1/? fbclid=IwAR1wuDHbyKYCTAEONE6OGaU-i_OBT8RiNBLHvZnZq8MDSdlPu8fInkCGe1I# 

ne prendre que les codes postaux 75
croiser avec la colonne arrondissement
plotter et tout
régression
en tirer conclu : influence


III/ Impact de l’urbanisme sur la répartition des lieux de tournages 

1/ Espaces verts 

Espaces verts et assimilés 
https://opendata.paris.fr/explore/dataset/espaces_verts/information/?disjunctive.type_ev&disjunctive.categorie&disjunctive.adresse_codepostal&disjunctive.presence_ cloture 

2/ Volumétrie 

Volumes bâtiments 
https://opendata.paris.fr/explore/dataset/volumesbatisparis/information/ 

Emprises/ terrains bâtis et non bâtis 
https://opendata.paris.fr/explore/dataset/emprise-batie-et-non-batie/information/ 

3/ Chantiers ou autre ??? peut-être moyen

Chantiers à Paris 
https://opendata.paris.fr/explore/dataset/chantiers-a-paris/table/? disjunctive.cp_arrondissement&disjunctive.chantier_categorie&disjunctive.moa_principal&disjunct ive.chantier_synthese&disjunctive.localisation_detail&disjunctive.localisation_stationnement 


IV/ Comparaison avec une autre ville

https://data.london.gov.uk/dataset/cultural-infrastructure-map?fbclid=IwAR1TWUJOvU_KM5zLG0XZjtlgfq_Zn6atQ9oinAJ_LEshiT65_s-HGqGOkms
