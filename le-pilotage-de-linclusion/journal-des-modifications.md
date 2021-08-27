---
description: Journal des modifications du pilotage de l'inclusion
---

# Journal des modifications

## Du 16/08/2021 au 26/08/202

* Automatisation du script qui permet d'avoir un suivi des structures qui sur-conrsomment/sous-consomment les ETP
* Automatisation du script qui permet d'avoir un suivi par structure du nombre d'heures travaillées par les salariés en insertion et le nombre d'ETP consommés
* Automatisation du script qui permet aux DDETS  d'avoir un suivi en temps réel du retard que les structures prennent dans la saisie des données mensuelles dans l'extranet ASP
* Automatisation du script qui permet  de retravailler les colonnes de la table ASP "fluxIAE\_AnnexeFinanciere": récupérer le type de structure de la colonne af.af\_mesure\_dispositif\_code \(ex : ACI\_DC\) + retraiter les variables dates qui sont au format string dans la table source
* Automatisation du script qui permet  de rajouter le nom du département et la région de la structure à la table ASP "fluxIAE\_Structure"
* Ajout du bas de page dans le TB88 avec le lien vers le glossaire et la date de mise à jour des données
* Correction d'un bug sur le tableau "Détail des critères de niveau 2" du TB32
* Affichage du numéro de convention en plus de la dénomination de la structure au niveau de la question  'suivi des saisies mensuelles des structures dans l'ASP' du TB88
* Finalisation du script qui permet de récupérer le nom du département à partir du numéro de convention
* Ajout de la section [tableaux de bord](les-tableaux-de-bord-disponibles.md) dans la documentation
* Correction d'un bug sur les filtres dans le TB52
* refonte du [glossaire](../glossaire-inclusion.md) des acronymes de l'inclusion dans l'espace documentation
* intégration de l'opération restauration dans le script qui met à jour le tableau de bord TB60
* ajout de l'opération AI RESTO et ETTI RESTO dans le tableau de bord TB60
* ajout du tableau "Profil des candidats recrutés" dans le TB52
* ajout du [dictionnaire des indicateurs](dictionnaire-des-indicateurs.md) dans l'espace documentation

## 26/08/2021

* Automatisation du script qui permet d'avoir un suivi des structures qui sur-conrsomment/sous-consomment les ETP

## 24/08/2021

* Ajout du bas de page dans le TB88 avec le lien vers le glossaire et la date de mise à jour des données
* Automatisation du script qui permet d'avoir un suivi par structure du nombre d'heures travaillées par les salariés en insertion et le nombre d'ETP consommés

## 23/08/2021

* Correction d'un bug sur le tableau "Détail des critères de niveau 2" du TB32
* Automatisation du script qui permet aux DDETS  d'avoir un suivi en temps réel du retard que les structures prennent dans la saisie des données mensuelles dans l'extranet ASP
* Affichage du numéro de convention en plus de la dénomination de la structure au niveau de la question  'suivi des saisies mensuelles des structures dans l'ASP' du TB88 

## 20/08/2021

* Finalisation du script qui permet de récupérer le nom du département à partir du numéro de convention
* Automatisation du script qui permet  de retravailler les colonnes de la table ASP "fluxIAE\_AnnexeFinanciere": récupérer le type de structure de la colonne af.af\_mesure\_dispositif\_code \(ex : ACI\_DC\) + retraiter les variables dates qui sont au format string dans la table source

## 19/08/2021

* Ajout de la section [tableaux de bord](les-tableaux-de-bord-disponibles.md) dans la documentation
* Correction d'un bug sur les filtres dans le TB52
* Automatisation du script qui permet  de rajouter le nom du département et la région de la structure à la table ASP "fluxIAE\_Structure"

## 18/08/2021

* refonte du [glossaire](../glossaire-inclusion.md) des acronymes de l'inclusion dans l'espace documentation
* intégration de l'opération restauration dans le script qui met à jour le tableau de bord TB60
* ajout de l'opération AI RESTO et ETTI RESTO dans le tableau de bord TB60
* ajout du tableau "Profil des candidats recrutés" dans le TB52
* ajout du [dictionnaire des indicateurs](dictionnaire-des-indicateurs.md) dans l'espace documentation

## 05/07/2021

* Ajout du champ BRSA dans la table Organisations.
* Ajout du champ id\_asp dans la table Structures.
* Accès sécurisé via le C1  pour les CD de France aux tableaux de bord Metabase avec les  données de leur département.
* Évolutions dans les TDB consultables  par le CD93 et la DRIEETS 93:
  * Ajout d’un sommaire
  *  Ajout de clé de lecture sur certains graphiques pour accompagner les utilisateurs dans les analyses
  * Ajout de l’indicateur  “nombre de salariés en insertion qui ont travaillé dans les structures durant l’année “  décliné par type de structures et par genre du salarié
* Ajout du filtre ‘Année’ dans le TDB consultable par le CD93

## 18/06/2021

* Construction d’un TDB qui présente l’évolution du nombre de créations et fermetures de structures par département /région et type de structure.
* Construction d’un tableau de bord qui fait un focus sur les métiers de restauration avec possibilité de filtrer par région/département du salarié et type de structure.
* Construction d’un tableau de bord qui fait un focus sur les métiers forestiers avec possibilité de filtrer par région/département du salarié et type de structure.
* Construction d’un TDB avec la  cartographie  du nombre de salariés en insertion en Ile de France  qui montre les zones blanches /grises avec possibilité de filtrer par région /département du salarié ,type de structure et tranche du nombre de salarié. 
*  Amélioration apportée au tableau de bord consultable par le CD93 : utilisation de l’adresse de gestion pour récupérer la commune de la structure  au lieu de l’adresse administrative. 
* Montée en version de Metabase avec 3 nouvelles fonctionnalités : tableaux croisés dynamiques, possibilité de lier les différents filtres, affichage des volumes au-dessus des histogrammes.
* Ajout de la table ASP  fluxiae\_AnnexeFinanciereACI.

