---
type: pattern
id: probabilites-opaques
title: Probabilités de tirage opaques ou dynamiques
lang: fr
category: monetization
severity_base: 4
domains: [games]
aliases:
  - rigged drop rates
  - taux caches
  - probabilites dynamiques
  - hidden odds
psychology: >
  Exploite l'asymétrie d'information et l'illusion de contrôle. Lorsque les
  probabilités exactes ne sont pas affichées avant la dépense ou varient selon
  des paramètres cachés, le joueur ne peut pas évaluer rationnellement le coût
  espéré d'un objet ou l'équité du tirage.
criteria:
  includes:
    - Des mécanismes aléatoires payants n'affichent aucune grille complète et chiffrée des probabilités directement au moment de l'achat
    - Les chances d'obtention sont modulées dynamiquement selon le profil du joueur, l'historique d'achats ou des seuils non documentés
    - Les chances publiées agrègent des paliers de rareté sans détailler le poids individuel des récompenses phares
  excludes:
    - Tirage payant affichant explicitement et avant paiement les taux exacts de chaque objet et règle de garantie (pity) vérifiable
    - Tirage purement gratuit interne au gameplay sans aucun lien direct ni indirect avec de l'argent réel
    - Boutique à prix ferme sans composante aléatoire
references:
  - title: Digital Fairness Check & Loot Box Odds Transparency Guidelines
    authors: Commission européenne (DG JUST) / PEGI
    year: 2024
  - regulation: /regulations/eu-digital-fairness-act
regulated_by:
  - /regulations/eu-digital-fairness-act
  - /regulations/be-loot-boxes-2018
tags: [monétisation, hasard, probabilités, transparence, europe]
---

# Probabilités de tirage opaques ou dynamiques

Dissimulation des taux réels d'obtention ou variation algorithmique cachée des chances dans un tirage payant (loot box, gacha, paquet de cartes).

## Différence avec `coffre-aleatoire`

`coffre-aleatoire` constate la présence même d'un mécanisme de hasard payant. `probabilites-opaques` documente l'opacité aggravée : absence de tableau de probabilités accessible avant achat, taux agrégés trompeurs ou ajustement dynamique dissimulé des chances.

## Comment le vérifier

- Ouvrir l'écran d'achat du tirage et chercher un bouton ou lien « Taux / Probabilités » accessible avant toute dépense.
- Vérifier que les taux indiqués couvrent chaque objet individuellement et pas uniquement une catégorie large.
- Recenser les notes de version ou enquêtes réglementaires documentant une divergence entre taux affichés et taux observés.
