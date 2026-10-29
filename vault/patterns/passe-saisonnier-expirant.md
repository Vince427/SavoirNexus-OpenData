---
type: pattern
id: passe-saisonnier-expirant
title: Passe saisonnier expirant
lang: fr
category: urgency
severity_base: 3
domains: [games]
aliases:
  - battle pass
  - passe de combat
  - passe de saison
psychology: >
  Combine aversion à la perte et coûts irrécupérables : une récompense
  achetée mais non débloquée est vécue comme une perte imminente, ce qui
  transforme le jeu en obligation. Le joueur ne joue plus pour jouer, mais
  pour ne pas perdre ce qu'il a déjà payé.
criteria:
  includes:
    - L'accès à des récompenses est acheté à l'avance
    - Leur déblocage exige un temps de jeu dans une fenêtre bornée
    - Ce qui n'est pas débloqué à l'échéance est perdu sans compensation
  excludes:
    - Contenu acheté et immédiatement disponible
    - Récompenses restant réclamables après la fin de la saison
    - Abonnement donnant accès à du contenu tant qu'il est actif
references:
  - title: Dark patterns in the design of games — temporal dark patterns
    authors: Zagal, Björk, Lewis
    venue: Foundations of Digital Games
    year: 2013
  - title: Deceptive patterns — Fake urgency
    authors: Brignull
    url: https://www.deceptive.design/types
tags: [urgence, temps, monétisation]
---

# Passe saisonnier expirant

Un contenu payé d'avance dont l'obtention exige de jouer avant une échéance,
sous peine de perte.

## Mécanisme

Le joueur achète un accès, pas un contenu. Les récompenses se débloquent par
paliers, atteints en jouant, dans une fenêtre de quelques semaines à quelques
mois.

L'inversion est là : dans une vente ordinaire, payer donne le bien. Ici, payer
**donne le droit de travailler pour l'obtenir** — et le travail non accompli à
l'échéance annule ce qui a été payé.

## Où passe exactement la frontière

Un passe saisonnier n'est pas en soi un anti-pattern, et le dire serait une
erreur d'analyse. Beaucoup fonctionnent honnêtement : le contenu débloqué reste
acquis, la progression est atteignable en jeu normal, l'échéance est annoncée.

Le pattern se caractérise par la **perte sèche** : ce qui a été payé mais non
débloqué disparaît. S'y ajoutent souvent deux aggravations — une cadence de
déblocage calibrée au-delà du temps de jeu moyen, et un accélérateur payant qui
résout le problème que la cadence a créé.

## Comment le vérifier

Relever la durée de la saison, le nombre de paliers, le temps de jeu nécessaire
par palier, et surtout **le sort des récompenses non débloquées à l'échéance** —
cette dernière information figure généralement dans les conditions, pas sur
l'écran d'achat.

Cet écart entre l'écran d'achat et les conditions est lui-même documentable.

## Le cas favorable, à documenter aussi

Un éditeur qui rend les récompenses réclamables après la fin de saison supprime
le pattern. C'est exactement le type de changement qui fait passer un claim en
`corrected`, avec crédit affiché. Ce n'est pas une hypothèse d'école : c'est
l'évolution la plus fréquente observée sur ce mécanisme.

## Ce qui ne relève pas de ce pattern

Un contenu acheté et disponible immédiatement. Un passe dont les récompenses
restent réclamables. Un abonnement qui donne accès tant qu'il est actif.

## Œuvres documentées

Renseigné à l'ingestion depuis les relations `exhibits`.
