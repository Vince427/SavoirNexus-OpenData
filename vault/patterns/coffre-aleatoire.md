---
type: pattern
id: coffre-aleatoire
title: Coffre aléatoire
lang: fr
category: monetization
severity_base: 5
domains: [games]
aliases:
  - loot box
  - coffre à butin
  - gacha
  - caisse de butin
psychology: >
  Repose sur le renforcement à ratio variable : une récompense dont la
  survenue est imprévisible produit un taux de réponse plus élevé et plus
  résistant à l'extinction qu'une récompense certaine. C'est le mécanisme
  qui structure les machines à sous.
criteria:
  includes:
    - Le contenu obtenu est déterminé par le hasard au moment de l'ouverture
    - L'accès au tirage est payant, directement ou via une monnaie achetable
    - Le joueur ne connaît pas le résultat avant d'avoir engagé la dépense
  excludes:
    - Récompense aléatoire obtenue exclusivement en jouant, sans voie payante
    - Coffre dont le contenu est annoncé avant l'ouverture
    - Achat direct d'un objet identifié à un prix affiché
references:
  - title: Dark patterns in the design of games
    authors: Zagal, Björk, Lewis
    venue: Foundations of Digital Games
    year: 2013
  - regulation: /regulations/be-loot-boxes-2018
regulated_by:
  - /regulations/be-loot-boxes-2018
tags: [monétisation, hasard, régulé]
---

# Coffre aléatoire

Un contenu payant dont la nature exacte n'est révélée **qu'après** l'engagement
de la dépense.

## Mécanisme

Le joueur achète un tirage, pas un objet. La grille de probabilités est parfois
publiée, souvent approximative, et presque jamais présentée au moment de la
décision d'achat.

Le renforcement à ratio variable est le levier : une récompense imprévisible
soutient un comportement plus longtemps qu'une récompense garantie, y compris
après que les gains ont cessé. C'est un fait de psychologie expérimentale bien
établi, et c'est ce qui distingue ce pattern d'une simple vente.

## Pourquoi la sévérité maximale

Trois raisons cumulatives, et c'est le seul pattern du fonds à les réunir :

1. **Il est régulé.** Une autorité européenne l'a qualifié de jeu de hasard —
   voir [la décision belge de 2018](/regulations/be-loot-boxes-2018).
2. **Le coût est indéterminable à l'avance.** Obtenir un objet précis peut
   coûter dix euros ou mille, et le joueur ne peut pas le savoir.
3. **Il concerne des mineurs.** Les classifications d'âge des jeux qui
   l'emploient ne recoupent pas celles des jeux d'argent.

## Comment le vérifier

Relever, à la même date : la grille des probabilités si elle est publiée, le
prix du tirage, et le nombre d'objets distincts obtenables. Capturer l'écran
d'achat — pas la page de documentation, qui n'est pas ce que le joueur voit au
moment de décider.

Le constat décisif est **l'absence d'information sur le contenu au moment de la
transaction**. Il est objectif et se montre en une capture.

## Ce qui ne relève pas de ce pattern

Un coffre gagné en jouant, sans possibilité d'achat. Un « pack » dont la
composition est annoncée. Une boutique où l'on achète l'objet voulu à un prix
affiché — quel que soit ce prix.

La frontière est le **hasard payant**, pas le prix.

## Œuvres documentées

Renseigné à l'ingestion depuis les relations `exhibits`.
