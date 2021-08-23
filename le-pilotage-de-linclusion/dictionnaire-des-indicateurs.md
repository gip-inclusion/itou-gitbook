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

