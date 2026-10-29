---
type: pattern
id: paquet-force
title: Paquet forcé
lang: fr
category: monetization
severity_base: 4
domains: [games]
aliases:
  - forced bundling
  - lot forcé
  - achat forcé de surplus
  - solde résiduel captif
psychology: >
  Exploite l'incommensurabilité des prix et l'effet de dotation. Le joueur est contraint
  d'acheter plus de devise virtuelle que nécessaire pour obtenir l'article désiré.
  Le solde résiduel captif active l'aversion au gaspillage et pousse à de nouveaux achats récurrents.
criteria:
  includes:
    - Les paliers de devises virtuelles vendus ne correspondent à aucune combinaison exacte des prix pratiqués
    - L'achat d'un article impose systématiquement l'achat d'un paquet supérieur laissant un reliquat inexploitable
    - Impossibilité de payer le prix exact de l'article en monnaie réelle au centime près
  excludes:
    - Achat direct de l'article en monnaie réelle au prix exact affiché
    - Boutique où les paliers de monnaie permettent d'acquérir le montant exact sans surplus forcé
    - Monnaies obtenues uniquement via la progression en jeu sans passerelle d'achat payante
references:
  - title: "Monetising Play: Regulating in-game and in-app premium currencies"
    authors: BEUC (The European Consumer Organisation)
    url: https://www.beuc.eu/publications/monetising-play-regulating-game-and-app-premium-currencies
    year: 2024
  - title: Dark patterns in the design of games — monetary dark patterns
    authors: Zagal, Björk, Lewis
    venue: Foundations of Digital Games
    year: 2013
tags: [monétisation, prix, opacité, devises]
---

# Paquet forcé

Une structuration des lots de devises virtuelles qui oblige à acheter un surplus financier et enferme le joueur dans un solde résiduel perpétuel.

## Mécanisme

Lorsqu'un cosmétique ou un objet coûte 1 200 unités virtuelles, la boutique ne propose à la vente que des paquets de 1 000 ou 2 800 unités. Le joueur est dans l'obligation de payer pour le lot supérieur.

Ce mécanisme produit un double préjudice :
1. **Le surcoût forcé immédiat** : Le joueur paie plus cher que la valeur faciale de l'objet désiré.
2. **Le piège du solde résiduel captif (Leftover trap)** : Après l'achat, il reste des crédits insuffisants pour acheter quoi que ce soit d'autre, mais suffisants pour créer une incitation psychologique à « compléter le solde » lors d'un prochain achat.

## Régulation et dénonciation

Ce pattern a été formellement dénoncé en **septembre 2024** par le **BEUC** (Bureau Européen des Unions de Consommateurs) dans sa plainte paneuropéenne contre les principaux éditeurs de jeux vidéo (Epic Games, EA, Supercell, Ubisoft, Roblox), le qualifiant de pratique commerciale trompeuse en violation du droit européen de la consommation.

## Comment le vérifier

- Relever le prix en devise virtuelle de plusieurs articles populaires de la boutique.
- Comparer ces prix aux paliers d'achat de devises proposés.
- Constater s'il est techniquement impossible d'acheter l'objet sans accumuler un surplus de devise résiduel.
