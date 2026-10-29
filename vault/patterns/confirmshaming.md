---
type: pattern
id: confirmshaming
title: Culpabilisation au refus
lang: fr
category: interface
severity_base: 2
domains: [games, software, ecommerce]
aliases:
  - confirmshaming
  - culpabilisation
  - refus honteux
psychology: >
  Associe un coût émotionnel au refus. Le libellé du bouton de rejet cesse
  d'être neutre pour devenir un aveu — de radinerie, de désintérêt, de
  déraison. Le mécanisme ne trompe pas sur les faits : il rend le choix
  légitime inconfortable à formuler.
criteria:
  includes:
    - Le libellé de refus est rédigé à la première personne sur un ton dévalorisant
    - Le refus est présenté comme un renoncement ou une erreur de jugement
    - Le contraste visuel désavantage nettement l'option de refus
  excludes:
    - Libellés neutres (« Non merci », « Plus tard », « Annuler »)
    - Rappel factuel de ce que le refus implique
    - Simple différence de style entre les deux boutons
references:
  - title: Deceptive patterns — Confirmshaming
    authors: Brignull
    url: https://www.deceptive.design/types
tags: [interface, langage, manipulation]
---

# Culpabilisation au refus

Un bouton de refus rédigé pour rendre le refus embarrassant.

## Mécanisme

L'interface propose deux options. L'acceptation est neutre et visible ; le refus
est rédigé à la première personne, sur un ton qui transforme un choix ordinaire
en aveu :

> « Non merci, je préfère jouer sans avantage »
> « Je ne veux pas progresser plus vite »
> « Tant pis pour mes récompenses »

Le procédé ne dissimule aucune information. Il **taxe émotionnellement** une
décision parfaitement rationnelle.

Un renfort visuel l'accompagne fréquemment : bouton d'acceptation coloré et
saillant, refus en gris pâle ou en texte de petite taille.

## Pourquoi une sévérité faible, et pourquoi le documenter quand même

Classé 2 sur 5 : le joueur conserve son choix, l'information reste complète,
aucun prélèvement n'a lieu contre son gré. Le préjudice est réel mais mineur.

Il mérite néanmoins sa fiche pour deux raisons. C'est un **marqueur fiable** :
une interface qui l'emploie en emploie presque toujours d'autres, plus lourds.
Et c'est le pattern le plus **immédiatement lisible** par un non-spécialiste —
tout le monde comprend la manœuvre dès qu'on la lui montre, ce qui en fait une
bonne porte d'entrée pédagogique dans le fonds.

## Comment le vérifier

Une capture de la boîte de dialogue suffit, à condition qu'elle montre **les
deux options ensemble**. Le libellé du refus isolé ne prouve rien : c'est le
contraste avec l'acceptation qui fait le pattern.

C'est aussi le pattern le plus facile à documenter par un contributeur non
technicien — aucune mesure, aucun relevé, une seule capture.

## Ce qui ne relève pas de ce pattern

« Non merci ». « Plus tard ». « Annuler ». Un rappel factuel de ce que le refus
implique — « votre progression ne sera pas sauvegardée » est une information, pas
une culpabilisation. Une simple différence de style entre deux boutons.

## Œuvres documentées

Renseigné à l'ingestion depuis les relations `exhibits`.
