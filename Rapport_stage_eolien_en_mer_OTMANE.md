<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F2026051402380030c62b1370f34e7e%2Fcrop_1_1778697501682.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=X2adOvLFv97kagVMO6wdT1OuXms%3D&Expires=1779302301' alt='OCR图片'/></div>

Institut de Thermique, Mécanique, Matériaux

UFR Sciences Exactes et Naturelles

## PC0601 Stage L3

<div align="center">

# LA PRODUCTION D'ÉNERGIE PAR L'ÉOLIEN

</div>

Principe physique, évolution, problématiques,

statistiques, recherche actuelle.

— Focus : éolien en mer (offshore et far-shore) —

Par : Tahar OTHMANE

Étudiant en 3ème année de Licence PC

Responsable professionnel : Pr. Nathalie TRANNOY-ORBAN (ITheMM)

Responsable universitaire : J.-S. ANTONIOW

Période du stage : du 23 mars au 10 avril 2026

Année universitaire : 2025/2026

CONFIDENTIALITÉ DU RAPPORT :

OUI Non [X]

Si OUI durée : —

## Table des matières

1 Introduction...3

1.1 Contexte du stage...3

1.2 Présentation de l'ITheMM...3

1.3 Objectifs et méthodologie...3

1.4 Prévention des risques...3

1.5 Plan du rapport...3

2 Principe physique de l'éolien en mer...3

2.1 Énergie cinétique et limite de Betz...3

2.2 Spécificité offshore : vents et facteur de charge...4

2.3 Plages de fonctionnement et chaîne de conversion...4

3 Technologies : éolien posé, flottant et far-shore...5

3.1 Fondations posées...5

3.2 Éolien flottant et concept far-shore...5

3.3 Raccordement et stockage par STEP...5

4 Statistiques mondiales et situation en France...6

4.1 Capacité mondiale et répartition géographique...6

4.2 Parc français et production électrique...6

5 Coûts et mécanisme de soutien...7

5.1 CAPEX, OPEX et LCOE...7

5.2 Évolution des prix sur les appels d'offres...7

5.3 Complément de rémunération bidirectionnel...7

6 Comparaison France / Royaume-Uni...8

7 Avantages, inconveniens et enjeux géopolitiques...9

7.1 Avantages...9

7.2 Inconveniens et impact environnemental...9

7.3 Dépendance aux terres rares et innovations...9

8 Perspectives et conclusion...10

8.1 Objectifs PPE3 et obstacles...10

8.2 Synthèse et bilan...10

A Carte des vents en France et en Europe...11

B Données détaillées : capacités et production offshore...12

C Parcs offshore français — opérationnels et en projet...13

D Schémas de fondations et chaîne de conversion...14

## 1 Introduction

## 1.1 Contexte du stage

Ce rapport présente le travail réalisé dans le cadre du stage bibliographique de Licence 3 Physique à l'URCA (Université de Reims Champagne-Ardenne), effectué du 23 mars au 10 avril 2026 sous l'encadrement du Pr. Nathalie Trannoy-Orban (ITheMM) et la responsabilité pédagogique de M. Jean-Stéphane Antoniow. Le sujet est : « La production d'énergie par l'éolien : principe physique, évolution, problématiques, statistiques, recherche actuelle. » Le travail est centré sur l'éolien en mer (offshore et far-shore), où se concentrent aujourd'hui l'essentiel des innovations de la filière et les principaux enjeux de déploiement à l'horizon 2030-2050.

## 1.2 Présentation de l'ITheMM

L'ITheMM (Institut de Thermique, Mécanique, Matériaux) est un laboratoire de l'URCA rattaché à l'UFR Sciences Exactes et Naturelles, dont est issue mon encadrante Pr. N. Trannoy-Orban. Ses thématiques couvrent la thermique, la mécanique des fluides et des solides, et la science des matériaux, avec des applications à l'énergétique. Plusieurs équipes y travaillent sur des sujets connexes à l'éolien : caractérisation thermique de matériaux composites, méthodes non destructives, et couplage fluide-structure dans les écoulements éoliens. C'est dans ce dernier axe que s'inscrit la thèse d'A. Boujelben, doctorante avec qui j'ai pu m'entretenir au cours du stage, échange qui a alimenté la partie technologique.

## 1.3 Objectifs et méthodologie

Le stage est bibliographique : il n'y a pas eu de manipulation expérimentale, mais un travail de recherche, de lecture critique et de synthèse. La méthode a consisté à identifier les sources de référence (Techniques de l'Ingénieur, GWEC, WindEurope, RTE, KPMG, The Crown Estate, Observatoire de l'éolien, ADEME), à croiser les données chiffrées entre plusieurs sources pour évaluer leur fiabilité et détecter d'éventuels biais, à rédiger des documents intermédiaires hebdomadaires discutés avec l'encadrante, et à produire enfin une synthèse comparative entre la France et le Royaume-Uni, qui constitue la principale puissance offshore européenne.

## 1.4 Prévention des risques

Le stage s'est déroulé entièrement à distance, sur poste informatique personnel. Les dispositions de prévention correspondent aux risques du travail prolongé sur écran : ergonomie du poste, pauses visuelles et alternance des tâches. Aucune manipulation expérimentale.

## 1.5 Plan du rapport

Après cette introduction, le rapport présente les principes physiques (section 2), les technologies posées et flottantes ainsi que le concept far-shore (section 3), les statistiques mondiales et françaises (section 4), les coûts et mécanismes de soutien (section 5), une comparaison France / Royaume-Uni (section 6), les avantages, inconvenients et enjeux géopolitiques (section 7), puis les perspectives et la conclusion (section 8).

## 2 Principe physique de l'éolien en mer

## 2.1 Énergie cinétique et limite de Betz

