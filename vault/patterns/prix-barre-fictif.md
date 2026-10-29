---
type: pattern
id: prix-barre-fictif
title: Prix barré fictif
lang: fr
category: monetization
severity_base: 3
domains: [games, ecommerce]
aliases:
  - fausse remise
  - prix de référence fictif
  - ancrage tarifaire
psychology: >
  Exploite l'effet d'ancrage : un premier nombre présenté oriente l'évaluation
  de tous les suivants. Un prix barré élevé rend le prix demandé acceptable,
  indépendamment de la valeur réelle du bien.
criteria:
  includes:
    - Un prix de référence barré est affiché à côté du prix demandé
    - Le bien n'a jamais été vendu à ce prix de référence, ou seulement de façon marginale
    - La remise affichée est permanente ou se répète sans interruption réelle
  excludes:
    - Remise réelle sur un prix effectivement pratiqué de façon durable
    - Promotion saisonnière annoncée à date fixe
    - Prix d'entrée différent du prix courant, sans référence barrée
references:
  - title: Deceptive patterns — Fake urgency, Comparison prevention
    authors: Brignull
    url: https://www.deceptive.design/types
tags: [monétisation, prix, ancrage]
---

# Prix barré fictif

Une remise affichée par rapport à un prix qui n'a jamais réellement existé.

## Mécanisme

L'interface affiche un prix barré supérieur, et le prix demandé apparaît comme
une opportunité. L'ancrage opère avant tout raisonnement : le lecteur évalue
l'écart, pas la valeur.

Deux formes se rencontrent dans le jeu vidéo :

- **le prix de référence jamais pratiqué** — l'objet n'a jamais été proposé au
  tarif barré ;
- **la remise permanente** — la « promotion » ne s'interrompt jamais, ce qui
  fait du prix remisé le prix réel.

## Ce qui rend ce pattern vérifiable

C'est un des rares patterns dont la preuve est **historique et non
interprétative** : il suffit de montrer que le prix barré n'a pas été pratiqué.

Le corollaire est exigeant : **sans historique de prix, le claim ne tient pas**.
Une capture unique montrant « 40 € barré, 20 € » ne prouve rien du tout — la
remise peut être authentique.

## Comment le vérifier

Relever le prix affiché à intervalles réguliers sur plusieurs semaines, ou
utiliser un historique public de prix de plateforme lorsqu'il existe. Le constat
utile est soit « le prix barré n'apparaît jamais comme prix courant », soit « la
remise est ininterrompue sur toute la période observée ».

Chaque relevé doit être archivé séparément, avec sa date.

## Ce qui ne relève pas de ce pattern

Une remise réelle. Une promotion saisonnière annoncée. Un prix de lancement
inférieur au prix ultérieur — c'est l'inverse d'une fausse remise. Un objet cher
sans référence barrée.

## Œuvres documentées

Renseigné à l'ingestion depuis les relations `exhibits`.
