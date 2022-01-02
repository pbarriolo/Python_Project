# Projet Python : Étude de la localisation des tournages de la ville de Paris

Pablo Barrio Lopez - Claire Dechaux - Adèle Moreau


L’invention du cinéma se fait au XIXe siècle, grâce à des évolutions technologiques successives. Les « inventeurs » les plus célèbres restent toutefois les frères Lumière. Premiers réalisateurs de l’histoire, ils ont rendu hommage à Paris dans plusieurs de leurs films. La capitale française accueille d’ailleurs la première projection cinématographique publique, le 28 décembre 1895, réalisée par Antoine Lumière. 

De nombreux films français ont été tournés à Paris. Certains ont d’ailleurs connu un formidable succès à l’international, comme *Le fabuleux destin d’Amélie Poulain*. Mais beaucoup de réalisateurs internationaux se laissent aussi tenter par les charmes de Paris. La liste des films ayant pour décor la capitale est longue. De *Midnight in Paris* à *La Délicatesse*, en passant par *La Môme*, *Ratatouille*, *Da Vinci Code* ou encore *Marie-Antoinette*. Paris réunit tout ce qui attire en France. La ville offre des décors de rêve pour le cinéma, grâce à ses monuments célèbres et à une architecture historique. D’ailleurs, Paris remporte, avec New-York, la palme de la ville la plus filmée au monde.

La ville de Paris reste néanmoins vaste et présente des caractéristiques hétérogènes selon ses quartiers, et notamment ses arrondissements. Durant ce projet nous nous sommes ainsi demandés comment les différents tournages cinématographiques sont répartis dans l’espace parisien et quels sont les facteurs influant sur cette répartition ? Pour tenter de répondre à cette problématiques, nous commencerons par étudier les lieux de tournages dans la ville de Paris pour en distinguer la répartition, puis nous concentrerons notre analyse sur 2 axes pouvants expliquer cette répartition : la répartition des lieux culturels sur l’ensemble de la ville et l’urbanisme (superficie des bâtiments) de Paris.


Détails des fichiers présents dans notre git :

- Étude de la localisation des tournages de la ville de Paris.ipynnb : Notebook principal

- Données : Dossier contenant toutes les données utiles au projet
    lieux-de-tournage-a-paris-csv.csv : Base de données principale, recense des informations sur les lieux de tournages dans la ville de Paris de 2016 à 2020,    disponible à l'adresse https://opendata.paris.fr/explore/dataset/lieux-de-tournage-a-paris/table/?disjunctive.type_tournage&disjunctive.nom_tournage&disjunctive.nom_realisateur&disjunctive.nom_producteur&disjunctive.ardt_lieu&dataChart&fbclid=IwAR1fIzMdQJFL8WPnwV_rZUwjBmeKQE4d5JHIELippsvERKLKmelPysytMqg
    lieux-cultures-paris-csv.csv : Base de données utile dans la partie II, recense les lieux culturels de la ville de Paris et leurs caractéristiques, disponible à l'adresse https://www.data.gouv.fr/fr/datasets/grand-paris-express-et-lieux-culturels-1/?fbclid=IwAR1wuDHbyKYCTAEONE6OGaU-i_OBT8RiNBLHvZnZq8MDSdlPu8fInkCGe1I#
    volumesbatisparis-csv-reduit.csv : Base de données utiles dans la partie III, contient initialement les caractéristiques de tous les bâtiments de la capitale mais a été restreinte aux variables utiles, base de données initiale disponible à l'adresse https://opendata.paris.fr/explore/dataset/volumesbatisparis/information/
    carteparis.png : Carte de Paris en fonction des arrondissements
    idf.csv : Base de données des contours administratifs des communes françaises, seulement utile ici pour les contours de l'Ile-de-France
