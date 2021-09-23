---
description: Liste de tous les indicateurs présentés dans l'ensemble des tableaux de bord
---

# Dictionnaire des indicateurs

{% hint style="info" %}
_N'hésitez pas à consulter le_ [_Glossaire_](../glossaire-inclusion.md) _si vous avez un doute sur un terme_
{% endhint %}

## Employeurs

### Nombre d'employeurs inscrits

* 📗 **Définition** : Nombre de structures 'employeurs' ayant activé leur compte sur les emplois de l'inclusion
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre total d'employeurs dont la date d'inscription est non vide
* 📊 **Présent dans** : [TB54](les-tableaux-de-bord-disponibles.md#employeurs), [TB34](les-tableaux-de-bord-disponibles.md#statistiques-des-emplois-de-linclusion), [TB43](les-tableaux-de-bord-disponibles.md#statistiques-avancees-des-emplois-de-linclusion)

### Nombre d'employeurs inscrits \(yc antennes\)

* 📗 **Définition** : Nombre de structures 'employeurs' ayant activé leur compte sur les emplois de l'inclusion, en comptant les antennes que ces employeurs ont créé sur les emplois de l'inclusion. Un employeur a la possibilité de créer des antennes pour indiquer le lieu d'embauche
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre total d'employeurs dont la date d'inscription est non vide + nombre d'antennes que ces employeurs ont créé
* 📊 **Présent dans** : [TB54](les-tableaux-de-bord-disponibles.md#employeurs)

### Pourcentage d'employeurs avec au moins un poste ouvert

* 📗 **Définition** : Pourcentage d'employeurs qui ont activé au moins une offre de poste sur les emplois de l'inclusion à l'instant t
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre d'employeurs avec au moins une offre de poste active divisé par le nombre total d'employeurs, rapporté en base 100
* 📊 **Présent dans** : [TB54](les-tableaux-de-bord-disponibles.md#employeurs)

### Pourcentage d'employeurs ayant embauché dans les 30 derniers jours

* 📗 **Définition** : Pourcentage d'employeurs qui ont embauché au moins une personne via les emplois de l'inclusion dans les 30 derniers jours
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre d'employeurs ayant accepté au moins une candidature dans les 30 derniers jours divisé par le nombre total d'employeurs, rapporté en base 100
* 📊 **Présent dans** : [TB54](les-tableaux-de-bord-disponibles.md#employeurs)

## Prescripteurs

### Nombre de prescripteurs inscrits

* 📗 **Définition** : Nombre de structures 'prescripteurs habilités' ou 'orienteurs' ayant enregistré leur structure sur les emplois de l'inclusion
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre total de prescripteurs habilités et d'orienteurs dont la date d'inscription est non vide
* 📊 **Présent dans** : [TB34](les-tableaux-de-bord-disponibles.md#statistiques-des-emplois-de-linclusion), [TB43](les-tableaux-de-bord-disponibles.md#statistiques-avancees-des-emplois-de-linclusion), [TB52](les-tableaux-de-bord-disponibles.md#prescripteurs)

### Pourcentage de prescripteurs habilités

* 📗 **Définition** : Part des prescripteurs habilités parmi les prescripteurs inscrits \([à propos des prescripteurs habilités](../qui-est-eligible-iae-criteres-eligibilite/)\)
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre de prescripteurs habilités inscrits divisé par le nombre total de prescripteurs habilités et d'orienteurs dont la date d'inscription est non vide, ramené en base 100
* 📊 **Présent dans** : [TB52](les-tableaux-de-bord-disponibles.md#prescripteurs)

### Part du SPE

* 📗 **Définition** : Part du SPE parmi les prescripteurs inscrits
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre de prescripteurs de type 'Pôle emploi', 'CAP emploi' ou 'Mission locale' inscrits divisé par le nombre total de prescripteurs habilités et d'orienteurs dont la date d'inscription est non vide, ramené en base 100
* 📊 **Présent dans** : [TB52](les-tableaux-de-bord-disponibles.md#prescripteurs)

### Nombre d'établissements

* 📗 **Définition** : Nombre d'établissements de Prescripteurs
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre total de prescripteurs habilités et d'orienteurs dont la date d'inscription est non vide
* 📊 **Présent dans** : [TB52](les-tableaux-de-bord-disponibles.md#prescripteurs)

### Nombre de conseillers

* 📗 **Définition** : Nombre d'utilisateurs des emplois de l'inclusion travaillant chez un prescripteur habilité ou un orienteur
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : x
* 📊 **Présent dans** : [TB52](les-tableaux-de-bord-disponibles.md#prescripteurs)

## Candidatures, embauches et pass IAE

### Nombre de candidatures

* 📗 **Définition** : Nombre de candidatures reçues par les employeurs sur les emplois de l'inclusion
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre total des candidatures
* 📊 **Présent dans** : [TB34](les-tableaux-de-bord-disponibles.md#statistiques-des-emplois-de-linclusion), [TB43](les-tableaux-de-bord-disponibles.md#statistiques-avancees-des-emplois-de-linclusion), [TB54](les-tableaux-de-bord-disponibles.md#employeurs)

### Origine des candidatures

* 📗 **Définition** : Organisation ou personne à l'origine des candidatures
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Répartition des candidatures selon l'organisation ou la personne qui en est à l'origine \(candidat, orienteur, prescripteur habilité, employeur\)
* 📊 **Présent dans** : [TB54](les-tableaux-de-bord-disponibles.md#employeurs)

### Nombre de candidatures dans les 7 derniers jours

* 📗 **Définition** : Nombre de candidatures reçues par les employeurs sur les emplois de l'inclusion dans les 7 derniers jours qui précèdent la mise à jour de données du tableau de bord
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre total des candidatures dont la date de candidature est comprise entre aujourd'hui et aujourd'hui - 7 jours
* 📊 **Présent dans** : [TB34](les-tableaux-de-bord-disponibles.md#statistiques-des-emplois-de-linclusion)

### Nombre de candidats

* 📗 **Définition** : Nombre de candidats ayant postulé directement, via un prescripteur ou via un employeur sur les emplois de l'inclusion
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre total de candidats avec au moins une candidature
* 📊 **Présent dans** : [TB52](les-tableaux-de-bord-disponibles.md#prescripteurs)

### Nombre d'embauches

* 📗 **Définition** : Nombre de candidatures acceptées par les employeurs sur les emplois de l'inclusion
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre total des candidatures dont le statut est 'acceptée'
* 📊 **Présent dans** : [TB34](les-tableaux-de-bord-disponibles.md#statistiques-des-emplois-de-linclusion), [TB43](les-tableaux-de-bord-disponibles.md#statistiques-avancees-des-emplois-de-linclusion)

### Nombre de personnes embauchées

* 📗**Définition** : Nombre de personnes embauchées via les emplois de l'inlcusion
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre de candidats dont au moins une candidature a été acceptée
* 📊 **Présent dans** : [TB54](les-tableaux-de-bord-disponibles.md#employeurs)

### Pourcentage de candidats embauchés parmi ceux orientés par des prescripteurs

* 📗 **Définition** : Pourcentage de candidats embauchés parmi ceux orientés par des prescripteurs
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre de candidats orientés par un prescripteur et dont au moins une candidature a été acceptée divisé par le nombre total de candidats orientés par des prescripteurs, ramené en base 100
* 📊 **Présent dans** : [TB52](les-tableaux-de-bord-disponibles.md#prescripteurs)

### Profil des personnes orientées

* 📗 **Définition** : Pour chacun des critères administratifs principaux, part des personnes relevant de ce critère parmi les personnes orientées
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Pour chacun des critères, nombre de personnes orientées par un prescripteur et pour lesquels ce critère est coché, divisé par le nombre total de personnes embauchées, rapporté en base 100
* 📊 **Présent dans** : [TB52](les-tableaux-de-bord-disponibles.md#prescripteurs)

### Profil des personnes embauchées

* 📗 **Définition** : Pour chacun des critères administratifs principaux, part des personnes relevant de ce critère parmi les personnes embauchées
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Pour chacun des critères, nombre de personnes embauchées et pour lesquels ce critère est coché, divisé par le nombre total de personnes embauchées, rapporté en base 100
* 📊 **Présent dans** : [TB54](les-tableaux-de-bord-disponibles.md#employeurs), [TB52](les-tableaux-de-bord-disponibles.md#prescripteurs)

### Nombre d'embauches dans les 7 derniers jours

* 📗 **Définition** : Nombre de candidatures acceptées par les employeurs sur les emplois de l'inclusion dans les 7 derniers jours qui précèdent la mise à jour de données du tableau de bord
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre total des candidatures dont le statut est 'acceptée' et dont la date de candidature est comprise entre aujourd'hui et aujourd'hui - 7 jours
* 📊 **Présent dans** : [TB34](les-tableaux-de-bord-disponibles.md#statistiques-des-emplois-de-linclusion)

### Part des employeurs qui ont reçu au moins une candidature

* 📗 **Définition** : Pourcentage des employeurs qui ont reçu au moins une candidature
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre d'employeurs qui ont reçu au moins une candidature, divisé par le nombre d'employeurs inscrits, ramené en base 100.
* 📊 **Présent dans** : [TB34](les-tableaux-de-bord-disponibles.md#statistiques-des-emplois-de-linclusion)

### Nombre de pass IAE

* 📗 **Définition** : Nombre de pass IAE délivrés sur les emplois de l'inclusion
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre de pass IAE délivrés suite à une déclaration d'éligibilité par un prescripteur habilité ou un employeur et suite à l'acceptation de la candidature par l'employeur
* 📊 **Présent dans** : [TB43](les-tableaux-de-bord-disponibles.md#statistiques-avancees-des-emplois-de-linclusion)

### Pass IAE versus agrément Pôle emploi

* 📗 **Définition** : Répartition des entrées en IAE selon que la personne a reçu un pass IAE \(délivré par les emplois de l'inclusion\) ou un agrément délivré par Pôle emploi - Taux de pénétration des emplois de l'inclusion
* 💾 **Source des données** : emplois de l'inclusion et Pôle emploi
* 🧮 **Formule** : Nombre de pass IAE délivrés sur une période, divisé par la somme du nombre de pass IAE et du nombre d'agrément PE délivrés pendant la même période
* 📊 **Présent dans** : [TB34](les-tableaux-de-bord-disponibles.md#statistiques-des-emplois-de-linclusion)

## Auto-prescription

### Recrutements en auto-prescription

* 📗 **Définition** : La part des candidatures acceptées initiées par l'employeur parmi toutes les embauches faites par les SIAE
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Somme des candidatures acceptées initiées par les employeurs de type SIAE divisée par le nombre total des embauches \(initiés par l'employeur, par un prescripteur ou par le candidat lui-même\) dans les structures de type SIAE
* 📊 **Présent dans** : [TB34](les-tableaux-de-bord-disponibles.md#statistiques-des-emplois-de-linclusion), [TB43](les-tableaux-de-bord-disponibles.md#statistiques-avancees-des-emplois-de-linclusion)

### Nombre de personnes concernées par l'autoprescription

* 📗 **Définition** : Nombre de personnes dont l'éligibilité a été validée par une SIAE dans le cadre de l'autoprescription
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre de candidats embauchés et dont l'éligibilité a été validée par une SIAE
* 📊 **Présent dans** : [TB32](les-tableaux-de-bord-disponibles.md#criteres)

### Nombre de critères de niveau 1

* 📗 **Définition** : Nombre critères de niveau 1 sélectionnés par la SIAE dans le cadre de l'autoprescription pour valider l'éligibilité d'une personne \([rappel sur les règles](../qui-est-eligible-iae-criteres-eligibilite/)\)
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Pour chaque personne embauchée en autoprescription, décompte du nombre de critères niveau 1 cochés par la SIAE \(de 0 à 4 car il y a 4 critères de niveau 1\)
* 📊 **Présent dans** : [TB32](les-tableaux-de-bord-disponibles.md#criteres)

### Nombre de personnes recrutées en autoprescription sur la base de critères de niveau 1

* 📗 **Définition** : Nombre de personnes dont l'éligibilité a été validée par une SIAE dans le cadre de l'autoprescription sur la base de critères de niveau 1 \([rappel sur les règles](../qui-est-eligible-iae-criteres-eligibilite/)\)
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Pour chaque personne embauchée en autoprescription, décompte du nombre de cas où au moins 1 critère de niveau 1 a été coché par la SIAE
* 📊 **Présent dans** : [TB32](les-tableaux-de-bord-disponibles.md#criteres)

### Nombre de personnes recrutées en autoprescription sur la base de critères de niveau 2

* 📗 **Définition** : Nombre de personnes dont l'éligibilité a été validée par une SIAE dans le cadre de l'autoprescription sur la base de critères de niveau 2 \([rappel sur les règles](../qui-est-eligible-iae-criteres-eligibilite/)\)
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Pour chaque personne embauchée en autoprescription, décompte du nombre de cas où aucun critère de niveau 1 n'a été coché par la SIAE, ce qui veut dire obligatoirement que ce sont les critères de niveau 2 qui sont pris en compte
* 📊 **Présent dans** : [TB32](les-tableaux-de-bord-disponibles.md#criteres)

### Nombre de critères de niveau 2

* 📗 **Définition** : Nombre critères de niveau 2 sélectionnés par la SIAE dans le cadre de l'autoprescription pour valider l'éligibilité d'une personne \([rappel sur les règles](../qui-est-eligible-iae-criteres-eligibilite/)\)
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Pour chaque personne embauchée en autoprescription dont le nombre de critères de niveau 1 cochés est égale à 0, décompte du nombre de critères niveau 2 cochés par la SIAE \(de 2 à 11 car il y a 11 critères de niveau 2\)
* 📊 **Présent dans** : [TB32](les-tableaux-de-bord-disponibles.md#criteres)

## Postes et métiers

### Nombre de postes proposés

* 📗 **Définition** : Nombre de postes proposés par les employeurs sur les emplois de l'inclusion à un instant t
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Nombre de fiches de postes actives
* 📊 **Présent dans** : [TB54](les-tableaux-de-bord-disponibles.md#employeurs)

### Métiers les plus proposés par les employeurs

* 📗 **Définition** : métiers les plus proposés par les employeurs sur les emplois de l'inclusion, basés sur le code rome indiqué par l'employeur dans la fiche de poste
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : nombre de fois où un code rome apparait dans les fiches de postes, classé de manière décroissante
* 📊 **Présent dans** : [TB90](les-tableaux-de-bord-disponibles.md#metiers-de-linclusion)

### Métiers les plus demandés par les candidats

* 📗 **Définition** : métiers les plus demandés par les candidats sur les emplois de l'inclusion, basés sur le code rome indiqué dans la fiche de poste à laquelle le candidat postule
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : nombre de fois où un code rome apparait dans les candidatures, classé de manière décroissante
* 📊 **Présent dans** : [TB90](les-tableaux-de-bord-disponibles.md#metiers-de-linclusion)

### Métiers recevant le plus de candidatures \(ration nb candidatures / poste\)

* 📗 **Définition** : métiers recevant le plus de candidature, rapporté au nombre de fiches de poste proposés
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : nombre de candidatures à des fiches de poste rattachées à un code rome donné, divisé par nombre de fiches de poste correspondant
* 📊 **Présent dans** : [TB90](les-tableaux-de-bord-disponibles.md#metiers-de-linclusion)

## Opérations spéciales avec les AI et les ETTI

### Chiffres déclarés : missions

* 📗 **Définition** : nombre de missions déclarées par les SIAE sur les opérations spéciales dans l'extranet IAE de l'ASP
* 💾 **Source des données** : ASP
* 🧮 **Formule** : décompte du nombre de missions pour lesquelles le code opération \(ex : AIEHPAD, AIPH, AI RESTO, ETTI RESTO\) est saisi dans le champ description
* 📊 **Présent dans** : [TB60](les-tableaux-de-bord-disponibles.md#suivi-des-operations-de-soutien-aux-metiers-en-tension)

### Chiffres déclarés : heures

* 📗 **Définition** : nombre d'heures de travail déclarées par les SIAE sur les opérations spéciales dans l'extranet IAE de l'ASP
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : total du nombre d'heures travaillées déclarées dans des missions pour lesquelles le code opération \(ex : AIEHPAD, AIPH, AI RESTO, ETTI RESTO\) est saisi dans le champ description
* 📊 **Présent dans** : [TB60](les-tableaux-de-bord-disponibles.md#suivi-des-operations-de-soutien-aux-metiers-en-tension)

### Chiffres déclarés : répartition des heures par semaine

* 📗 **Définition** : nombre d'heures de travail déclarées par les SIAE sur les opérations spéciales dans l'extranet IAE de l'ASP, heures présentées par semaine pendant laquelle la déclaration a été faite
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : total du nombre d'heures travaillées déclarées dans des missions pour lesquelles le code opération \(ex : AIEHPAD, AIPH, AI RESTO, ETTI RESTO\) est saisi dans le champ description, heures regroupées par semaine sur la base de la date de saisie
* 📊 **Présent dans** : [TB60](les-tableaux-de-bord-disponibles.md#suivi-des-operations-de-soutien-aux-metiers-en-tension)

### Chiffres déclarés : SIAE

* 📗 **Définition** : nombre de SIAE qui ont déclaré au moins une mission sur les opérations spéciales dans l'extranet IAE de l'ASP
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : décompte du nombre de SIAE qui ont déclaré des missions pour lesquelles le code opération \(ex : AIEHPAD, AIPH, AI RESTO, ETTI RESTO\) est saisi dans le champ description
* 📊 **Présent dans** : [TB60](les-tableaux-de-bord-disponibles.md#suivi-des-operations-de-soutien-aux-metiers-en-tension)

### Chiffres établis sur les suivis mensuels validés : missions

* 📗 **Définition** : nombre de missions déclarées par les SIAE sur les opérations spéciales dans l'extranet IAE de l'ASP et pour lesquelles le suivi mensuel a été validé par l'ASP
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : décompte du nombre de missions pour lesquelles le code opération \(ex : AIEHPAD, AIPH, AI RESTO, ETTI RESTO\) est saisi dans le champ description et pour lesquelles le champ "Etat saisie" est "valide"
* 📊 **Présent dans** : [TB60](les-tableaux-de-bord-disponibles.md#suivi-des-operations-de-soutien-aux-metiers-en-tension)

### Chiffres établis sur les suivis mensuels validés : heures

* 📗 **Définition** : nombre d'heures de travail déclarées par les SIAE sur les opérations spéciales dans l'extranet IAE de l'ASP et pour lesquelles le suivi mensuel a été validé par l'ASP
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : total du nombre d'heures travaillées déclarées dans des missions pour lesquelles le code opération \(ex : AIEHPAD, AIPH, AI RESTO, ETTI RESTO\) est saisi dans le champ description et pour lesquelles le champ "Etat saisie" est "valide"
* 📊 **Présent dans** : [TB60](les-tableaux-de-bord-disponibles.md#suivi-des-operations-de-soutien-aux-metiers-en-tension)

### Chiffres établis sur les suivis mensuels validés : SIAE

* 📗 **Définition** : nombre de SIAE qui ont déclaré au moins une mission sur les opérations spéciales dans l'extranet IAE de l'ASP et pour lesquelles le suivi mensuel a été validé par l'ASP
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : décompte du nombre de SIAE qui ont déclaré des missions pour lesquelles le code opération \(ex : AIEHPAD, AIPH, AI RESTO, ETTI RESTO\) est saisi dans le champ description et pour lesquelles le champ "Etat saisie" est "valide"
* 📊 **Présent dans** : [TB60](les-tableaux-de-bord-disponibles.md#suivi-des-operations-de-soutien-aux-metiers-en-tension)

### Chiffres établis sur les suivis mensuels validés : personnes

* 📗 **Définition** : nombre de salariés en insertion déclarés par les SIAE sur les opérations spéciales dans l'extranet IAE de l'ASP et pour lesquelles le suivi mensuel a été validé par l'ASP
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : décompte du nombre de personnes déclarées dans des missions pour lesquelles le code opération \(ex : AIEHPAD, AIPH, AI RESTO, ETTI RESTO\) est saisi dans le champ description et pour lesquelles le champ "Etat saisie" est "valide"
* 📊 **Présent dans** : [TB60](les-tableaux-de-bord-disponibles.md#suivi-des-operations-de-soutien-aux-metiers-en-tension)

### Chiffres établis sur les suivis mensuels validés : répartition des heures par mois

* 📗 **Définition** : nombre d'heures de travail déclarées par les SIAE sur les opérations spéciales dans l'extranet IAE de l'ASP et pour lesquelles le suivi mensuel a été validé par l'ASP, heures présentées par mois pendant lequel les heures ont été travaillées
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : total du nombre d'heures travaillées déclarées dans des missions pour lesquelles le code opération \(ex : AIEHPAD, AIPH, AI RESTO, ETTI RESTO\) est saisi dans le champ description et pour lesquelles le champ "Etat saisie" est "valide", heures regroupées par mois pendant lequel les heures ont été travaillées
* 📊 **Présent dans** : [TB60](les-tableaux-de-bord-disponibles.md#suivi-des-operations-de-soutien-aux-metiers-en-tension)

## Recrutements, salariés en insertion et sorties

### Recrutements

* 📗 **Définition** : nombre distinct de salariés recrutés en insertion déclarés par les SIAE dans l'extranet IAE de l'ASP
* 💾 **Source des données** : ASP
* 🧮 **Formule** : total du nombre des salariés distincts recrutés dans les SIAE
* 📊 **Présent dans** : TB88, TB100

### Nombre de salariés en insertion

* 📗 **Définition** : nombre de salariés distincts déclarés comme ayant travaillé en IAE par l'ensemble des SIAE dans l'extranet ASP
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : total du nombre de salariés déclarés par les SIAE comme ayant travaillé au moins une heure dans la période considérée
* 📊 **Présent dans** : TB88, TB100

### Nombre d'heures travaillées

* 📗 **Définition** : nombre d'heures travaillées par les salariés en insertion déclarées par l'ensemble des SIAE mensuellement sur l'extranet ASP 
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : somme des heures travaillées par les salariés des SIAE dans la période considérée
* 📊 **Présent dans** : TB88, TB100

### Moyenne des ETP consommés depuis le début de l'année

* 📗 **Définition** : moyenne des équivalents temps plein consommés depuis le début de l'année en cours
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : si le dernier mois saisi par la structure dans l'ASP est le mois de février 2021, la moyenne du nombre d'ETP consommés depuis le début de l'année est la somme du nombre d'ETP consommés en janvier 2021 auquel on rajoute le nombre d'ETP consommés en février 2021, le tout divisé par 2 tel que 2 est le nombre de mois écoulés depuis le début de l'année en cours
* 📊 **Présent dans** : TB88

### Dernier mois saisi dans l'ASP

* 📗 **Définition** : le mois de la dernière déclaration mensuelle faite par la SIAE sur l'extranet ASP
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : le mois le plus récent avec une saisie sur l'extranet ASP
* 📊 **Présent dans** : TB88

### Nombre de sorties

* 📗 **Définition** : nombre de salariés en insertion déclarés dans l'extranet ASP comme ayant quitté la structure vers une des différentes catégories de sorties \(emploi durable, emploi de transition, sorties positives, autres sorties\) 
* 💾 **Source des données** : Agence de services et de paiement
* 🧮 **Formule** : nombre de salarié avec une catégorie de sortie renseignée dans l'ASP
* 📊 **Présent dans** : TB88, TB100

## Accompagnement des salariés en insertion

### Nombre de conseillers en insertion professionnelle

* 📗 **Définition** : nombre de salariés permanents déclarés par les SIAE dans l'extranet IAE de l'ASP s'occupant de l'accompagnement socio-professionnel des salariés en insertion
* 💾 **Source des données** : ASP
* 🧮 **Formule** : total du nombre des conseillers en insertion professionnelle
* 📊 **Présent dans** : TB100

## Tensions de recrutement

### Evolution des candidatures par état

* 📗 **Définition** : Évolution mois par mois de toutes les candidatures, présentées par état de la candidature \(à l'étude, acceptée...\)
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Décompte de toutes les candidatures de la période considérée, regroupées par mois \(sur la base de la date de candidature\), puis par état à l'intérieur d'un mois
* 📊 **Présent dans** : [TB116](les-tableaux-de-bord-disponibles.md#recrutement)

### Evolution des candidatures par type d'orienteur

* 📗 **Définition** : Évolution mois par mois de toutes les candidatures, présentées par type d'orienteur à l'origine de la candidature. Trois types d'orienteurs sont présentées pour simplifier la lecture : employeur, Pôle emploi et tous les autres cas.
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Décompte de toutes les candidatures de la période considérée, regroupées par mois \(sur la base de la date de candidature\), puis par type d'orienteur.
* 📊 **Présent dans** : [TB116](les-tableaux-de-bord-disponibles.md#recrutement)

### Evolution des candidatures acceptées par type d'employeur

* 📗 **Définition** : Évolution mois par mois de toutes les candidatures acceptées, présentées par type d'employeur.
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Décompte de toutes les candidatures dont l'état est "candidature acceptée" de la période considérée, regroupées par mois \(sur la base de la date de candidature\), puis par type d'employeur qui a acceptée la candidature.
* 📊 **Présent dans** : [TB116](les-tableaux-de-bord-disponibles.md#recrutement)

### Evolution des candidatures acceptées par type d'orienteur

* 📗 **Définition** : Évolution mois par mois de toutes les candidatures acceptées, présentées par type d'orienteur à l'origine de la candidature. Trois types d'orienteurs sont présentées pour simplifier la lecture : employeur, Pôle emploi et tous les autres cas.
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Décompte de toutes les candidatures dont l'état est "candidature acceptée" de la période considérée, regroupées par mois \(sur la base de la date de candidature\), puis par type d'orienteur.
* 📊 **Présent dans** : [TB116](les-tableaux-de-bord-disponibles.md#recrutement)

### Profil des candidats acceptés

* 📗 **Définition** : Evolution mois par mois du profil des candidats dont la candidature a été acceptée, en se concentrant sur 5 types de profil : RSA, DETLD, DELD, Jeune, QPV
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Pour RSA : pourcentage calculé par la division du \[décompte de tous les candidats dont au moins une candidature a été acceptée et dont le champ RSA est égal à Oui\] par le \[décompte de tous les candidats dont au moins une candidature a été acceptée\], regroupés par mois \(sur la base de la date de diagnostic : date à laquelle le prescripteur ou l'employeur a renseigné le profil\). Même principe pour les autres profils DETLD, DELD, Jeune, QPV
* 📊 **Présent dans** : [TB116](les-tableaux-de-bord-disponibles.md#recrutement)

### Etat des candidatures par métier

* 📗 **Définition** : Liste des métiers proposés sur les emplois de l'inclusion, avec le nombre de candidatures, le pourcentage de candidatures acceptées et le pourcentage de candidatures déclinées
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Liste de tous les codes ROME, nombre total sur la période concernée de candidatures rattachées à des fiches de poste avec le code ROME correspondant ; nombre de candidatures dont l'état est "candidature acceptée" parmi ce total divisé par le total ramené en base 100 ; nombre de candidatures dont l'état est "candidature déclinée" parmi ce total divisé par le total ramené en base 100
* 📊 **Présent dans** : [TB116](les-tableaux-de-bord-disponibles.md#recrutement)

### Pourcentage de candidatures acceptées par type de prescripteur

* 📗 **Définition** : Liste des prescripteurs avec le nombre d'établissements, de conseillers, de candidatures, ratio de candidatures par conseiller et ratio de candidatures acceptées
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Liste de tous les types de prescripteurs et orienteurs et en colonne le nombre d'établissements, le nombre total de conseillers, le nombre total de candidatures émises sur la période considérée, le ratio candidatures par conseiller \(division du total précédent par le nombre de conseillers\), le ratio de candidatures acceptées \(part des candidatures dont l'état est "candidature acceptée" parmi le total précédent\)
* 📊 **Présent dans** : [TB116](les-tableaux-de-bord-disponibles.md#recrutement)

### Motif de refus des candidatures

* 📗 **Définition** : Répartition des motifs de refus des candidatures sur la période considérée
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Répartition en pourcentage des refus des candidatures dont l'état est "candidature déclinée" sur la période considérée. Les motifs sont répartis comme suit : Candidat pas venu ou pas intéressé \(motif "Candidat indisponible ou non intéressé par le poste" ou "Candidat non venu ou non joignable"\) ; Pas de poste ouvert \(motif "Pas de poste ouvert en ce moment"\) Incompatibilité avec le poste \(motif "Un des freins à l'emploi du candidat est incompatible avec le poste proposé"\) ; Doute sur l'éligibilité \(motif "Candidat non éligible" ou "Doute sur l'éligibilité du candidat \(penser à renvoyer la personne vers un prescripteur\)"\) ; Contraire aux objectifs négociés \(motif "L'embauche du candidat empêche la réalisation des objectifs du dialogue de gestion"\) ; Autre \(tous les autres motifs\)
* 📊 **Présent dans** : [TB116](les-tableaux-de-bord-disponibles.md#recrutement)

### Motif de refus des candidatures par type de prescripteur

* 📗 **Définition** : Répartition des motifs de refus des candidatures sur la période considérée, par type de prescripteur
* 💾 **Source des données** : emplois de l'inclusion
* 🧮 **Formule** : Répartition en pourcentage des refus des candidatures dont l'état est "candidature déclinée" sur la période considérée et par type de prescripteur. Les motifs sont répartis comme suit : Candidat pas venu ou pas intéressé \(motif "Candidat indisponible ou non intéressé par le poste" ou "Candidat non venu ou non joignable"\) ; Pas de poste ouvert \(motif "Pas de poste ouvert en ce moment"\) Incompatibilité avec le poste \(motif "Un des freins à l'emploi du candidat est incompatible avec le poste proposé"\) ; Doute sur l'éligibilité \(motif "Candidat non éligible" ou "Doute sur l'éligibilité du candidat \(penser à renvoyer la personne vers un prescripteur\)"\) ; Contraire aux objectifs négociés \(motif "L'embauche du candidat empêche la réalisation des objectifs du dialogue de gestion"\) ; Autre \(tous les autres motifs\)
* 📊 **Présent dans** : [TB116](les-tableaux-de-bord-disponibles.md#recrutement)