Le principe de l'éolien en mer est identique à celui de l'éolien terrestre : on récupère une partie de l'énergie cinétique du vent. Pour un flux d'air de masse volumique $ \rho $ ( $ \approx $ 1,225 kg/m $ ^{3} $ à 15 $ ^{\circ} $ C) traversant une surface balayée S à la vitesse $ V_{0} $ , la puissance disponible vaut :

$$
P _ {-} d i s p = \frac {1}{2} \rho S V _ {0} ^ {3}
$$

La dépendance en $ V^{3} $ est la propriété fondamentale : un vent doublé multiplie la puissance par huit, ce qui justifie à lui seul l'intérêt d'aller chercher les vents marins, plus forts et plus stables qu'à terre. La limite de Betz (1919) montre par ailleurs qu'on ne peut récupérer plus de C_p,max = 16/27 ≈ 0,593 de cette puissance, car l'air s'arrêterait derrière le rotor. Les machines offshore modernes atteignent C_p ≈ 0,45 à 0,50, soit 80 % de la limite théorique : la marge de progrès aérodynamique est désormais étroite, et l'essentiel des gains attendus porte sur la taille, la chaîne de conversion et l'implantation.

## 2.2 Spécificité offshore : vents et facteur de charge

L'absence d'obstacles topographiques en mer (relief, forêts, bâtiments) réduit fortement la rugosité de surface et la turbulence : l'écoulement est plus laminaire, plus régulier, et la vitesse moyenne plus élevée. Cette différence structurelle se mesure par le facteur de charge :

$$
F _ {-} c = E _ {-} p r o d u i t e / \left(P _ {-} n o m i n a l e \times 8 7 6 0 h\right)
$$

Concrètement, F_c quantifie l'impact de l'intermittence : un facteur de 35 % signifie que la machine a fonctionné, en moyenne, l'équivalent de 35 % de l'année à pleine puissance. En France en 2024 (données RTE), on observe (Tableau 1) :

<table border="1"><tr><td>Filière</td><td>Facteur de charge</td><td>Heures équiv.</td><td>Référence</td></tr><tr><td>Éolien offshore (France)</td><td>35,2%</td><td>≈3083h</td><td>RTE2024</td></tr><tr><td>Éolien terrestre (France)</td><td>21,8%</td><td>≈1910h</td><td>RTE2024</td></tr><tr><td>Parc nucléaire (France)</td><td>60-75%</td><td>5256-6570h</td><td>RTE2024</td></tr><tr><td>Hywind(Écosse, flottant)</td><td>≈58%</td><td>≈5080h</td><td>Equinor2019</td></tr></table>

<div align="center">

Tableau 1 — Comparaison des facteurs de charge par filière. L'offshore français produit en proportion environ 60 % de plus qu'une éolienne terrestre de même puissance.

</div>

Le facteur de charge typique d'un parc offshore européen s'établit entre 35 % et 50 %, et peut atteindre 58 % dans les meilleures conditions (Hywind, Écosse, 2019). Pour les futurs parcs flottants méditerranéens, les modélisations prévoient F_c ≈ 50 % grâce aux régimes de mistral et de tramontane. L'offshore reste néanmoins en deçà du nucléaire en termes de disponibilité, ce qui justifie la complémentarité des deux filières dans les scénarios RTE.

## 2.3 Plages de fonctionnement et chaîne de conversion

Les éoliennes ne fonctionnent que dans une fenêtre de vent bornée : en deçà de la vitesse de couplage (≈ 10 km/h), les frottements et l'inertie du rotor empêchent la mise en rotation ; au-delà de la vitesse de coupure (≈ 90 km/h), l'éolienne est mise en drapeau (les pales pivotent pour annuler la portance) et freinée mécaniquement. Cette procédure est impérative : historiquement, l'absence ou la défaillance de freinage a

conduit à des emballements destructeurs (rupture des pales, flambage du mât sous les forces centrifuges et les moments de flexion).

La conversion mécanique-électrique se fait selon deux topologies. La génératrice asynchrone, historiquement dominante, requiert des vitesses élevées et donc un multiplicateur (boîte de vitesses). En milieu marin, ce composant est un maillon faible : il subit de fortes contraintes cycliques, présente un taux de défaillance élevé, et exige des vidanges d'huile coûteuses, chaque intervention en mer mobilisant un navire spécialisé. La génératrice synchrone à aimants permanents, devenue le standard en offshore, permet un entraînement direct (Direct Drive) : suppression du multiplicateur, donc moins de maintenance — au prix d'une dépendance aux terres rares (néodyme, dysprosium) discutée en section 7.3.

La puissance produite est centralisée vers une sous-station offshore, qui élève la tension (passage de la moyenne à la haute ou très haute tension) afin de minimiser les pertes par effet Joule lors du transit sous-marin vers le continent.

## 3 Technologies : éolien posé, flottant et far-shore

## 3.1 Fondations posées

Le choix de la fondation dépend de la profondeur du site. Pour des fonds inférieurs à environ 60 m, les fondations posées s'imposent : elles sont fixées directement dans le sol marin et constituent à ce jour la technologie la plus mature, utilisée dans 80 % des parcs européens. On distingue trois types principaux. Le monopieu est un tube en acier de 6 à 10 m de diamètre, enfoncé dans le fond par battage ; il convient aux fonds sableux de la mer du Nord et représente la solution la plus économique. La fondation gravitaire est une large base en béton posée sur un fond préalablement nivelé, retenue par son seul poids propre. Le jacket est une structure métallique en treillis sur pieux, employée pour les eaux plus profondes ou les fonds rocheux ; c'est la solution retenue à Saint-Brieuc. Le retrait total en fin de vie de ces fondations est complexe et coûteux : elles sont parfois laissées sur place pour servir de récifs artificiels.

## 3.2 Éolien flottant et concept far-shore

