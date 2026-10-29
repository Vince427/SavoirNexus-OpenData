---
type: pattern
id: avantage-competitif-payant
title: Avantage compétitif payant
lang: fr
category: monetization
severity_base: 4
domains: [games]
aliases:
  - pay-to-win
  - P2W
  - payer pour gagner
psychology: >
  Détourne la logique de compétence : le résultat cesse de mesurer l'habileté
  pour mesurer la dépense. L'effet sur le joueur non payant est une dévaluation
  de son investissement en temps, qui le pousse soit à dépenser, soit à partir.
criteria:
  includes:
    - Un achat confère un avantage mesurable en confrontation directe entre joueurs
    - L'avantage n'est pas obtenable en un temps de jeu comparable et raisonnable
    - Les joueurs payants et non payants sont mis en concurrence
  excludes:
    - Achats purement cosmétiques sans effet sur les caractéristiques
    - Avantage disponible gratuitement par le jeu en un temps comparable
    - Jeu sans confrontation entre joueurs
    - Files d'attente séparant payants et non payants
references:
  - title: Dark patterns in the design of games — monetary dark patterns
    authors: Zagal, Björk, Lewis
    venue: Foundations of Digital Games
    year: 2013
tags: [monétisation, compétition, équité]
---

# Avantage compétitif payant

Un achat qui améliore les chances de gagner face à d'autres joueurs.

## Mécanisme

Le jeu vend de la puissance : statistiques supérieures, accès exclusif à un
équipement, réduction d'un temps d'attente qui pénalise en confrontation.

L'effet ne porte pas seulement sur l'acheteur. Il **dévalue le temps investi par
les autres**, ce qui crée une pression indirecte : continuer à perdre, dépenser,
ou partir.

## Le critère décisif, souvent mal appliqué

Ce pattern est fréquemment invoqué à tort. Le critère n'est pas « on peut
acheter des choses », ni même « les objets achetés sont puissants ».

Le critère est la **confrontation** : payants et non payants doivent s'affronter
pour que l'avantage produise son effet. Un jeu solo dont on peut acheter un
équipement surpuissant ne relève pas de ce pattern — il n'y a personne à léser.

Second critère, le **temps comparable** : si l'objet s'obtient gratuitement en
quelques heures de jeu, l'achat est une commodité, pas un avantage. S'il demande
trois cents heures, c'en est un.

## Comment le vérifier

Relever les caractéristiques chiffrées de l'objet payant et de son meilleur
équivalent gratuit, ainsi que le temps de jeu nécessaire pour obtenir ce dernier.
Vérifier ensuite que le mode concerné met bien en présence les deux populations.

Le constat est arithmétique lorsque les statistiques sont affichées — donc
opposable. Quand elles ne le sont pas, un claim reste au mieux `inferred`.

## Ce qui ne relève pas de ce pattern

Le cosmétique, même très cher. Les extensions de contenu. Les jeux sans
affrontement. Les serveurs séparés qui ne mélangent pas les populations.

Documenter un jeu cosmétique-seulement comme pay-to-win est l'erreur qui fait
tomber une fiche en réclamation, et à juste titre.

## Œuvres documentées

Renseigné à l'ingestion depuis les relations `exhibits`.