## 04/06/2021

* Ajout de la table fiches de poste par candidature qui permet de relier la table fiches de poste et la table candidatures 
* Ajout de 3 tables ASP : fluxIAE\_PMSMP / fluxIAE\_Formations  /fluxIAE\_Encadrement/fluxIAE\_EtatMensuelAgregat
* Ajout d'une table avec le volume des DELD et DETLD par département
* Construction du TDB "Personnes en insertion versus DELD / DETLD TB94
* Développement d'une requête SQL qui permet pour un salarié ayant travaillé dans plusieurs structures différentes dans mois m d'avoir la concaténation des 2 structures dans le champs "type de structure". Exemple

  ![](https://lh5.googleusercontent.com/oGK3mY3OT08P0s077RwrRoXq9x-xWbjOQR7duuWnG89UtCIlWypyJyCI_jHrECZfQ9tryBgDJGSuFLDpuybIDogYbrSEFwRXe5ysD5-zLxm36CpsTXeVa4w)

* Ajout du nombre de CIP par structure dans le TDB construit pour le département
* Construction d'une première version du TDB sur la rapidité des recrutements TB98
* Ajout au TDB consultable par la DRIEETS :
  1. Question qui met en avant le structure avec une surconsommation d'ETP
  2. Question qui met en avant le structure avec une sous-consommation d'ETP
  3. Question qui affiche les structures qui n'ont pas saisi leurs données dans l'ASP

## 07/05/2021

* Ajout de la colonne date de création de la fiche de poste dans la table "Fiches de poste"
* Construction  d'un TDB sur "Les métiers les plus recherchés et les plus proposés" TB90
* Ajout dans le TDB "Indicateurs des chantiers" des statistiques sur le nombre moyen de candidatures avant l'embauche.
* Construction d'un TDB "Personnes recrutées en auto prescription" qui concerne les critères remplis par les personnes recrutées en auto-prescription TB32
* Construction d'un TDB consultable par la DRIEETS et qui se base sur les données ASP TB88

## 25/04/2021

* Ajout du Référentiel établissement public territorial  \(EPT\)
* Ajout du Référentiel établissement public de coopération intercommunale \(EPCI\)
* Ajout de la  table des Demandeurs d’emploi inscrits en fin de mois à Pôle emploi :
  * pour Février 2021  /Catégorie : A et B et C
  * par commune de plus de 5000 hab. /Ancienneté d’inscription 
* Construction d’une table mission agrégée concernant les déclarations mensuelles : une ligne par état mensuel individuel et qui contient les données suivantes :

  ![](https://lh3.googleusercontent.com/75CFuee7Zv7UK0mjsV_TEIafxYHoTPcP_r_gJX5rZzrEk0uoII0eNStw3sA4IHcYWrvinXOe1RfTHD_-2JrZKXBU0ISMcG8q9XJENhvm2wjTwNZNnbLSeXw)

* Ajout de 13 filtres \(axes d’analyse\) dans le Reporting pour l’expérimentation du 93 \(TB78\)

  ![](https://lh6.googleusercontent.com/A-iIY9a4zXJ3hnIJCkobVICxw2s8AB2l92w-NZzmaNIXu7exCj-5uECsoFhgV0MY17RyUeC_Yr_DMO62d3mRy7uOLIybZKPdcFF63dfNsTj2qSzBpKDAKH4)

  ![](https://lh6.googleusercontent.com/zrTjWPP4cHyBaWe0j4PyEOFv1-KKv33Ta-23FbHrFkLY-8PPB2Tx6SmXiWFFvLJAqn2LWvMzEuCNgPMDQtkvZ7kmX2DbPZK0mt8XwQokTRsDjq5_XJBMY9U)

## 09/04/2021

* Ajout d’un nouveau champ "total candidatures" dans la table "fiches de poste" sur Métabase
* Ajout des 28 référentiels fluxIAE \(données ASP\)
* Ajout de la table “commune” qui permet à partir du  code insee de récupérer la latitude et longitude.

## 12/03/2021



* Ajout des départements et régions dans metabase

![image](https://lh6.googleusercontent.com/8_PZB6gDzxiXxObFQSFmn4agDTUcffIXAc_2S-FAHI-3wb5mD08wrguoWZqAKFEHbVgz9LjX6HlqmI3Iyo3I0_hGMrK86eThJ_UOy9FFbn2LiG9u2pGmzeU)

* Ajout d'une nouvelle table fiches de poste dans metabase

![image](https://lh6.googleusercontent.com/yqfpEwrwj9jpoiVkvBwuPXM28bEOtBloPq4k0uvfmLGU4CA9IOzU6lN-uBXhmxEH-Zl9f7PpNMmuoE96kPjIgSwn267Vtu47n-8yQMf3nNaNpBvo-TDobOA)

## 26/02/2021

* Création de ce changelog
* Metabase : ajout de trois colonnes à la table Organisations \(date\_dernière\_candidature, latitude et longitude\) et transformation de la colonne temps\_écoulé\_depuis\_dernière\_candidature en date\_dernière\_candidature
* Metabase : ajout de deux colonnes à la table Candidatures \(nom\_org\_prescripteur et safir\_org\_prescripteur\)

