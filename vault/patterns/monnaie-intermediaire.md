---
type: pattern
id: monnaie-intermediaire
title: Monnaie intermédiaire
lang: fr
category: monetization
severity_base: 4
domains: [games]
aliases:
  - monnaie premium
  - premium currency
  - devise virtuelle
psychology: >
  Découple l'acte d'achat de l'acte de dépense, ce qui atténue la douleur de
  payer. La conversion en monnaie réelle exige un calcul mental que
  l'incommensurabilité des paquets rend délibérément coûteux.
criteria:
  includes:
    - Les paquets vendus ne correspondent à aucune combinaison exacte des prix pratiqués
    - Le prix en monnaie réelle n'est pas affiché au moment de dépenser
    - Un solde résiduel inutilisable subsiste après achat
  excludes:
    - Monnaie gagnée en jouant et non achetable
    - Grille de paquets couvrant exactement les prix des articles
    - Achat direct en monnaie réelle, prix affiché
references:
  - title: Deceptive patterns — Currency confusion
    authors: Brignull
    url: https://www.deceptive.design/types
  - title: Dark patterns in the design of games — monetary dark patterns
    authors: Zagal, Björk, Lewis
    venue: Foundations of Digital Games
    year: 2013
tags: [monétisation, opacité, prix]
---

# Monnaie intermédiaire

Une devise interne achetée en paquets, dont les **dénominations ne coïncident
jamais** avec les prix des articles.

## Mécanisme

Le joueur ne dépense jamais d'euros : il dépense des gemmes, des crédits, des
pièces. Deux effets se cumulent.

D'abord, l'atténuation : payer avec une monnaie déjà achetée ne déclenche pas la
même résistance qu'un débit en euros. La dépense a été consentie plus tôt, sur
un montant global, dans un autre contexte de décision.

Ensuite, l'opacité : quand les paquets se vendent par 500, 1 200 et 2 500, et
que les articles coûtent 800, la conversion vers l'euro demande un calcul que
personne ne fait au moment d'acheter.

## Le résidu, et pourquoi il n'est pas accidentel

L'incommensurabilité produit systématiquement un **solde résiduel** — trop petit
pour acheter quoi que ce soit, trop visible pour être oublié. Ce solde est un
levier : il rend le prochain achat de paquet plus probable, puisqu'il « ne
manque plus que » quelques unités.

C'est ce qui distingue ce pattern d'une simple commodité de paiement. Un système
de monnaie dont les paquets couvriraient exactement les prix pratiqués ne
produirait pas de résidu. Sa persistance à travers les rééditions et les mises à
jour est l'indice le plus solide du caractère délibéré.

## Comment le vérifier

Relever la grille complète des paquets et la grille complète des prix, à la même
date, et vérifier qu'aucune combinaison de paquets ne permet d'atteindre un
solde nul sur les articles courants.

Ce constat est arithmétique, donc opposable : c'est l'un des rares claims de
monétisation qui peut légitimement porter `confidence: proven` sans dépendre de
l'interprétation.

## Ce qui ne relève pas de ce pattern

Une monnaie gagnée en jouant et non achetable. Un système où les paquets
correspondent aux prix. Un abonnement libellé en euros. Documenter ces cas
comme monnaie intermédiaire serait une erreur d'analyse.
