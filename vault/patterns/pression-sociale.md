---
type: pattern
id: pression-sociale
title: Pression sociale
lang: fr
category: social
severity_base: 3
domains: [games]
aliases:
  - obligation sociale
  - social obligation
  - pyramide sociale
  - chantage au groupe
psychology: >
  Déplace le coût de l'absence du joueur vers son entourage : ce n'est plus
  lui qui est pénalisé, ce sont ses coéquipiers. L'obligation devient
  interpersonnelle, donc beaucoup plus difficile à refuser qu'une contrainte
  imposée par le jeu.
criteria:
  includes:
    - L'absence ou l'inaction d'un joueur pénalise d'autres joueurs
    - La progression exige de recruter ou de solliciter des tiers
    - Le jeu rend cette pénalité visible pour le groupe
  excludes:
    - Jeu coopératif dont l'intérêt suppose des partenaires, sans pénalité
    - Fonctions sociales facultatives, sans effet sur la progression
    - Classements sans conséquence sur les autres joueurs
references:
  - title: Dark patterns in the design of games — social capital-based dark patterns
    authors: Zagal, Björk, Lewis
    venue: Foundations of Digital Games
    year: 2013
tags: [social, obligation, groupe]
---

# Pression sociale

Une mécanique qui fait porter à d'autres joueurs le coût de votre absence.

## Mécanisme

Zagal, Björk et Lewis rangent ces dispositifs dans une catégorie distincte,
fondée sur le **capital social** : le jeu ne mobilise plus le temps ou l'argent
du joueur, mais ses relations.

Trois formes principales :

- **la pénalité de groupe** : l'inactivité d'un membre dégrade le résultat
  collectif, et le groupe le sait ;
- **le recrutement obligatoire** : la progression exige d'amener de nouveaux
  joueurs, structure explicitement pyramidale ;
- **la sollicitation** : le jeu incite à demander de l'aide à ses contacts, en
  transformant chaque joueur en canal d'acquisition.

## Pourquoi c'est la catégorie la plus difficile à documenter

Un jeu multijoueur **suppose** des interdépendances. Une équipe incomplète joue
moins bien : ce n'est pas un dark pattern, c'est la nature du jeu en équipe.

Le critère de basculement est que la pénalité soit **conçue et rendue visible**
pour produire la pression, plutôt que d'être la conséquence naturelle de
l'absence. Un tableau affichant au groupe quel membre ne s'est pas connecté n'a
pas d'autre fonction que de créer cette pression.

## Comment le vérifier

Capturer l'écran qui rend l'information visible au groupe, et relever la
pénalité chiffrée subie par les tiers. La preuve utile n'est pas l'existence de
la coopération : c'est **l'affichage nominatif de l'inactivité** ou la pénalité
explicitement appliquée aux autres.

Pour le recrutement, relever si la progression est bloquée en l'absence de
parrainage, ou seulement ralentie.

## Ce qui ne relève pas de ce pattern

Un jeu coopératif. Un jeu de guilde. Un classement. Une fonction sociale
facultative. La difficulté accrue à jouer seul un contenu conçu pour plusieurs.

## Œuvres documentées

Renseigné à l'ingestion depuis les relations `exhibits`.
