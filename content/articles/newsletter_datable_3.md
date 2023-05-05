---
title: "Infolettre Datable - Mai 2023"
date: 2023-05-05T07:53:48+01:00
draft: False
---

# Datable Infolettre Données et Énergie mai 2023

![bannière datable](https://www.tuba-lyon.com/wp-content/uploads/DATABLE-e1679568343921.png)

Bonjour à tous,

Dans cette troisième info-lettre Datable, nous avons préparé une compilation de dataviz, d’actualités, d’outils sur l’énergie en France et dans la Métropole de Lyon.

Au sommaire :

- **Dataviz :** des tracés des infrastructures d'énergie, une vision de la production et de la consommation d’énergie en France, à l'échelle nationale, régionale, et métropolitaine…
- **Open Data :** l'étude "Individualisation des frais de chauffage" de l’ADEME : le rapport et les données utilisées…
- **Biogaz :** comprendre et mesurer la méthanisation en France…
- **Data Science :** l'IA expliquée par EDF, un webinaire proposé par Tenerrdis, la détection d'anomalie sur les bruits du réseau de gaz, la maintenance prédictive du colmatage dans les centrales nucléaires
- **Nucléaire :** l’Allemagne débranche ses centrales nucléaires, la Belgique repousse la fermeture des siennes, en France Emmanuel Macron parle un peu vite sur les économies d’eau
- **Réseaux de chaleur :** plus près de nous, une nouvelle chaufferie à bio-masse à Vénissieux et la SNCF, accompagnée de la grande muette, qui se branche au réseau de chaleur métropolitain à Gerland

---

## Dataviz 📊 🗺️

### Tracés des infrastructures d'énergie

![Cartographie des infrastructures réseaux d'énergie, vue de la Métropole de Lyon](https://www.tuba-lyon.com/wp-content/uploads/agence_ore_dataviz_cartographie_reseaux_infra_energie_metropole_lyon.png)

Explorez les réseaux de transport et de distribution d'énergie sur votre territoire, grâce à cette cartographie publiée par [l’Agence ORE](https://www.agenceore.fr/) *(dont vous n’avez pas fini d'entendre parler ici)*.

Les données source sont disponibles sur le [portail de l'Agence ORE (distributeurs)](https://opendata.agenceore.fr/) et sur [Open Data Réseaux Énergie (transporteurs)](https://opendata.reseaux-energies.fr/).

➡ ***[cartographie des infrastructures des réseaux d'énergie](https://www.agenceore.fr/datavisualisation/cartographie-reseaux)***


### Production énergétique des territoires

![energie produite sur le territoire](https://www.tuba-lyon.com/wp-content/uploads/datable_dataviz_energie_produite_arh.png)

Quelle est la part de la filière nucléaire dans la production d’énergie en France ? En Auvergne-Rhône-Alpes ? Qu'en est-il de l'énergie éolienne, solaire, hydraulique ?

Pour avoir rapidement une vision d'ensemble ou par territoire des sources de l’énergie produite en France, l’[Agence ORE](https://www.agenceore.fr/) produit et héberge cette cartographie de la production énergétique des territoires :

➡ ***[https://www.agenceore.fr/datavisualisation/production-elec-par-territoire](https://www.agenceore.fr/datavisualisation/production-elec-par-territoire)***


### Consommation locale d'énergie par secteur et par type

![infographie représentant la consommation d’énergie sur le territoire](https://www.tuba-lyon.com/wp-content/uploads/datable_dataviz_consommation_energie_locale-1.png)

Pendant de la production, comment est consommée l’énergie sur le territoire ? Toujours via [l’Agence ORE](https://www.agenceore.fr/), voici une [datavisualisation de la consommation d’énergie locale par secteur et par type](https://www.agenceore.fr/datavisualisation/consommations-locales-energie).

On peut y découvrir par exemple, que la consommation en énergie de la Métropole de Lyon est d’un peu plus de 19  millions de MWh ( 57% de gaz, 43% d’électricité), et que cette consommation est essentiellement faite par les secteurs de l'industrie, du tertiaire et par la consommation résidentielle, à peu près à parts égales.


### Suivi de la consommation de Gaz hiver 2022 - 2023

![tableau présentant la consommation de gaz en hiver 2022-2023, comparée à 4 ans plus tôt](https://www.tuba-lyon.com/wp-content/uploads/odre_dataviz_consommation_gaz.png)

Dans un contexte de crise énergétique, mais aussi de transition et de sobriété énergétique, voici un [tableau de bord hebdomadaire de la consommation de gaz en France](https://odre.opendatasoft.com/pages/suivi-consommation/) publié par [Open Data Réseaux Énergie (ODRÉ)](odre.opendatasoft.com). Ces données mises à disposition sur le site de GRTgaz ainsi que sur Open Data Réseaux Energies permettront de donner un état des lieux du système gazier français en lien avec la mise en œuvre du plan de sobriété du gouvernement.

Née en janvier 2017, Réseaux Énergies a vocation à s’enrichir avec de nouvelles données multi-énergies, multi-opérateurs et multi-réseaux mais également à s’élargir avec de nouveaux acteurs souhaitant partager une démarche de transparence et de pédagogie à l’égard des citoyens, des collectivités territoriales et des acteurs économiques, et contribuer ainsi à l’élaboration et l’évaluation des politiques énergétiques.

Réseaux Énergies est le fruit de la collaboration de GRTgaz, RTE et Teréga qui ont été à l’origine de sa création. Ils ont depuis été rejoints par l’AFGNV, Weathernews France, Elengy, Storengy et Dunkerque LNG.

---

## Open Data 💾

### Données de l'étude "Individualisation des frais de chauffage" de l’ADEME

![un radiateur avec robinet thermostatique](https://www.tuba-lyon.com/wp-content/uploads/chauffage-collectif.jpg)

Le dispositif d'Individualisation des Frais de Chauffage (IFC) est une obligation réglementaire qui concerne une grande majorité des immeubles collectifs équipés de chauffage central collectif (soit près de 4,5 millions de logements). Les charges de chauffage sont ainsi reparties selon la consommation du logement incitant les occupants à réduire leurs consommations de chauffage et à réaliser des économies d'énergie.

L'ADEME avec l'appui de nombreux acteurs professionnels du chauffage collectif a conduit une étude de référence permettant de faire un état des lieux complet du dispositif IFC en France et en Europe. Cette étude menée se traduit par plusieurs volets :

- un benchmark à l'échelle européenne
- une analyse des coûts et de rentabilité de la mesure IFC
- une analyse statistique des gains énergétiques engendrés par l'IFC
- une étude sociotechnique : facteurs de réussite et d'échec, impact sur les pratiques des ménages et la gouvernance des copropriétés

Ces différents livrables sont maintenant disponibles en téléchargement, ainsi qu'une synthèse reprenant les grands enseignements de cette étude sous forme de recommandations.

Le document de synthèse de l'étude est disponible [sur la librairie en ligne de l’ADEME](https://librairie.ademe.fr/urbanisme-et-batiment/647-individualisation-des-frais-de-chauffage-quels-avantages-.html)

Le jeu de données utilisé dans l’étude est également accessible en open data sur la plateforme nationale [data.gouv.fr](https://www.data.gouv.fr/fr/datasets/donnees-de-letude-individualisation-des-frais-de-chauffage/#/resources).

---

## Biogaz - CH₄ 🔥

### Jamy l'Épicurieux explique la méthanisation

Tout ce que vous avez toujours voulu savoir sur le gaz naturel et la méthanisation, sans avoir osé le demander, Jamy l'Épicurieux l’a fait en vidéo, avec la participation de GRDF :

[![jamy thumbnail](https://www.tuba-lyon.com/wp-content/uploads/jamy_thumbnail.png)](https://www.youtube.com/watch?v=wwl05u5U9vo)

En supposant que vous soyez curieux mais que vous n’ayez pas le temps de visionner cette vidéo, voici les éléments à retenir en résumé :
Le méthane, CH₄ (molécule faite d’un atome de carbone et quatre atomes d’hydrogène), qui constitue l'essentiel du gaz dit naturel que nous brulons dans nos chaudières et cuisinières est un hydrocarbure, fossile, et donc ressource limitée qui ne se renouvelle pas à l’échelle de temps humaine. 

Il a plusieurs avantages : il se stocke facilement, et peut être utilisé dans des centrales électriques pour ajuster la production électrique.
Mais l’accès à cette ressource ne va pas sans difficultés d’ordre géopolitique, la Russie détenant un quart des réserves mondiales.

En le consumant, on libère de l’eau et du CO₂ selon la formule :

`CH₄ + 2*O₂ => CO₂ + 2*H₂0`

La méthanisation, c'est un peu faire le chemin inverse : partir des déchets issus de l'agriculture (effluents de l'élevage, déchets végétaux) qui sont riches en carbone, en hydrogène et en oxygène, et par une réaction qui a lieu via des bactéries, dans une cuve fermée, chauffée, et brassée, obtenir des molécules de méthane, et des matières organiques servant de fertilisant.

Le méthane produit ainsi peut être valorisé de différentes manières : 

- Cogénération : Le méthane produit est brûlé sur place, pour générer de l'électricité, et la chaleur de l'eau de refroidissement est utilisée dans un réseau de chaleur local.
- Injection : envoi du méthane produit dans le réseau de Gaz. Nécessite de séparer le méthane du CO₂ puis d'ajouter le "parfum" du gaz.

Le digestat, c'est le résidu de la digestion des bactéries utilisées dans la méthanisation : il est utilisé comme fertilisant pour les sols.
22 tonnes de matières organiques en entrées donnent 19 tonnes de digestat en sortie.

Production française de biogaz est équivalente à 3% de la consommation nationale de gaz.

➡ ***[À visionner sur YouTube](https://www.youtube.com/watch?v=wwl05u5U9vo)***

### Panorama de la bio-méthanisation dans la région Auvergne Rhône Alpes

![Vue du méthaniseur Méthamoly](https://www.tuba-lyon.com/wp-content/uploads/methaniseur_methamoly.jpg)

En 2019, neuf partenaires institutionnels et techniques ont signé la [Charte de partenariat 2019-2023 pour le développement de la méthanisation en Auvergne-Rhône-Alpes "Ambitions Biogaz 2023"](https://www.biogaz-aura.fr/fileadmin/user_upload/mediatheque/enr/Documents/Biogaz/Charte_BIOGAZ_2023/Charte_regionale_methanisation_2019-2023_VF_signee.pdf) et se sont ainsi engagés à créer les conditions pour accompagner et accélérer le développement vertueux de la méthanisation en région.

La Région publie [panorama en ligne de la biométhanisation en Auvergne Rhône Alpes](https://lookerstudio.google.com/reporting/55f32fab-f58a-4f17-8d8c-9c498e85eaef/page/EHdpB).
Cet état des lieux, fruit du travail collectif des partenaires d'Ambitions Biogaz 2023, notamment des services déconcentrés de l'État et d'AURA-EE, se met instantanément à jour avec les informations apportées par le réseau à la base de données mutualisée.

![évolution annuelle du nombre d’unités en service en région](https://www.tuba-lyon.com/wp-content/uploads/panorama_methanisation_1.png)

![nombre de mises en service par an en région, par type de valorisation](https://www.tuba-lyon.com/wp-content/uploads/panorama_methanisation_2.png)

### Observatoire du bio-méthane

![odre ratio biogaz produit gaz consomme region.png](https://www.tuba-lyon.com/wp-content/uploads/odre_ratio_biogaz_produit_gaz_consomme_region.png)

Le biométhane se développe sur tout le territoire français. Il est produit à partir de la transformation de matières organiques issues de divers secteurs : agricole, déchets ménagers, industriel, gaz issu des installations de stockage des déchets non dangereux (ISDND), station d’épuration. 

L’[ODRÉ](https://odre.opendatasoft.com/) publie un [Observatoire du bio-méthane](https://odre.opendatasoft.com/pages/observatoire-biomethane-v2/#implantation-des-sites) qui permet de suivre les différents points d'injection de bio-méthane en service, de [mesurer par région le ratio entre le biogaz produit et le gaz consommé](https://odre.opendatasoft.com/pages/observatoire-biomethane-v2/#rgions), et même de [localiser les projets d'implantation de "rebours"](https://odre.opendatasoft.com/pages/observatoire-biomethane-v2/#implantation-des-sites-rebours), qui permettent de trouver un exutoire au biogaz produit lors de périodes de faible consommation comme l'été.


---

## Data Science 👩🏼‍🔬

### Les termes de l'IA expliqués par EDF

![le deep learning expliqué par EDF](https://www.tuba-lyon.com/wp-content/uploads/glossaire_deep_learning.png)

De nos jours, on entend parler de l'Intelligence Artificielle à toutes les sauces, et dans tous les domaines. 
Système expert, IA symbolique, apprentissage automatiques ou machine Learning, supervisé ou non, apprentissage profond ou deep Learning, réseau de neurones … autant de mots ou de notions que l’on entend très souvent, sans forcément savoir ce qu'ils recouvrent exactement.

Quel est le concept derrière ? Comment se les représenter ?

Nicolas Bousquet et Yannig Goude de la R&D d'EDF se sont prêtés au jeu de définir de manière synthétique et accessible ces notions clés qui permettent de comprendre les bases de l’intelligence artificielle.

➡  ***À lire par ici [les termes de l'IA expliqués par EDF](https://www.edf.fr/groupe-edf/inventer-l-avenir-de-l-energie/r-d-un-savoir-faire-mondial/pepites-r-d/intelligence-artificielle/univers-5-mots-cles)***

### Un webinaire sur les applications de l'IA dans le domaine de l'énergie via Tenerrdis 

Inceptive, société spécialisée dans le conseil et l'ingénierie en intelligence artificielle et membre du club des partenaires de Tenerrdis, vous propose un webinaire de 90 minutes sur les applications de l'IA dans le secteur de l'énergie, **le 17 mai 2023, de 10h à 12h**.

***Détails et inscription sur [la page dédiée sur le site de tenerrdis](https://www.tenerrdis.fr/fr/evenements/webinaire-les-applications-de-lia-dans-le-secteur-de-lenergie/)***



### Wavely - Détection d'anomalie par le bruit

Un des cas d'application de l’intelligence artificielle est la détection d’anomalie dans les signaux, et notamment dans les bruits. 

C'est la spécialité de [Wavely](https://www.wavely.fr/), une start-up **"deep tech"** qui a été mise en avant par GRDF dans le cadre de l’appel à projets “Dispositifs physiques et logiciels pour une supervision intelligente des installations de production de biométhane” lancé en mai et juin 2020.

![l'équipe de Wavely](https://www.tuba-lyon.com/wp-content/uploads/wavely_team.jpg)

La solution, en mode expliquée à une grand-mère, ça donne ça :

> C’est simple, les machines tombent malades et au lieu de faire leur clic clic habituel, elles se mettent à faire clic clac. C’est ce qu’entendent nos capteurs, un drôle de bruit sera le signe que les machines ne vont pas bien. 

➡  ***À lire sur le site [act4gaz de GRDF](https://act4gaz.grdf.fr/lintelligence-humaine-du-capteur-wavely)***

### La data science pour prédire le niveau de colmatage dans les centrales nucléaires

Le groupe EDF met régulièrement à profit la data science pour trouver des solutions à des problématiques coûteuses. Dans le nucléaire, les phénomènes de colmatage (obturation) entraînent par exemple des opérations de maintenance très onéreuses. Une approche data science a permis d'identifier les facteurs clés des pannes et d’élaborer des procédures opérationnelles pour les contrôler. Il en découle une maîtrise de la cinétique de colmatage, ainsi qu’un gain de sûreté pour le parc nucléaire.

➡ ***Une innovation à découvrir en vidéo sur le site [electridays.fr d’EDF](https://www.electricdays.fr/fr/innovations/data-science-et-nucleaire)***

---

## Nucléaire ☢️⚡

### En Allemagne, les dernières centrales nucléaires se sont arrêtées, mais le pays n’en a pas tout à fait terminé

La page du nucléaire se tourne en Allemagne. Les trois derniers réacteurs allemands ont cessé de fonctionner le samedi 15 avril dernier. La fin du nucléaire a fait l’objet d’un consensus partagé par les quatre principaux partis politiques : lancé en 2003 par les sociaux-démocrates et les écologistes, le processus a été accéléré par les conservateurs et leurs alliés libéraux-démocrates en 2011, après l’accident nucléaire de Fukushima. La catastrophe a montré que « même dans un pays de haute technologie comme le Japon, les risques liés à l’énergie nucléaire ne peuvent être maîtrisés à 100 % », argumentait alors l’ex-chancelière Angela Merkel.

![Démolition d'une tour de refroidissement de la centrale nucléaire de Biblis, en Hesse, en février 2023 © Daniel Roland / AFP](https://www.tuba-lyon.com/wp-content/uploads/centrale_nucleaire_demolition.png)

Au total, trente-deux réacteurs doivent être démantelés, un chantier qui pourrait prendre encore une quinzaine d’années au mieux. Un site de stockage doit accueillir 300 000 m3 de déchets faiblement et moyennement radioactifs à partir de 2027. Les quelque 27 000 m3 de déchets hautement radioactifs produits par les centrales devront, eux, encore patienter : la mise en service de leur futur site de stockage n’est pas prévue avant 2050. Coût estimé : 176 milliards d’euros. 

➡  ***Article complet de Violette Bonebas à lire [sur reporterre.net](https://reporterre.net/Nucleaire-l-Allemagne-arrete-ses-derniers-reacteurs)***

### La Belgique reporte sa sortie du nucléaire de 2025 à 2035

La Belgique importe 90 % de son énergie consommée, dont 51 % depuis la Russie. 
Cette dépendance et le contexte géopolitique actuel l'amène à revoir sa stratégie de sortie du nucléaire pourtant inscrite dans la loi belge depuis 2003.

Le gouvernement belge a finalement acté le 17 mars dernier une nouvelle « stratégie énergétique », qui réduirait la dépendance aux hydrocarbures russes sur fond de guerre en Ukraine et pourrait acter le renoncement à l'abandon du nucléaire en 2025. La promesse d'une sortie progressive du nucléaire est inscrite dans la loi belge depuis 2003.

➡  ***Article complet à lire [sur lesechos.fr](https://www.lesechos.fr/monde/europe/belgique-la-sortie-du-nucleaire-probablement-reportee-en-2035-1394752)***

### Économiser l’eau en passant les centrales en circuit fermé ? L’annonce très discutable d'Emmanuel Macron

![Les réacteurs doivent être refroidis en permanence afin de fonctionner en toute sécurité. Ici, la centrale nucléaire de Belleville-sur-Loire (Cher).](https://www.tuba-lyon.com/wp-content/uploads/centrale_nucleaire_tour_refrigeration.png)

>« On doit adapter nos centrales nucléaires au changement climatique, en engageant un vaste programme d’investissements pour faire des économies d’eau et leur permettre de fonctionner beaucoup plus en circuit fermé. » 

Noyée au milieu du discours sur le Plan eau d’Emmanuel Macron, le 30 mars à Savines-le-Lac (Hautes-Alpes), cette annonce est passée quasiment inaperçue auprès du grand public. Mais il y a fort à parier que les membres de la direction d’EDF sont tombés de leur chaise en l’entendant, tant le chantier s’annonce titanesque, et sa pertinence, discutable.

Pas de réelles économies d’eau, travaux trop longs et coûteux : le projet d’Emmanuel Macron de passer les réacteurs nucléaires en circuit fermé n’est pas une solution miracle.

➡  ***Article complet d’Émilie Massemin à lire [sur reporterre.net](https://reporterre.net/Economiser-l-eau-des-centrales-nucleaires-le-projet-discutable-de-Macron)***

---

## Réseaux de chaleur 🫠

### Une nouvelle chaufferie biomasse intègre le réseau à Vénissieux

![La chaufferie Sentuc du réseau de chaleur de Vénissieux](https://www.tuba-lyon.com/wp-content/uploads/La-nouvelle-chaufferie-alimente-le-reseau-de-chaleur-depuis-le-1er-mars-2023.-scaled-1.jpeg)

Pour la construction et l’installation de son outil et la réalisation des 6 km de canalisations, Dalkia investit 12,3 millions d’euros. L’Ademe (Agence de l’environnement et de la maîtrise de l’énergie) finance plus de la moitié du projet (6,5 M€), via le Fonds Chaleur.

L’équipement intègre une chaudière bois d’une puissance de 6,6 mégawatts (MW). « Elle utilise comme combustible des résidus de bois issus de l’entretien des forêts et des déchets forestiers récoltés dans un périmètre de moins de 150 km », précise Jérôme Aguesse, directeur de Dalkia Centre-Est, filiale d’EDF.

Michèle Picard, maire de Vénissieux, le rappelle : « La mixité contractuelle du réseau était de 55 % d’énergie renouvelable et récupérable en 2022. » Cette part devra passer à 63 % en 2023, puis à 67,5 % en 2028, comme le prévoit le contrat de Délégation de service public.

➡  ***Article complet sur le site [expressions-venissieux.fr](https://www.expressions-venissieux.fr/2023-04-03-energie-une-nouvelle-chaufferie-biomasse-integre-le-reseau/)***

### L'armée et la SNCF se raccordent au réseau de chaleur urbain de la Métropole de Lyon

![Le Technicentre SNCF de Gerland à Lyon](https://www.tuba-lyon.com/wp-content/uploads/technicentre_gerland.jpg)

Dans le quartier de Gerland, les technicentres de la SNCF et deux quartiers militaires sont désormais reliés au réseau de chaleur urbain. Deux démarches visant à faire des économies et optimiser leurs démarches RSE.

Au gaz, la SNCF et l'armée préfèrent désormais les 65 % d'énergies renouvelables qui alimentent le réseau de chaleur urbain de la métropole. Depuis quelques semaines, le technicentre SNCF de Lyon Gerland et ses voisins de quelques mètres, les quartiers militaires de la Mouche et Sabatier viennent de raccorder leurs bâtiments au réseau de chauffage urbain de la Métropole de Lyon. Deux sites préalablement chauffés avec des chaudières gaz.

➡ ***Article complet sur le site [les echos.fr](https://www.lesechos.fr/pme-regions/auvergne-rhone-alpes/larmee-et-la-sncf-se-raccordent-au-reseau-de-chaleur-urbain-de-la-metropole-de-lyon-1911387)***

---

C’est tout pour cette fois !

Si vous avez une actualité en lien avec les données et l'énergie à transmettre, n’hésitez pas à contacter [Philippe](mailto:philippe.lemaire@tuba-lyon.com) par email.
