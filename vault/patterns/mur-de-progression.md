---
type: pattern
id: mur-de-progression
title: Mur de progression
lang: fr
category: progression
severity_base: 3
domains: [games]
aliases:
  - grind gate
  - mur de grind
  - progression bloquée
  - grinding
psychology: >
  Exploite l'engagement et les coûts irrécupérables : plus le temps investi
  est important, plus l'abandon est ressenti comme une perte. Le joueur qui a
  déjà consacré des dizaines d'heures évalue le contournement payant à l'aune
  de ce qu'il a investi, non de ce que l'objet vaut.
criteria:
  includes:
    - Le rythme de progression chute brutalement à un palier identifiable
    - Un achat permet de franchir ce palier plus vite
    - La chute n'est pas annoncée avant que le joueur ne l'atteigne
  excludes:
    - Difficulté croissante sans voie payante de contournement
    - Ralentissement annoncé et cohérent avec la conception affichée
    - Contenu additionnel payant qui n'accélère pas la progression existante
references:
  - title: Dark patterns in the design of games — temporal dark patterns
    authors: Zagal, Björk, Lewis
    venue: Foundations of Digital Games
    year: 2013
tags: [progression, temps, monétisation]
---

# Mur de progression

Une progression délibérément ralentie jusqu'au point où l'achat devient le
contournement évident.

## Mécanisme

Le jeu établit d'abord un rythme confortable, puis le casse à un palier précis.
Le ralentissement n'est pas présenté comme une difficulté accrue — le contenu
reste identique — mais comme une durée qui s'allonge.

L'achat proposé à ce moment n'ajoute rien : il **restaure le rythme initial**.
C'est ce qui distingue ce pattern d'une extension payante.

## La difficulté d'analyse, à ne pas minimiser

C'est le pattern le plus délicat à documenter honnêtement, et celui où les
erreurs d'appréciation sont les plus probables.

Un ralentissement de progression est une décision de conception **légitime** :
faire durer une expérience, espacer les récompenses, créer un sentiment
d'accomplissement. Des jeux entièrement dépourvus de monétisation en emploient.

Ce qui fait basculer dans l'anti-pattern est la **conjonction** : ralentissement
non annoncé **et** voie payante de contournement. Sans la seconde, ce n'est pas
ce pattern. En son absence, un claim sera contesté à juste titre.

## Comment le vérifier

Relever la courbe : temps ou ressources nécessaires par palier, sur au moins
cinq paliers de part et d'autre du seuil supposé. Un facteur brutal — un
triplement entre deux niveaux consécutifs — est objectivable ; une impression de
lenteur ne l'est pas.

Relever ensuite l'existence et le prix de l'accélérateur proposé.

**Sans relevé chiffré de première main, un claim sur ce pattern ne devrait pas
dépasser `confidence: inferred`.**

## Ce qui ne relève pas de ce pattern

Un jeu difficile. Un jeu long. Un jeu dont la progression ralentit sans
qu'aucun achat ne l'accélère. Une extension qui ajoute du contenu.

## Œuvres documentées

Renseigné à l'ingestion depuis les relations `exhibits`.