Au-delà de 60 m de profondeur, le posé devient économiquement et techniquement impraticable : on bascule sur l'éolien flottant. La turbine repose sur une fondation flottante reliée au fond par des lignes d'ancrage, l'ensemble étant assemblé au port puis remorqué sur site, ce qui simplifie considérablement la logistique. Trois grandes familles de flotteurs coexistent : le semi-submersible (colonnes flottantes, le plus mature et privilégié en France), le SPAR (cylindre vertical lesté immergé, choisi pour Hywind) et la TLP — tension leg platform — (lignes d'ancrage tendues). La barge est une variante plus simple, utilisée par Floatgen au Croisic (2 MW, 2018), premier démonstrateur flottant français.

Le terme far-shore désigne les éoliennes installées à grande distance des côtes. Il repose principalement sur la technologie flottante. L'intérêt est triple : vents encore plus puissants et constants, réduction des nuisances visuelles et sonores pour les riverains, et accès à un potentiel beaucoup plus vaste (pour la France : 169 GW techniquement exploitables en posé, mais 454 GW en flottant). Les défis majeurs sont l'acheminement de l'électricité sur de longues distances — qui nécessite des câbles haute tension et des convertisseurs HVDC pour limiter les pertes — et la maintenance en pleine mer, conditionnée par les fenêtres météorologiques.

## 3.3 Raccordement et stockage par STEP

L'éolien reste une énergie « fatale » : sa production dépend du vent et n'est pas pilotable. Pour intégrer cette ressource sans déstabiliser le réseau, on la couple à des moyens de stockage. La solution la plus mature en France reste les Stations de Transfert d'Énergie par Pompage (STEP), qui exploitent l'énergie potentielle de pesanteur E_p = mgh : en surplus, on pompe de l'eau vers un bassin supérieur ; en déficit, on la turbine vers le bassin inférieur. Le rendement global est de 75 à 80 %, et la France dispose d'environ 5 GW de STEP, dont la plus grande est Grand'Maison (1 800 MW). En France, c'est l'hydraulique — et non le nucléaire, dont la dynamique de modulation est lente — qui assure l'essentiel de la régulation rapide du réseau.

## 4 Statistiques mondiales et situation en France

## 4.1 Capacité mondiale et répartition géographique

L'éolien en mer est une technologie récente. Le premier parc commercial, Vindeby (Danemark, 5 MW), a été mis en service en 1991. La filière est restée marginale pendant une vingtaine d'années, avant que la croissance ne s'accélère à partir de 2010 et surtout après 2020 avec l'entrée en force de la Chine. Fin 2024, la capacité offshore cumulée mondiale atteint 83,2 GW, soit 7,3 % de la puissance éolienne mondiale totale (1 135,5 GW). Le marché a ajouté 8,0 GW en 2024, dont 64,6 % en Asie et 33,7 % en Europe. La région Asie-Pacifique domine désormais avec 46,3 GW (55,6 %), tirée par la Chine (41,8 GW), tandis que l'Europe, pionnière historique, conserve 36,7 GW (44,2 %). Les Amériques pèsent encore moins de 0,3 % du parc mondial.

<table border="1"><tr><td>Pays/Région</td><td>Capacité(GW)</td><td>Part mondiale</td><td>Part offshore dans le mix élec.</td></tr><tr><td>Chine</td><td>41,8</td><td>50,3%</td><td>≈1%</td></tr><tr><td>Royaume-Uni</td><td>15,9</td><td>19,2%</td><td>17,0%</td></tr><tr><td>Allemagne</td><td>9,0</td><td>10,9%</td><td>5-6%</td></tr><tr><td>Pays-Bas</td><td>4,9</td><td>5,9%</td><td>≈6%</td></tr><tr><td>Taiwan</td><td>3,1</td><td>3,7%</td><td>—</td></tr><tr><td>Danemark</td><td>2,7</td><td>3,2%</td><td>≈18%</td></tr><tr><td>Belgique</td><td>2,2</td><td>2,7%</td><td>≈7%</td></tr><tr><td>France</td><td>1,5</td><td>1,8%</td><td>0,7%</td></tr></table>

Tableau 2 — Principaux pays par capacité offshore installée fin 2024. La dernière colonne est la part de l'offshore seul dans le mix électrique national (l'éolien total — terrestre + mer — atteint par exemple 56 % au Danemark et 24 % aux Pays-Bas). Sources : GWEC 2025, WindEurope, données nationales.

## 4.2 Parc français et production électrique

La France dispose du deuxième gisement éolien marin d'Europe après le Royaume-Uni grâce à ses 3 500 km de côtes, mais accuse un retard important dans le déploiement de parcs commerciaux. Elle a mis en service son premier parc en novembre 2022 (Saint-Nazaire, 480 MW, EDF), soit dix ans après l'attribution de l'appel d'offres. Deux autres parcs ont suivi en 2024 : Saint-Brieuc (496 MW) et Fécamp (497 MW). Fin 2024, la puissance installée atteint 1 508 MW (3 parcs posés + 1 pilote flottant), et la France se place au $ 8 ^{e} $ rang mondial avec 1,8 % du total.

<table border="1"><tr><td>Parc</td><td>Puissance(MW)</td><td>Turbines</td><td>Mise en service</td><td>CAPEX(Md€)</td></tr><tr><td>Saint-Nazaire</td><td>480</td><td>80×6MW</td><td>Nov.2022</td><td>≈2,0</td></tr><tr><td>Saint-Brieuc</td><td>496</td><td>62×8MW</td><td>Mai2024</td><td>2,4</td></tr><tr><td>Fécamp</td><td>497</td><td>71×7MW</td><td>2024</td><td>≈2,0</td></tr><tr><td>Prov.Grand Large</td><td>25</td><td>3×8,4MW</td><td>2024</td><td>—</td></tr></table>

Tableau 3 — Parcs offshore français opérationnels fin 2024 (3 posés + 1 pilote flottant). Sources : RTE, MerEnergies 2025.

