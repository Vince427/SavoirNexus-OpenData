---
type: pattern
id: systeme-energie
title: Système d'énergie
lang: fr
category: progression
severity_base: 3
domains: [games]
aliases:
  - énergie
  - vies limitées
  - energy system
  - file d'attente de jeu
psychology: >
  Impose un rythme extérieur au joueur : la partie s'interrompt non par
  satisfaction ou lassitude, mais par épuisement d'une ressource dont la
  recharge est temporisée. L'attente crée une tension que l'achat résout
  immédiatement — c'est la conversion de l'impatience en revenu.
criteria:
  includes:
    - Une ressource consommée par le jeu limite le nombre de parties
    - Sa recharge est fonction du temps écoulé, pas de l'action du joueur
    - Un achat permet de la restaurer immédiatement
  excludes:
    - Ressource rechargée en jouant, sans temporisation
    - Limite quotidienne sans possibilité d'achat
    - Ressource narrative sans effet sur l'accès au jeu
references:
  - title: Dark patterns in the design of games — playing by appointment
    authors: Zagal, Björk, Lewis
    venue: Foundations of Digital Games
    year: 2013
tags: [progression, temps, monétisation]
---

# Système d'énergie

Une ressource temporisée qui interrompt la partie et se recharge contre paiement.

## Mécanisme

Chaque partie consomme une unité d'une réserve limitée. Épuisée, elle se
reconstitue au rythme de l'horloge — une unité toutes les vingt ou trente
minutes — sauf achat.

Le dispositif ne vend pas du contenu : il vend **l'annulation d'une contrainte
que le jeu a lui-même posée**. C'est ce qui le distingue d'une limite de
conception.

## L'effet de second ordre, plus important que le premier

Le revenu direct n'est pas l'essentiel. Le système d'énergie **installe une
habitude** : il conditionne le joueur à revenir à intervalles réguliers pour
consommer une réserve reconstituée, sous peine de la « gaspiller » en la
laissant pleine.

Zagal, Björk et Lewis rangent ce mécanisme parmi les *temporal dark patterns*,
sous le nom de « jeu sur rendez-vous » — le jeu fixe l'horaire, pas le joueur.

## Comment le vérifier

Relever trois chiffres : la taille de la réserve, la durée de recharge d'une
unité, et le prix de la restauration immédiate. Le tout se lit sur un seul écran
et se capture en une fois — c'est l'un des patterns les plus simples à établir.

Vérifier ensuite qu'aucune voie non payante ne permet de restaurer la réserve
par le jeu lui-même.

## Ce qui ne relève pas de ce pattern

Une ressource qui se regagne en jouant. Une limite quotidienne sans achat
possible — c'est une décision de conception, éventuellement protectrice. Une
jauge narrative sans effet sur l'accès.

## Œuvres documentées

Renseigné à l'ingestion depuis les relations `exhibits`.
