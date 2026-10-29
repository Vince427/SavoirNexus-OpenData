---
type: pattern
id: resiliation-difficile
title: Résiliation difficile
lang: fr
category: interface
severity_base: 4
domains: [games, software, services]
aliases:
  - hard to cancel
  - roach motel
  - piège à cafards
  - désabonnement obstrué
psychology: >
  Exploite l'asymétrie d'effort : chaque obstacle ajouté sur le chemin de
  sortie augmente la probabilité d'abandon de la démarche, et donc d'un
  prélèvement supplémentaire. La friction n'a pas besoin d'être infranchissable,
  seulement d'excéder l'énergie disponible au moment où l'utilisateur y pense.
criteria:
  includes:
    - L'abonnement se souscrit en ligne mais se résilie par un autre canal
    - Le parcours de résiliation compte plus d'étapes que celui de souscription
    - Des propositions de rétention s'intercalent avant la confirmation
    - La commande de résiliation est absente des emplacements attendus
  excludes:
    - Confirmation unique demandée avant résiliation
    - Délai de préavis annoncé lors de la souscription
    - Résiliation en ligne accessible en un nombre d'étapes comparable
references:
  - title: Deceptive patterns — Hard to cancel, Obstruction
    authors: Brignull
    url: https://www.deceptive.design/types
tags: [interface, abonnement, obstruction]
---

# Résiliation difficile

Un abonnement facile à prendre et pénible à quitter.

## Mécanisme

L'asymétrie est le pattern lui-même. Souscrire demande deux clics ; résilier
demande de trouver une page non liée, de traverser trois écrans de rétention, ou
de passer par un canal différent de celui de la souscription.

Aucun obstacle n'est individuellement insurmontable. C'est leur **accumulation**
qui produit l'effet, et chaque mois d'abandon de la démarche est un prélèvement
supplémentaire.

## Pourquoi c'est le plus mesurable de tous

Ce pattern a une propriété rare : il se quantifie par un **nombre entier**, sans
interprétation.

```
étapes pour souscrire :  2
étapes pour résilier  :  7
```

Un écart de cette nature n'a pas de justification technique. Il ne se conteste
pas sur le terrain de l'appréciation, seulement sur celui du comptage — et le
comptage se refait.

## Comment le vérifier

Capturer les deux parcours complets, écran par écran, en comptant les étapes.
Relever aussi le **canal** : souscription en ligne et résiliation par téléphone
ou courrier constitue à soi seul le constat.

Noter les écrans de rétention et leur formulation — ils relèvent souvent
simultanément du [confirmshaming](/patterns/confirmshaming).

## Une réserve à garder

Ce pattern relève dans plusieurs juridictions du droit de la consommation, avec
des obligations précises sur la symétrie des parcours. Une fiche peut le
documenter comme pratique observable ; **elle ne doit pas conclure à
l'illégalité** — c'est le rôle des juridictions, et le rattachement à une
régulation suffit à informer le lecteur.

## Ce qui ne relève pas de ce pattern

Une confirmation unique. Un préavis annoncé à la souscription. Une résiliation
en ligne accessible en un nombre d'étapes comparable à celui de la souscription.

## Œuvres documentées

Renseigné à l'ingestion depuis les relations `exhibits`.
