# Politique d'usage de la plateforme data.economie.gouv.fr

## Table

- [Introduction](#Introduction)
  - [Objectif du document](#Objectif-du-document)
  - [Importance de la normalisation](#Importance-de-la-normalisation)
- [Gouvernance de l'Open Data](#Gouvernance-de-l'Open-Data)
  - [Au sein des ministères économiques et financiers](#Au-sein-des-minist%C3%A8res-%C3%A9conomiques-et-financiers)
  - [Articulation entre data.economie.gouv.fr et data.gouv.fr](#Articulation-entre-data.economie.gouv.fr-et-data.gouv.fr)
- [Politique d'utilisation de la plateforme](#Politique-d'utilisation-de-la-plateforme)
  - [Accès et autorisation](#Acc%C3%A8s-et-autorisation)
  - [Responsabilité des producteurs de données](#Responsabilit%C3%A9-des-producteurs-de-donn%C3%A9es)
- [Opérations courantes](#Op%C3%A9rations-courantes)
  - [Modification de l'identifiant technique d'un jeu de données](#Modification-de-l'identifiant-technique-d'un-jeu-de-donn%C3%A9es)
  - [Suppression d'un jeu de données](#Suppression-d'un-jeu-de-donn%C3%A9es)
  - [Ouverture d'un jeu de données](#Ouverture-d'un-jeu-de-donn%C3%A9es)
  - [Tester un jeu de données en accès restreint](#Tester-un-jeu-de-donn%C3%A9es-en-acc%C3%A8s-restreint)
- [Structure des jeux de données](#Structure-des-jeux-de-donn%C3%A9es)
  - [Conventions de nommage](#Conventions-de-nommage)
  - [Identifiants et noms des jeux de données](#Identifiants-et-noms-des-jeux-de-donn%C3%A9es)
  - [Versionnement des jeux de données](#Versionnement-des-jeux-de-donn%C3%A9es)
  - [Gestion des sources](#Gestion-des-sources)
- [Format et structure des fichiers de données](#Format-et-structure-des-fichiers-de-donn%C3%A9es)
- [Gestion des métadonnées](#Gestion-des-m%C3%A9tadonn%C3%A9es)
  - [Considérations générales](#Consid%C3%A9rations-g%C3%A9n%C3%A9rales)
  - [Modèle de documentation](#Mod%C3%A8le-de-documentation)
  - [Métadonnées requises](#M%C3%A9tadonn%C3%A9es-requises)
  - [Point de contact](#Point-de-contact)
- [Monitoring](#Monitoring)
  - [Suivi du remplissage des métadonnées](#Suivi-du-remplissage-des-m%C3%A9tadonn%C3%A9es)
- [Ressources](#Ressources)
  - [Documentation technique](#Documentation-technique)
  - [Métadonnées](#M%C3%A9tadonn%C3%A9es)
  - [Acculturation à la donnée](#Acculturation-%C3%A0-la-donn%C3%A9e)

## Introduction

### Objectif du document

Le présent document vise à établir des directives d'usage claires pour la plateforme Open Data du ministère de
l'Économie et des Finances [data.economie.gouv.fr](https://data.economie.gouv.fr).

L'objectif est de fournir aux producteurs de données des directions un cadre de référence pour la publication, la
gestion et l'utilisation des jeux de données ministériels.

Ces normes et ces bonnes pratiques ont pour finalité d'offrir à nos réutilisateurs – internes et externes – une
interface cohérente avec nos activités tout en garantissant un certain niveau de qualité.

### Importance de la normalisation

Cet effort de normalisation présente plusieurs avantages :

- **Qualité** : garantir un niveau de pertinence et de fiabilité des données utilisées,
- **Accessibilité** : une plateforme bien structurée et documentée facilite la recherche, la découverte et l'utilisation
  des données,
- **Interopérabilité** : adopter des standards et des référentiels pour les données ainsi que les métadonnées facilite
  leur utilisation intégrée,
- **Confiance** : des pratiques transparentes renforcent la confiance des utilisateurs et valorise notre mission de
  service public.

## Gouvernance de l'Open Data

### Au sein des ministères économiques et financiers

Dans le cadre de la mise en place d'une politique de la donnée voulue comme ambitieuse, la
[circulaire n°6264/SG](https://www.legifrance.gouv.fr/circulaire/id/45162) publiée le 27 avril 2021 crée un nouveau rôle
– l'Administrateur ministériel des données, des algorithmes et des codes sources (AMDAC) – chargé de coordonner la
circulation, l'ouverture et l'exploitation des données publiques, des algorithmes et des codes sources.

Au niveau ministériel, cette politique est coordonnée par l'AMDAC au sein du Bercy Hub (amd@finances.gouv.fr) et cadrée
par la feuille de route de la donnée 2024-2026, co-construite avec les directions tout au long de l'année 2023.

La gouvernance de l'Open Data et la gestion de la plateforme [data.economie.gouv.fr](https://data.economie.gouv.fr) font
au sein des Ministères économiques et financiers l'objet d'une mission dédiée.

Au sein des directions, l'Administrateur directionnel des données est chargé de la stratégie et de la gouvernance des
données, comprenant le plus souvent l'Open Data. Suivant leur structure, l'Open Data peut faire l'objet d'une mission
dédiée.

N'hésitez pas à mobiliser ces acteurs pour le cadrage, la réalisation ou le suivi de vos projets data lorsque vous
contactez nos équipes. Nous tiendrons prochainement un annuaire directionnel des référents Open Data à votre
disposition.

### Articulation entre data.economie.gouv.fr et data.gouv.fr

Le site [data.gouv.fr](https://www.data.gouv.fr/fr/) est le portail national des données publiques ouvertes de
l'administration.

La plateforme [data.economie.gouv.fr](https://data.economie.gouv.fr/pages/accueil/) est la plateforme des données
ouvertes publiées par les ministères économiques et financiers.

Le portail data.gouv.fr récupère les données de data.economie.gouv.fr quotidiennement par voie de moissonnage, il n'est
donc pas nécessaire de procéder à des opérations manuelles de publication sur data.gouv.fr.

Le portail data.gouv.fr propose une fonctionnalité de discussion. Les équipes Open Data du Bercy Hub sont notamment
chargées de ventiler les notifications. Les métiers souhaitant répondre peuvent demander à être rattachés à
l'organisation MEFSIN sur data.gouv.fr sur demande à \[contact.dataeconomie@finances.gouv.fr\]

**Attention** : Chaque jeu de données publié et en accès public sur la plateforme data.economie.gouv.fr est moissonné et
rendu accessible sur le portail data.gouv.fr. Il convient donc de ne pas rendre accessible des données de test et / ou
des données confidentielles.

## Politique d'utilisation de la plateforme

### Accès et autorisation

L'accès à la plateforme [data.economie.gouv.fr](https://data.economie.gouv.fr) n'est autorisé qu'aux agents habilités
des Ministères économiques et financiers, après demande auprès de l'administrateur de la plateforme :

- contact.dataeconomie@finances.gouv.fr

La gestion des identités et des accès est effectuée par les administrateurs de la plateforme, qui attribuent les droits
appropriés en fonction des responsabilités de chaque utilisateur.

Ceux-ci sont priés de se conformer aux politiques et procédures de sécurité de l'organisation lors de l'accès à la
plateforme, notamment :

- les comptes doivent être personnels (pas de boîte à lettre fonctionnelle),
- les comptes ne doivent pas être partagés entre utilisateurs.

### Responsabilité des producteurs de données

Les producteurs de données sont responsables de la qualité et de l'intégrité des jeux de données qu'ils publient sur la
plateforme. Ceci inclut la vérification de l'exactitude des données et des métadonnées, leur mise à jour éventuelle
ainsi que la résolution rapide des problèmes de qualité signalés par les utilisateurs.

Les producteurs de données sont également tenus de garantir que les jeux de données rendus publics - hors usage
restreint - ne contiennent pas d'informations sensibles ou confidentielles : un jeu de données rendu public est
moissonné de manière programmatique par plusieurs plateformes, dont la plateforme Open Data
[data.gouv.fr](https://data.gouv.fr).

## Opérations courantes

### Modification de l'identifiant technique d'un jeu de données

**Attention** : Le changement d'identifiant technique sur [data.economie.gouv.fr](https://data.economie.gouv.fr) est une
opération qui provoque des effets de bord difficiles à appréhender. Elle ne doit en aucun cas être réalisée sans l'appui
d'un administrateur.

### Suppression d'un jeu de données

**Attention** : La suppression d'un jeu de données public non restreint est une opération administrateur quelle que soit
la plateforme (data.economie.gouv.fr ou data.gouv.fr).

Adresser la demande à l'équipe d'administration qui la traitera dans les plus brefs délais en fournissant les liens
pointant vers les jeux de données à supprimer.

Un certain nombre de jeux de données sont réutilisés par des systèmes d'information tiers et entrent dans la chaîne
logistique informationnelle.

Une suppression sans étude d'impact peut occasionner une perte d'accès à l'information pour les utilisateurs ainsi
qu'une interruption dans la continuité des données.

Un jeu de données supprimé ainsi que ses métadonnées peuvent ne pas être récupérable facilement.

### Ouverture d'un jeu de données

Par sécurité, les jeux de données publiés sont par défaut en usage restreint. Les producteurs de données sont par
conséquent responsables de leur ouverture, qui nécessite une action consciente :

> *dataset* -> Sécurité -> Sécurité par défaut -> Accès limité aux utilisateurs et groupes autorisés

Tout jeu de données ouvert est ensuite moissonné par les plateformes data.gouv.fr et peut potentiellement entrer dans la
chaîne de dépendance de systèmes d'information tiers.

Les jeux de données de `test` ou de `preprod` ne doivent être ouverts qu'à un public restreint en accordant aux
personnes habilitées les droits adaptés, en lecture et / ou en écriture.

N'hésitez pas à solliciter l'équipe d'administration à ce sujet.

### Tester un jeu de données en accès restreint

Les jeux de données en accès restreint ne sont accessibles de manière programmatique qu'après authentification. Après
avoir [généré une clef API](https://data.economie.gouv.fr/account/api-keys/), vous pouvez intégrer la clef au `header`
de la requête comme ceci :

```
import os

import requests

KEY = os.environ["KEY"]
HEADERS = {"Authorization": f"Apikey {KEY}"}
print(HEADERS)
DATASET_NAME = "test-my-dataset"

url = f"https://data.economie.gouv.fr/api/explore/v2.1/catalog/datasets/"
params = {"where": f"dataset_id='{DATASET_NAME}'", "include_app_metas": True}

response = requests.get(url, headers=HEADERS, params=params)
print(response.json())
```

**Attention** : une clef API ne doit jamais être publiée, il reste préférable de passer par des variables
d'environnement.

## Structure des jeux de données

### Conventions de nommage

> Selon que notre idée est plus ou moins obscure, L’expression la suit, ou moins nette, ou plus pure. Ce que l’on
> conçoit bien s’énonce clairement, Et les mots pour le dire arrivent aisément. – Boileau, *Art Poétique*

Principes généraux :

- **Clarté et concision** : les noms des jeux de données ou des fichiers joints doivent éviter autant que possible les
  acronymes ou les abréviations obscures et ne pas faire plus de 170 signes,
- **Noms** : les noms utilisés pour les jeux de données, les titres, les champs doivent respecter autant que possible un
  vocabulaire commun et demeurer explicites à l'utilisateur non averti
- **Uniformité** : de manière à faciliter l'identification des jeux de données et leur regroupement, une structure de
  nommage cohérente devra être adoptée pour tous les jeux de données (cf. ci-dessous),
- **Encodage** : les jeux de données seront encodés au format `utf-8`, un format désormais courant, compatible ASCII et
  devenu un standard facilitant la compatibilité et les performances,
- **Mots-clés** : intégrer des mots clefs dans les noms des jeux de données permet d'améliorer leur référencement :
  qu'ils disent ce qu'ils fassent et qu'ils fassent ce qu'ils disent.

### Identifiants et noms des jeux de données

Par *identifiant*, nous entendons *identifiant technique*, soit non seulement l'identifiant unique d'un jeu de données
sur la plateforme data.economie.gouv.fr, mais également sur les plateformes qui réutilisent nos jeux de données par voie
de moissonnage, comme data.gouv.fr.

- il doit être défini avant la publication,
- il ne doit pas être changé après avoir été mis en production.

Par *nom du jeu de données*, nous entendons la chaîne de caractère identifiant le jeu de données sur la plateforme, soit
ce qui est affiché à l'utilisateur, soit sur la page du jeu de données lui-même ou dans le moteur de recherche.

Quelques considérations :

- préférer le tiret court (1/4 de cadratin) au tiret bas pour les identifiants des jeux de données,
- nommer les identifiants techniques des jeux de données en fonction de leur environnement :
  - `test-<dataset_name>`,
  - `preprod-<dataset_name>`,
- les variables *environnement* à mentionner sont `test`et `preprod`, leur absence désigne la production,
- nommer les identifiants des jeux de données en fonction de leur périmètre de diffusion :
  - `<env>-restreint-<dataset_name>`,
  - `<env>-interne-<dataset_name>`.
- les noms des jeux de données sont écrits autant que possible en français courant,
- les variables _environnement_ et _périmètre de diffusion_ sont notées entre crochets dans les jeux de données.

*Exemple* :

- Identifiant technique : `test-interne-prix-des-carburants-v2`
- Nom du jeu de données : `[Test][Interne] Prix des carburants v2`

### Versionnement des jeux de données

De manière à assurer la traçabilité et la cohérence des jeux de données, un numéro de version doit être associé à chaque
jeu de données publié sur la plateforme. A cette fin, nous préconisons, en matière de gestion sémantique de version,
l'emploi du standard [SemVer 2.0.0](https://semver.org/lang/fr/) : `<majeure>.<mineure>.<patch>`.

Les producteurs sont tenus de documenter clairement, soit dans un fichier texte en pièce jointe type `CHANGELOG`, soit
en description, les modifications apportées à chaque version des jeux de données, y compris les mises à jour, les
corrections d'erreur et les ajouts de nouvelles données.

Outre la gestion sémantique de version, les mises à jour peuvent être horodatées en activant l'option
`Mettre à jour la date après un traitement des données` dans les informations de chaque jeu de données au chemin suivant
:

- `Informations > Standard > Informations générales > Afficher la date de modification`

### Gestion des sources

La plateforme data.economie.gouv.fr est la plateforme Open Data du ministère de l'Économie et des Finances. À ce titre,
elle ne doit contenir que des jeux de données produits par les Ministères économiques et financiers.

**Attention** : La plateforme data.gouv.fr, qui reprend par moissonnage le contenu de la plateforme
data.economie.gouv.fr ne peut pas être une source de données pour data.economie.gouv.fr.

## Format et structure des fichiers de données

Le format ainsi que la manière avec laquelle un fichier est structuré, ont une forte influence sur son accessibilité, sa
lisibilité et sa réutilisation.

Principes généraux :

- **Encodage** : Les fichiers doivent être encodés au format `utf-8`,
- **Formats standardisés** : Nous privilégierons les formats standardisés et ouverts tels que `CSV`, `JSON`, `XML`,
  `TXT`,
- **Formats ouverts** : Nous chercherons à éviter :
  - les formats propriétaires (`docx`, `xlsx`),
  - le format PDF,
  - les formats compressés (`zip`, `tar.gz`).
- **Normalisation des valeurs** :
  - Les champs `date` doivent suivre le standard ISO 8601 : `AAAA-MM-JJ HH:MM:SS.CCC`,
  - Les noms des champs doivent respecter des conventions de nommage cohérentes (pas de majuscules, séparateurs
    identiques, etc.).

## Gestion des métadonnées

### Considérations générales

Les métadonnées sont des "données qui fournissent de nouvelles informations sur d'autres données". À ce titre, elles
permettent de contextualiser un jeu de données : les champs dans lesquels apparaissent des termes métier donnent des
indications sur le producteur, la fréquence des mises à jour, la licence, etc.

Le module de recherche (raccourci `Ctrl / Cmd + K`) se nourrit des métadonnées pour offrir plus de contexte aux
recherches des utilisateurs : remplir les métadonnées permet également d'étoffer considérablement l'indexation des jeux
de données et de renforcer la pertinence du moteur de recherche.

Sur la plateforme ministérielle data.economie.gouv.fr, ces métadonnées, à remplir pour chaque jeu de donnée, se trouvent
à plusieurs endroits :

- métadonnées des champs d'un document tabulaire, qui apparaissent dans l'onglet `Traitement` du backoffice,
- métadonnées `standard`, `admin` et `DCAT` de l'onglet `Informations` du backoffice.

**Attention** : Le remplissage des métadonnées répond aux mêmes critères de concision et de clarté que ceux décrits
ci-dessus.

### Modèle de documentation

Le modèle de documentation [Datasheets for Datasets](https://arxiv.org/pdf/1803.09010) cadre la rédaction des
métadonnées en fournissant une liste de questions utiles, sur la création des jeux de données, leur composition, leur
collecte, les traitements opérés, les modalités de diffusion ou de maintenance.

### Métadonnées requises

Les métadonnées à remplir en premier lieu sont :

- **le titre** : permet aux utilisateurs de comprendre le contenu du jeu de données,
- **la description** : brève description du contenu et de l’objectif du jeu de données,
- **la date de publication** : renseigne sur la temporalité des données,
- **le producteur** : indique la direction responsable de la production du jeu de données (voir note *Point de contact*
  ci-dessous)
- **contact** : coordonnées du responsable des données.
- **la licence** : fixe les conditions d'utilisation et de réutilisation des données. Par défaut
  `Licence Ouverte v2.0 (Etalab)`,
- **la description** : détaille le contenu, les sources et la méthodologie de collecte des données,
- **les références** : ou tout lien vers des sources externes ou documents connexes utiles.

### Point de contact

La question peut se poser de renseigner comme `email de contact` l'adresse d'une boîte à lettres fonctionnelle (BALF)
plutôt qu'un email en `finances.gouv.fr`.

Le point de contact personnel a un avantage : il permet de savoir qui est nommément responsable d’un jeu de données et
savoir précisément à qui s’adresser.

Inconvénient : il est rarement mis à jour en cas de départ et devient alors obsolète très rapidement.

Une BALF est plus anonyme mais aussi plus stable dans le temps.

Sans avoir de doctrine établie, nous pouvons ici faire valoir le bon sens et laisser le choix aux producteurs de
données, pourvu que :

- le point de contact renseigné soit d'une granularité adaptée,
- soit directement relié à une personne physique responsable de la production et la mise à jour des données,
- permette un traitement des demandes des utilisateurs le plus rapide et le plus efficace possible.

## Monitoring

### Suivi du remplissage des métadonnées

Un jeu de données mis à jour à une fréquence bi-hebdomadaire peut vous renseigner sur le taux de remplissage de vos
métadonnées :

- https://data.economie.gouv.fr/explore/dataset/admin-qualite-des-jeux-de-donnees-publies

Le `quality_score` est indicatif.

______________________________________________________________________

## Ressources

### Documentation technique

- [Publier un jeu de données](https://userguide.opendatasoft.com/l/fr/category/jrnwp63j97-publier-vos-jeux-de-donnees)

### Métadonnées

- [DCAT](https://doc.data.gouv.fr/moissonnage/dcat/)
- [Datasheets for datasets](https://open.datactivist.coop/docs/datasheets-datasets)
- [Remplir les métadonnées](https://userguide.opendatasoft.com/l/fr/category/is2wkknb71-metadonnes-des-ensembles-de-donnees)

### Acculturation à la donnée

- [Lab Archipel - DATAcculturation](https://youtu.be/_yxlo41dBuA?si=DVxW9M5MsiBNJ8iS) (Vidéo)
- [Open Data France](https://opendatafrance.fr/les-ressources/)
- [Datactivist - Blog](https://open.datactivist.coop/docs)
