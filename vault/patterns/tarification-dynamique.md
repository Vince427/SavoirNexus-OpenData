---
type: pattern
id: tarification-dynamique
title: Tarification dynamique et profilage algorithmique
lang: fr
category: data
severity_base: 4
domains: [games]
aliases:
  - personalized pricing
  - tarification personnalisee
  - price discrimination
  - offre personnalisee dsa
psychology: >
  Exploite les données comportementales et la propension à payer de chaque
  individu pour ajuster prix, remises ou lots proposés afin de maximiser
  l'extraction financière à son insu.
criteria:
  includes:
    - Le prix ou la composition des promotions in-game varie d'un compte à un autre au même moment sur la même plateforme et devise selon le comportement ou l'historique d'achats
    - Des offres personnalisées ciblent les temps de stagnation, les défaites récentes ou les segments de dépense (« whales », mineurs)
    - Aucune information claire n'avertit le joueur qu'un prix affiché résulte d'une décision automatisée individualisée
  excludes:
    - Tarification régionale par pays/devise liée au pouvoir d'achat ou aux taxes locales, identique pour tous les comptes de la région
    - Promotion publique identique affichée à l'ensemble des joueurs sur la boutique
    - Offre de bienvenue unique documentée et identique pour tout nouveau compte
references:
  - title: Digital Services Act (DSA Art. 25, 26 & 28) & Digital Fairness Act Consultation
    authors: Union européenne
    year: 2024
  - regulation: /regulations/eu-digital-fairness-act
regulated_by:
  - /regulations/eu-digital-fairness-act
tags: [données, prix, profilage, dsa, europe]
---

# Tarification dynamique et profilage algorithmique

Variation individualisée des prix, lots ou promotions affichés à deux joueurs au même instant à partir du suivi de leur comportement ou historique de dépense.

## Mécanisme et cadre légal

Au titre du **Digital Services Act (DSA)** et du **Digital Fairness Act**, la personnalisation opaque des prix ou des incitations à l'achat fondée sur les vulnérabilités détectées (en particulier chez les mineurs) constitue une pratique encadrée ou proscrite dans l'Union européenne.

## Comment le vérifier

- Comparer simultanément les offres et tarifs d'une boutique sur deux comptes distincts dans la même région et sur la même plateforme.
- Consulter les politiques de confidentialité et brevets/communications techniques de l'éditeur mentionnant les « dynamic personalized offers ».