En 2024, les parcs offshore français ont produit 4,02 TWh, soit 9,0 % de la production éolienne nationale (terrestre + mer) et environ 0,7 % de la production électrique totale du pays (539 TWh). Le doublement de la production entre 2023 (1,91 TWh) et 2024 s'explique par la montée en puissance de Saint-Brieuc et Fécamp, partiellement opérationnels en 2023. Le parc de Saint-Brieuc, à lui seul, est dimensionné pour produire 1 820 GWh/an, soit la consommation annuelle d'environ 835 000 habitants. Cette montée en puissance reste très en deçà des objectifs : la PPE3 publiée en février 2026 vise 3,6 GW en 2028 et 15 GW en 2035 — un déficit de 6 à 8 GW est anticipé sur la trajectoire actuelle (cf. annexe B).

## 5 Coûts et mécanisme de soutien

## 5.1 CAPEX, OPEX et LCOE

L'investissement initial (CAPEX) d'un parc offshore posé se situe entre 1,4 et 2,4 milliards d'euros pour des puissances de 450 à 600 MW, soit environ 3 à 5 M€/MW installé — deux à trois fois plus qu'un parc terrestre de même puissance. Les coûts d'exploitation (OPEX) sont également elevés du fait des interventions en mer : navires spécialisés, fenêtres météorologiques restreintes, et ports d'opération dédiés. Ces coûts sont compensés par un facteur de charge nettement supérieur à celui du terrestre, ce qui réduit le LCOE (Levelized Cost of Energy, coût actualisé de l'énergie sur la durée de vie). L'Observatoire de l'éolien 2024 estime le LCOE à 113 €/MWh pour l'éolien en mer posé, contre 82 €/MWh pour le terrestre — chiffres à manier avec prudence : ils dépendent du taux d'actualisation, de la durée de vie retenue (20 ou 30 ans) et de la frontière entre coûts du parc et coûts de raccordement, qui ne sont pas explicités dans toutes les sources.

## 5.2 Évolution des prix sur les appels d'offres

L'évolution des prix garantis sur les appels d'offres français illustre la baisse rapide des coûts au fur et à mesure que la filière se structure (Tableau 4).

<table border="1"><tr><td>Appel d&#x27;offres</td><td>Année</td><td>Parc attribué</td><td>Prix garanti(€/MWh)</td><td>Baisse</td></tr><tr><td>AO1</td><td>2011-12</td><td>Saint-Nazaire,Fécamp,Saint-Brieuc...</td><td>155-180</td><td>—</td></tr><tr><td>AO2</td><td>2013-14</td><td>Yeu-Noirmoutier,Dieppe-LeTréport</td><td>≈155</td><td>≈0%</td></tr><tr><td>AO3</td><td>2019</td><td>Dunkerque(600MW)</td><td>44</td><td>-72%</td></tr><tr><td>AO4</td><td>2023</td><td>Centre Manche1(1GW)</td><td>44,9</td><td>-71%</td></tr><tr><td>AO8</td><td>2024</td><td>Centre Manche2(1,5GW)</td><td>66</td><td>-58%</td></tr></table>

Tableau 4 — Évolution des prix garantis sur les appels d'offres offshore français. Sources : DGEC, Mer et Marine.

La baisse de 155-180 €/MWh à 44 €/MWh entre 2012 et 2019 ( - 72 %) s'explique par trois facteurs combinés : effets d'échelle (turbines passées de 6 à 14 MW, pales plus longues, plus de production par fondation), maturation industrielle (chaîne d'approvisionnement européenne consolidée), et concurrence accrue entre développement. La légère remontée à 66 €/MWh en 2024 reflète l'inflation des matériaux (acier, cuivre) et la hausse des taux d'intérêt depuis 2022, qui pèsent sur des projets fortement capitalistiques.

## 5.3 Complément de rémunération bidirectionnel

Pour sécuriser le financement face aux fluctuations du marché, l'État a mis en place un complément de rémunération bidirectionnel sur 20 ans. Le principe : si le prix de marché est inférieur au tarif garanti par contrat, l'État compense la différence ; s'il le dépasse, le producteur reverse l'excédent. Ce mécanisme, équivalent au système britannique des Contracts for Difference (cf. section 6), agit comme un stabilisateur financier sans sur-rémunérer le producteur. Pendant la crise gazière de 2022-2023, les parcs sous ce contrat ont reversé environ 5,8 Md€ à l'État — preuve que le mécanisme peut fonctionner dans les deux sens. Les exploitants paient par ailleurs une taxe d'usage du domaine public maritime d'environ 20 250 €/MW installé par an, reversée aux communes, à la pêche et à la protection de l'environnement marin.

## 6 Comparaison France / Royaume-Uni

Le Royaume-Uni est, derrière la Chine, le pays qui a le plus développé l'éolien offshore. Son parcours est instructif pour comprendre ce que la France cherche à reproduire — et les limites auxquelles elle se heurtera. Premier parc commercial dès 2003 (North Hoyle, 60 MW), 19 ans avant la France. Avec 15,9 GW raccordés fin 2024, le Royaume-Uni est au $ 2^{\mathrm{e}} $ rang mondial. Surtout, l'éolien offshore représente 17,0 % de l'électricité britannique en 2024 (contre 0,7 % en France), un facteur 24 d'écart qui résume la situation.

Le succès britannique repose sur deux piliers. Le premier est l'antériorité : 25 ans d'expérience industrielle ont permis de constituer une chaîne d'approvisionnement (ports de Hull et Grimsby, usines de pales) et d'amortir les coûts d'apprentissage. Le second est le mécanisme des Contracts for Difference (CfD), opérationnel depuis 2015 : sur le 1er appel d'offres (AR1, 2015), le prix garanti était de 117 £/MWh ; lors de l'AR3 (2019), des offres à moins de 40 £/MWh ont été remportées, inférieures aux prix de gros. La concurrence et l'effet d'échelle expliquent cette baisse. L'AR7 attribué en janvier 2026 a porté sur 8,4 GW à 89-91 £/MWh — en hausse modérée, due à l'inflation matériaux.

<table border="1"><tr><td>Indicateur</td><td>France</td><td>Royaume-Uni</td></tr><tr><td>Capacité installée fin 2024</td><td>1,5 GW</td><td>15,9 GW</td></tr><tr><td>Part dans le mix électrique 2024</td><td>≈0,7%</td><td>≈17%</td></tr><tr><td>Facteur de charge 2024</td><td>35,2%</td><td>≈40%</td></tr><tr><td>Parcs commerciaux opérationnels</td><td>3</td><td>≈35</td></tr><tr><td>1er parc commercial</td><td>2022(Saint-Nazaire)</td><td>2003(North Hoyle)</td></tr></table>

<table border="1"><tr><td>Indicateur</td><td>France</td><td>Royaume-Uni</td></tr><tr><td>Prix dernier appel d&#x27;offres</td><td>44€/MWh(Dunkerque,2024)</td><td>89-91£/MWh(AR7,2026)</td></tr><tr><td>Objectif 2030</td><td>3,6GW</td><td>43-50GW</td></tr><tr><td>Durée appel d&#x27;offres→mise en service</td><td>10-12ans</td><td>5-7ans</td></tr><tr><td>Rang mondial offshore(2024)</td><td>8e(1,8%)</td><td>2e(19,2%)</td></tr></table>

Tableau 5 — Comparaison France / Royaume-Uni sur les principaux indicateurs offshore. Sources : GWEC 2025, RTE, The Crown Estate, Wikipedia.

Deux facteurs expliquent l'écart. D'abord, l'antériorité de vingt ans cumule expérience industrielle et baisse des coûts. Ensuite, le CfD britannique a fourni dès 2015 une visibilité pluriannuelle aux investisseurs, dont la France n'a disposé que tardivement. La France rattrape néanmoins son retard sur les prix : à 44 €/MWh (Dunkerque, 2024), elle est en ligne avec les meilleurs prix européens. Et sur le segment flottant — incontournable pour exploiter la Méditerranée et l'Atlantique profond — la France est en avance, avec Floatgen opérationnel depuis 2018 et deux parcs commerciaux (Narbonnaise 1 et Golfe de Fos 1, 250 MW chacun) attribués fin 2024. Le retard administratif reste le frein principal : 10 à 12 ans en France contre 5 à 7 ans au Royaume-Uni, dont 3 à 4 ans absorbés par les recours juridiques.

## 7 Avantages, inconvenients et enjeux géopolitiques

## 7.1 Avantages

Énergie décarbonée à l'usage. L'éolien offshore émet sur son cycle de vie environ 12- 15 g CO $ _{2} $ /kWh, comparable au nucléaire ( $ \approx $ 6 g) et très loin du gaz ( $ \approx $ 490 g). Aucune émission en exploitation.

Densité énergétique supérieure au terrestre. Avec un facteur de charge de 35-50 % (contre 21-25 % à terre), une éolienne offshore produit jusqu'à deux fois plus d'électricité, à puissance nominale égale, qu'une éolienne terrestre.

Aucune emprise foncière à terre, et les nuisances visuelles et sonores pour les riverains diminuent rapidement avec l'éloignement (presque nulles au-delà de 20 km, ce qui rend le far-shore particulièrement intéressant).

Filière industrielle et emplois. L'éolien offshore génère environ 7 000 emplois par GW installé. La filière française comptait 7 840 emplois ETP fin 2023, en hausse de 50 % sur cinq ans, avec pour objectif 19 000 emplois en 2028. Les principales usines sont au Havre (pales et nacelles Siemens Gamesa) et à Saint-Nazaire (sous-stations, câbles).

Effet récif local. Les fondations immergées favorisent la colonisation par la faune benthique et peuvent constituer des zones interdites au chalutage, jouant le rôle de réserves marines de fait.

## 7.2 Inconvénients et impact environnemental

CAPEX élevé : 3 à 5 M€/MW contre 1 à 1,5 M€/MW à terre, avec un OPEX également supérieur.

Impact environnemental marin. La phase de chantier (battage des pieux pour les monopieux) génère un bruit sous-marin intense pouvant désorienter les mammifères marins (cétacés, phoques). En exploitation, les pales représentent un risque de collision pour l'avifaune migratrice, et les champs électromagnétiques générés par les

câbles peuvent affecter certaines espèces sensibles (raies, requins). Des mesures de réduction existent : rideaux de bulles pendant le battage, dispositifs effaroucheurs, choix d'implantation hors couloirs migratoires.

Conflits d'usage. Pêche professionnelle (zones de chalutage), navigation (rails maritimes), tourisme (visibilité depuis la côte) et défense (zones militaires). En France, ces conflits se traduisent en recours juridiques qui ajoutent 3 à 4 ans aux délais d'instruction.

Recyclage des pales. Les pales, en composite fibre de verre/résine epoxy,

Recyclage des pales. Les pales, en composite fibre de verre/resine epoxy, représentent 6 à 7 % de la masse de l'éolienne mais sont quasi-impossibles à recycler aux échelles industrielles actuelles. La pyrolyse, le co-processing en cimenterie et les résines thermoplastiques recyclables sont à l'étude. Le chiffre ADEME de « > 90 % de recyclabilité massique » est trompeur : il vaut pour l'acier et le cuivre, qui dominent la masse, mais pas pour les pales.

Démantèlement incomplet. Les fondations posées (monopieux, gravitaires) sont parfois laissées sur place faute de méthode de retrait économique. Le flottant, ancré par câbles, contourne ce problème.

## 7.3 Dépendance aux terres rares et innovations

Les génératrices synchrones à aimants permanents — devenues le standard offshore pour leur fiabilité — utilisent environ 200 kg d'aimants par MW installé, dont près d'un tiers en terres rares (soit ~70 kg de terres rares par MW) : néodyme (Nd) et praséodyme (Pr) pour la base de l'aimant NdFeB, dysprosium (Dy) et terbium (Tb) pour garantir la coercitivité (résistance à la désaimantation thermique). La Chine extrait et raffine 80 à 90 % de ces métaux, ce qui constitue une dépendance stratégique majeure pour l'Europe et un levier d'influence géopolitique potentiel.

Trois pistes d'innovation tentent de réduire cette dépendance. Les génératrices supraconductrices (projets ÉcoSwing, SUPRAPOWER, Air-core) remplacent les aimants permanents par des bobines refroidies, divisant par deux la masse de la génératrice et s'affranchissant des terres rares ; elles restent en phase de prototype. Les paliers magnétiques (Maglev) annulent les frottements de l'arbre par lévitation magnétique, abaissant la vitesse de couplage et augmentant le rendement global. Enfin, l'hydrogène offshore, en développement en Méditerranée, couple directement les éoliennes flottantes à des électrolyseurs pour produire in situ du dihydrogène vert à partir d'eau de mer, contournant ainsi les difficultés de raccordement électrique sur de longues distances.

## 8 Perspectives et conclusion

## 8.1 Objectifs PPE3 et obstacles

La PPE3 publiée en février 2026 vise 3,6 GW installés en 2028, 15 GW en 2035 et 45 GW en 2050 — ce qui ferait de l'éolien en mer la deuxième source d'électricité française après le nucléaire. Pour atteindre 15 GW en 2035, il faudrait raccorder en moyenne 1,2 GW/an à partir de 2025 : un rythme jamais atteint en France (meilleur score : 1,0 GW en 2024). À l'échelle européenne, la Commission vise 60 GW en 2030 et 300 GW en 2050, dont 120 GW concentrés en mer du Nord. Trois obstacles dominent : les délais administratifs (10-12 ans en France, dont 3-4 ans de recours), la saturation du raccordement réseau (500 GW en attente de raccordement en Europe), et les goulets d'étranglement de la chaîne d'approvisionnement (navires d'installation, cables HVDC, fondations).

D'après les modélisations RTE, la stratégie la plus économique pour la France n'est pas un système 100 % renouvelable, mais un mix combinant éolien en mer et nucléaire : ce mix permettrait d'économiser environ 10 milliards d'euros par an par rapport à un scénario tout-renouvelable, qui imposerait des renforcements massifs du réseau de transport et des capacités de stockage.

## 8.2 Synthèse et bilan

L'éolien en mer est une filière en pleine maturation. Sur le plan physique, les marges aérodynamiques sont presque épuisées (80 % de la limite de Betz), et l'essentiel des gains viendra de la taille des turbines (de 6 MW vers 20 MW), du flottant pour exploiter les eaux profondes, et du couplage avec l'hydrogène pour s'affranchir du raccordement. Sur le plan industriel, la baisse des coûts a été spectaculaire ( $ -72\% $ entre 2012 et 2019 sur les appels d'offres français) avant une légère remontée sous l'effet de l'inflation matériaux. Sur le plan stratégique, la dépendance aux terres rares et la concentration chinoise constituent les principales fragilités, partiellement adressables par les génératrices supraconductrices.

Comme pour l'éolien terrestre, les freins ne sont plus principalement techniques mais administratifs et industriels (procédures, raccordement, navires). Le cas britannique montre qu'un mécanisme de soutien stable et pluriannuel (CfD) couplé à une visibilité industrielle peut diviser les coûts par trois en dix ans — c'est cette dynamique que la France cherche à reproduire, avec un atout structurel sur le flottant mediterranéen.

Bilan professionnel. Le stage m'a permis de développer une méthodologie de recherche documentaire (identification et croisement de sources, évaluation de leur fiabilité, repérage des biais éditoriaux comme l'usage de l'Observatoire de l'éolien comme source unique), un esprit critique vis-à-vis des chiffres publiés (notamment sur le LCOE, dont les hypothèses ne sont pas toujours explicites), une pratique approfondie de LaTeX et de Word pour la rédaction scientifique, ainsi que la capacité à produire des documents intermédiaires hebdomadaires intégrant les retours de l'encadrante.

Bilan personnel. Le stage m'a fait découvrir le rythme d'un travail bibliographique encadré : relation à distance avec l'encadrante, allers-retours entre lecture, réflexion et rédaction, autonomie sur une durée courte. Le sujet a été enrichissant : la transition énergétique n'est pas un problème purement technique mais un terrain où la physique rencontre l'économie, l'industrie et la géopolitique. La question centrale n'est plus de savoir si l'éolien en mer fonctionne, mais comment accélérer son déploiement tout en sécurisant la chaîne d'approvisionnement et en maintenant un consensus social.

## Références

- [1] M. Rapin, J.-M. Noël, L'énergie éolienne — Du petit éolien à l'éolien offshore, $ 3^{\mathrm{e}} $ éd., Dunod, 2019.

- [2] M. Rapin, « Éoliennes — Évolution, principes de base et potentiel de conversion », Techniques de l'Ingénieur, BM 4640 v4, 2024.

- [3] GWEC, Global Wind Report 2025.

- [4] WindEurope, Wind energy in Europe 2024 Statistics and outlook 2025-2029.

- [5] RTE, Bilan électrique 2024, février 2025.

- [6] The Crown Estate, Offshore Wind Report 2024.

- [7] KPMG, Panorama de l'éolien français en mer 2025, août 2025.

- [8] DGEC, Programmation Pluriannuelle de l'Énergie (PPE3), février 2026.

- [9] MerEnergies, Rapport OEM 2025 — Suivi des parcs offshore français.

- [10] ADEME, Tout comprendre sur l'éolien, 2024.

- [11] Norton Rose Fulbright, Global offshore wind: UK mechanisms, 2025.

- [12] Observatoire des Énergies Renouvelables (Observ'ER), L'éolien dans le monde, Journal de l'éolien, 2024.

- [13] EurObserv'ER, Production éolienne UE-27, 2024.

- [14] Wikipedia, articles « Éolienne en mer », « Énergie éolienne au Royaume-Uni », « Énergie éolienne en France », consultés en avril 2026.

- [15] Global Wind Atlas v3.3, Technical University of Denmark / ESMAP / Banque mondiale, https://globalwindatlas.info, consulté en avril 2026.

- [16] Journal de l'éolien, cartes des parcs offshore français posés et flottants, https://www.journal-eolien.org, consulté en avril 2026.

- Entretien complémentaire : A. Boujelben, doctorante à l'ITheMM (URCA), 27 mars 2026.

## Annexes

## Annexe A — Carte des vents et gisement éolien

Les cartes de vent monrent que l'écrasante majorité du gisement éolien européen se concentre sur les façades maritimes : mer du Nord, Manche, Atlantique nord, mer Baltique. Pour la France, le gisement marin est particulièrement favorable sur trois façades : la Manche-mer du Nord (vents d'ouest dominants, fonds peu profonds favorables au posé), l'Atlantique (Bretagne sud, Vendée), et la Méditerranée (mistral et tramontane, fonds rapidement profonds favorables au flottant).

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F2026051402380030c62b1370f34e7e%2Fcrop_1_1778697501735.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=wGCB80b1SvmdvVvG0lnx9yb6sqo%3D&Expires=1779302301' alt='OCR图片'/></div>

Annexe A.1 — Vitesse moyenne du vent à 100 m de hauteur en France métropolitaine et Corse. La façade atlantique (Bretagne, Vendée), le Languedoc-Roussillon (tramontane) et la Méditerranée sud (mistral) ressortent comme les zones les plus ventées. Source : Global Wind Atlas v3.3 (DTU / ESMAP / Banque mondiale), consulté en avril 2026.

<table border="1"><tr><td>Zone</td><td>Vitesse moyenne à 100m</td><td>Type d&#x27;éolien adapté</td></tr><tr><td>Mer du Nord, Manche</td><td>9-11m/s</td><td>Posé (monopieu, jacket)</td></tr><tr><td>Atlantique nord (Bretagne)</td><td>8-10m/s</td><td>Posé puis flottant</td></tr><tr><td>Mediterranée(golfe du Lion)</td><td>8-11m/s(rafales)</td><td>Flottant exclusivement</td></tr><tr><td>Plaine intérieure</td><td>5-7m/s</td><td>Terrestre uniquement</td></tr><tr><td>Forêts,milieu urbain</td><td>&lt;5m/s</td><td>Inexploitable</td></tr></table>

Annexe A.2 — Vitesses de vent typiques à 100 m de hauteur en France selon la topographie. Source : Atlas du potentiel éolien, Techniques de l'Ingénieur BE 8400.

À titre indicatif, le potentiel technique français est évalué à 169 GW pour l'éolien posé et 454 GW pour le flottant — un gisement très largement sous-exploité (1,5 GW

<div align="center">

# installés fin 2024). Les cartes A.3 et A.4 ci-dessous précisent la localisation des parcs offshore français — posés et flottants — opérationnels et en projet.

</div>

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F2026051402380030c62b1370f34e7e%2Fcrop_1_1778697501744.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=2sfIvLTCEPXGoZeFrzKzrrkYFIU%3D&Expires=1779302301' alt='OCR图片'/></div>

Annexe A.3 — Carte des parcs éoliens en mer posés en France (opérationnels et en projet). Source : Journal de l'éolien, www.journal-eolien.org.

<div style='text-align: center;'><img src='https://maas-watermark-prod-new.cn-wlcb.ufileos.com/ocr%2Fcrop%2F2026051402380030c62b1370f34e7e%2Fcrop_2_1778697501754.png?UCloudPublicKey=TOKEN_6df395df-5d8c-4f69-90f8-a4fe46088958&Signature=CAUfN8c6AMkoipqQAjXRu%2FdLZR0%3D&Expires=1779302301' alt='OCR图片'/></div>

Annexe A.4 — Carte des parcs éoliens flottants en France (démonstrateurs, pilotes et projets commerciaux). Source : Journal de l'éolien, www.journal-eolien.org.

## Annexe B — Données détaillées : capacités et production offshore

<table border="1"><tr><td>Année</td><td>Cap. mondiale(GW)</td><td>Nouvelles install.(GW)</td><td>Cap. France(GW)</td><td>Production France(TWh)</td></tr><tr><td>2010</td><td>≈3,1</td><td>≈1,2</td><td>0</td><td>0</td></tr><tr><td>2015</td><td>≈12,1</td><td>≈3,4</td><td>0</td><td>0</td></tr><tr><td>2019</td><td>≈28,3</td><td>6,1</td><td>0</td><td>0</td></tr><tr><td>2021</td><td>≈57,0</td><td>21,1</td><td>0</td><td>0</td></tr><tr><td>2022</td><td>≈66,0</td><td>9,0</td><td>0,48</td><td>0,65</td></tr><tr><td>2023</td><td>75,2</td><td>10,9</td><td>0,98</td><td>1,91</td></tr><tr><td>2024</td><td>83,2</td><td>8,0</td><td>1,51</td><td>4,02</td></tr></table>

<div align="center">

Annexe B.1 — Évolution de la capacité offshore mondiale et française, et production française associée. Sources : GWEC 2025, RTE, Wikipedia.

</div>

<table border="1"><tr><td>Horizon</td><td>Objectif PPE3(GW)</td><td>Trajectoire estimée(GW)</td><td>Écart</td></tr><tr><td>Fin 2024(réel)</td><td>—</td><td>1,5</td><td>—</td></tr><tr><td>2028</td><td>3,6</td><td>≈3,0</td><td>-0,6</td></tr><tr><td>2030</td><td>3,6</td><td>≈3,0-4,0</td><td>Atteignable</td></tr><tr><td>2035</td><td>15</td><td>≈7-9</td><td>-6à-8</td></tr><tr><td>2050</td><td>45</td><td>non estimé</td><td>—</td></tr></table>

<div align="center">

Annexe B.2 — Objectifs PPE3 (publiée le 13 février 2026) et trajectoire prévue. Sources : DGEC, MerEnergies 2025, KPMG 2025.

</div>

<table border="1"><tr><td>Pays</td><td>Capacité 2024(GW)</td><td>Production 2024(TWh)</td><td>Part électrique</td></tr><tr><td>Royaume-Uni</td><td>15,9</td><td>52-55</td><td>17%</td></tr><tr><td>Allemagne</td><td>9,0</td><td>27-30</td><td>5-6%</td></tr><tr><td>Pays-Bas</td><td>4,9</td><td>15-17</td><td>6%</td></tr><tr><td>Danemark</td><td>2,7</td><td>9-10</td><td>≈18%</td></tr><tr><td>Belgique</td><td>2,2</td><td>6-7</td><td>7%</td></tr><tr><td>France</td><td>1,5</td><td>4,0</td><td>0,7%</td></tr></table>

<div align="center">

Annexe B.3 — Production offshore par pays européen (2024). Sources : RTE, EurObserv'ER 2024, Wikipedia.

</div>

<div align="center">

Annexe C — Parcs offshore français : opérationnels et en projet

</div>

<table border="1"><tr><td>Parc</td><td>Puissance</td><td>Mise en service</td><td>Statut</td></tr><tr><td>Saint-Nazaire(Banc de Guérande)</td><td>480 MW</td><td>2022</td><td>Opérationnel</td></tr><tr><td>Saint-Brieuc(Ailes Marines)</td><td>496 MW</td><td>2024</td><td>Opérationnel</td></tr><tr><td>Fécamp(Hautes-Falaises)</td><td>497 MW</td><td>2024</td><td>Opérationnel</td></tr><tr><td>Provence Grand Large(flottant)</td><td>25 MW</td><td>2024</td><td>Pilote opérationnel</td></tr></table>

<table border="1"><tr><td>Parc</td><td>Puissance</td><td>Mise en service</td><td>Statut</td></tr><tr><td>Calvados(Courseulles-sur-Mer)</td><td>448 MW</td><td>2025 prévue</td><td>En construction</td></tr><tr><td>Île d&#x27;Yeu-Noirmoutier</td><td>496 MW</td><td>2025 prévue</td><td>En construction</td></tr><tr><td>Dieppe-Le Tréport</td><td>496 MW</td><td>2026 prévue</td><td>En construction</td></tr><tr><td>Dunkerque</td><td>600 MW</td><td>2027 prévue</td><td>En construction</td></tr><tr><td>Centre Manche1</td><td>1000 MW</td><td>2031 prévue</td><td>Attribué(AO4,2023)</td></tr><tr><td>Centre Manche2</td><td>1500 MW</td><td>2032 prévue</td><td>Attribué(AO8,2024)</td></tr><tr><td>Sud Atlantique1</td><td>1000 MW</td><td>2032 prévue</td><td>En procédure</td></tr><tr><td>Sud Atlantique2</td><td>1000 MW</td><td>2034 prévue</td><td>En procédure</td></tr><tr><td>Narbonnaise1(flottant)</td><td>250 MW</td><td>2031 prévue</td><td>Attribuéfin2024</td></tr><tr><td>Golfe de Fos1(flottant)</td><td>250 MW</td><td>2031 prévue</td><td>Attribuéfin2024</td></tr></table>

Annexe C.1 — Inventaire des parcs offshore français opérationnels et en projet (à fin 2024). Sources : Journal de l'éolien, RTE, MerEnergies.

## Annexe D — Schémas de fondations et chaîne de conversion

<div align="center">

Quatre familles de fondations posées et trois familles de fondations flottantes coexistent dans le parc offshore mondial. Le tableau D.1 résume leurs domaines d'emploi.

</div>

<table border="1"><tr><td>Type</td><td>Profondeur</td><td>Domaine d&#x27;emploi</td><td>Exemples</td></tr><tr><td>Monopieu(posé)</td><td>0-40m</td><td>Fonds sableux, mer du Nord</td><td>Saint-Nazaire,Fécamp</td></tr><tr><td>Jacket(posé)</td><td>30-60m</td><td>Fonds rocheux,courants forts</td><td>Saint-Brieuc</td></tr><tr><td>Gravitaire(posé)</td><td>0-30m</td><td>Fonds plats préparés</td><td>Middelgrunden(DK)</td></tr><tr><td>Semi-submersible(flot.)</td><td>&gt;50m</td><td>Le plus polyvalent en flottant</td><td>Provence Grand Large</td></tr><tr><td>SPAR(flottant)</td><td>&gt;100m</td><td>Eaux très profondes</td><td>Hywind Scotland</td></tr><tr><td>TLP(flottant)</td><td>50-200m</td><td>Stabilité maximale</td><td>Prototypes</td></tr><tr><td>Barge(flottant)</td><td>&gt;30m</td><td>Démonstrateurs simples</td><td>Floatgen(Le Croisic)</td></tr></table>

<div align="center">

Annexe D.1 — Domaines d'emploi des principaux types de fondations offshore. Sources : Journal de l'éolien, GWEC, EDF R&D.

</div>

La chaîne de conversion comprend cinq étages : (1) le rotor (pales en compositevrillées) ; (2) la nacelle, avec multiplicateur + génératrice asynchrone, ou génératrice synchrone à aimants permanents en entraînement direct (Direct Drive, standard offshore) ; (3) un convertisseur électronique synchronisant la fréquence du rotor avec celle du réseau (50 Hz) ; (4) un transformateur en pied de mât (33-66 kV) ; (5) une sous-station offshore élevant à 220-400 kV pour le transit sous-marin. Au-delà de 100 km, la solution HVDC est privilégiée car elle élimine les pertes capacitives — appelée à se généraliser avec le far-shore.