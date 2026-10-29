---
type: pattern
id: recompense-quotidienne
title: Récompense de connexion quotidienne
lang: fr
category: progression
severity_base: 2
domains: [games]
aliases:
  - daily reward
  - série de connexions
  - login streak
  - bonus de fidélité quotidien
psychology: >
  Exploite l'aversion à la perte appliquée à une série : ce n'est pas la
  récompense du jour qui retient le joueur, c'est la crainte de rompre une
  progression accumulée. Plus la série est longue, plus le coût psychologique
  de l'interruption augmente, indépendamment de la valeur réelle du gain.
criteria:
  includes:
    - Une récompense est conditionnée à la connexion, pas au jeu
    - Sa valeur croît avec la longueur de la série
    - Une journée manquée réinitialise ou dégrade la série
  excludes:
    - Récompense quotidienne à valeur constante, sans effet de série
    - Série dont l'interruption n'entraîne aucune perte
    - Récompense liée à une activité de jeu, non à la simple connexion
references:
  - title: Dark patterns in the design of games — playing by appointment
    authors: Zagal, Björk, Lewis
    venue: Foundations of Digital Games
    year: 2013
tags: [progression, temps, habitude]
---

# Récompense de connexion quotidienne

Une récompense croissante liée à la régularité de connexion, dont l'interruption
efface l'acquis.

## Mécanisme

Le joueur se connecte, reçoit, repart. Le jeu n'a pas eu lieu — c'est le point.

La récompense n'est pas la contrepartie d'une activité mais d'une **présence**,
et sa valeur croissante rend chaque jour manquant plus coûteux que le précédent.
Au septième jour d'une série, l'enjeu n'est plus la récompense du huitième : c'est
la perte des sept premiers.

## Pourquoi une sévérité faible

Ce pattern est classé 2 sur 5, et l'écart avec les autres est délibéré.

Pris isolément, il coûte au joueur quelques secondes par jour et ne prélève rien.
Beaucoup de jeux l'emploient sans aucune monétisation associée, comme simple
mécanique de fidélisation. En faire un grief majeur affaiblirait la crédibilité
du fonds sur les patterns qui, eux, prélèvent réellement.

Sa nocivité est **combinatoire** : associé à un système d'énergie et à un passe
expirant, il transforme le jeu en obligation quotidienne. C'est la conjonction
qui pèse, et c'est ce que le calcul de sévérité par cumul reflète.

## Comment le vérifier

Une capture du calendrier de récompenses suffit, à condition qu'elle montre les
deux éléments décisifs : **la progression des valeurs** et **la règle de
réinitialisation**. Cette dernière est parfois reléguée dans une infobulle.

## Ce qui ne relève pas de ce pattern

Une récompense quotidienne constante, sans série. Une série dont la rupture ne
coûte rien. Une récompense liée à une action de jeu — jouer une partie n'est pas
se connecter.

## Œuvres documentées

Renseigné à l'ingestion depuis les relations `exhibits`.
