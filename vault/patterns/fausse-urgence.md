---
type: pattern
id: fausse-urgence
title: Fausse urgence
lang: fr
category: urgency
severity_base: 3
domains: [games, ecommerce, media]
aliases:
  - urgence artificielle
  - false urgency
  - faux compte à rebours
psychology: >
  Exploite l'aversion à la perte et la réactance temporelle : la perspective de
  perdre une opportunité pèse plus lourd, dans la décision, que la perspective
  d'un gain équivalent. La contrainte de temps réduit la délibération et
  favorise l'achat impulsif.
criteria:
  includes:
    - Le compte à rebours se réinitialise sans que l'offre change
    - La rareté annoncée porte sur un bien numérique, par nature non fini
    - L'offre « expirée » réapparaît à l'identique
    - L'échéance apparaît au moment de la décision, non en amont
  excludes:
    - Promotion saisonnière annoncée à date fixe, identique pour tous
    - Rareté portant sur un bien réellement fini (places, exemplaires physiques)
    - Échéance qui, une fois passée, fait réellement disparaître l'offre
references:
  - title: Deceptive patterns — Fake urgency, Fake scarcity
    authors: Brignull
    url: https://www.deceptive.design/types
  - title: Dark patterns in the design of games — temporal dark patterns
    authors: Zagal, Björk, Lewis
    venue: Foundations of Digital Games
    year: 2013
tags: [monétisation, temps, pression]
---

# Fausse urgence

Une contrainte temporelle **présentée comme réelle alors qu'elle ne l'est pas**,
ou qu'elle est reconductible à volonté par celui qui l'affiche.

## Mécanisme

L'interface annonce qu'une offre expire — compte à rebours, stock limité, « plus
que 2 places ». La contrainte est fabriquée : elle se réinitialise à chaque
visite, se répète à intervalle fixe, ou porte sur un bien numérique dont le
stock est par nature illimité.

Le joueur ne dispose d'aucun moyen de vérifier la contrainte depuis
l'interface. C'est précisément ce qui distingue la fausse urgence d'une
promotion réellement limitée, qui est légitime.

## Ce qui distingue une urgence légitime d'une fausse

| Légitime | Fausse |
|---|---|
| L'échéance est identique pour tous les utilisateurs | Le compte à rebours dépend de la session |
| La rareté porte sur un bien réellement fini | Le « stock » d'un bien numérique |
| L'échéance passée, l'offre disparaît vraiment | L'offre « expirée » revient à l'identique |
| L'échéance est annoncée en amont | Elle apparaît au moment de la décision |

Une promotion saisonnière annoncée à date fixe n'est pas un dark pattern. La
documenter comme tel serait une erreur d'analyse, et le genre de claim qu'une
réclamation d'éditeur ferait tomber à juste titre.

## Comment le vérifier

Le test décisif est la **reproductibilité** : ouvrir l'offre dans une session
neuve. Si le compte à rebours repart de sa valeur initiale, la contrainte est
fabriquée. Capture des deux états, horodatée, archivée.

Sans ces deux captures, un claim de fausse urgence est au mieux `inferred` — et
il ne survivra pas à une réclamation.

## Œuvres documentées

Renseigné automatiquement à l'ingestion depuis les relations `exhibits`.
