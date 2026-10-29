---
type: pattern
id: achat-accidentel
title: Achat accidentel par interface
lang: fr
category: interface
severity_base: 4
domains: [games, software]
aliases:
  - achat non intentionnel
  - accidental purchase
  - interface de facturation trompeuse
psychology: >
  Exploite l'automatisme moteur : un joueur ayant répété des milliers de fois
  une combinaison de touches ne relit pas l'écran avant d'appuyer. Placer une
  action facturante là où l'habitude attend une action neutre produit un
  consentement de façade.
criteria:
  includes:
    - Une action facturante partage sa commande avec une action non facturante
    - L'achat s'effectue sans étape de confirmation distincte
    - La disposition des commandes varie d'un écran à l'autre sans logique apparente
    - Une action ordinaire (sortie de veille, prévisualisation) peut déclencher un achat
  excludes:
    - Achat en un clic explicitement activé par l'utilisateur dans ses réglages
    - Confirmation supprimée après un avertissement clair et réversible
references:
  - title: "FTC — ordonnance Epic Games : configuration des commandes et consentement affirmatif"
    year: 2023
    regulation: /regulations/us-ftc-epic-2023
  - title: Deceptive patterns — Visual interference, Trick wording
    authors: Brignull
    url: https://www.deceptive.design/types
regulated_by:
  - /regulations/us-ftc-epic-2023
tags: [interface, facturation, consentement, régulé]
---

# Achat accidentel par interface

Une disposition de commandes qui transforme un geste ordinaire en transaction.

## Mécanisme

Le pattern ne cache pas le prix : il **déplace le consentement**. L'achat reste
affiché, mais il se déclenche à un endroit où l'utilisateur n'attend pas une
facturation — la même touche qu'ailleurs sert à confirmer, à annuler, ou
simplement à continuer.

Trois variantes se rencontrent :

- **la commande partagée** : la touche d'achat est celle de l'action courante ;
- **l'incohérence** : la position du bouton d'achat change d'un écran à l'autre ;
- **la facturation par action neutre** : sortir de veille, prévisualiser un objet.

## Pourquoi ce pattern est particulier

C'est le seul du fonds à avoir donné lieu à une **sanction financière majeure
explicitement fondée sur la notion de dark pattern** — voir
[l'ordonnance FTC de 2023](/regulations/us-ftc-epic-2023).

Il fournit donc un critère juridique réutilisable : le **consentement
affirmatif**. Une interface qui ne l'obtient pas est attaquable, indépendamment
de toute appréciation esthétique sur son design.

## Comment le vérifier

Filmer ou capturer la séquence complète, de l'écran neutre jusqu'au débit. La
preuve utile n'est pas l'écran de boutique : c'est **l'enchaînement** qui montre
qu'aucune étape de confirmation distincte n'intervient.

Relever aussi la position du bouton d'achat sur trois écrans différents.
L'incohérence entre eux est objective et se documente en trois captures.

## Ce qui ne relève pas de ce pattern

Un achat en un clic que l'utilisateur a délibérément activé. Une confirmation
retirée après avertissement explicite et réversible. Un prix élevé mais
clairement affiché avant validation — c'est peut-être cher, ce n'est pas
trompeur.

## Œuvres documentées

Renseigné à l'ingestion depuis les relations `exhibits`.
