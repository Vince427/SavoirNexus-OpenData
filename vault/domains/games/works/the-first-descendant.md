---
type: game
id: the-first-descendant
title: "The First Descendant"
lang: fr
platforms: [pc, playstation-5, playstation-4, xbox-series, xbox-one]
genres: [shooter, looter-shooter, action, rpg]
game_modes: [multiplayer, co-op]
monetization_model: free-to-play
publication_status: released
coverage_status: audited
first_release: 2024-07-02
cover_url: https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/2074920/dc8ac02c8328d66f2f78ea8b83472bdd7e281a62/header.jpg?t=1789716956
published_by: /domains/games/orgs/nexon
storefronts: [steam]
metadata_provenance: "Steam Storefront API (App 2074920)"
tags: [jeu, shooter, looter-shooter, action, rpg, co-op, free-to-play, nexon, passe-saisonnier, monnaie-virtuelle, fausse-urgence, avantage-competitif-payant]
observations:
  - id: the-first-descendant:obs-coffre-aleatoire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-11-07"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-steam-storefront-audit-1220.md
    statement: "Pas de système de loot box payante à tirage aveugle direct dans la boutique (achats directs de personnages et cosmétiques)."
    evidence:
      - source_url: https://store.steampowered.com/app/2074920/
        archive_url: https://web.archive.org/web/20261107000000/https://store.steampowered.com/app/2074920/
        quote: "Boutique Steam App 2074920 : Les objets et personnages sont achetables à l'unité en boutique sans coffre aléatoire payant direct."
  - id: the-first-descendant:obs-monnaie-intermediaire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: observed
    checked_at: "2026-11-07"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-steam-storefront-audit-1220.md
    statement: "Utilisation du Caliber, monnaie virtuelle payante vendue par paliers asymétriques pour masquer les tarifs réels."
    evidence:
      - source_url: https://store.steampowered.com/app/2074920/
        archive_url: https://web.archive.org/web/20261107000000/https://store.steampowered.com/app/2074920/
        quote: "Le Caliber est vendu par packs (250, 520, 1060, etc.) dont les montants ne correspondent pas exactement aux prix unitaires des articles en boutique."
  - id: the-first-descendant:obs-passe-saisonnier-expirant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: observed
    checked_at: "2026-11-07"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-steam-storefront-audit-1220.md
    statement: "Présence d'un Battle Pass saisonnier payant avec compte à rebours et récompenses expirantes."
    evidence:
      - source_url: https://store.steampowered.com/app/2074920/
        archive_url: https://web.archive.org/web/20261107000000/https://store.steampowered.com/app/2074920/
        quote: "Système de passe de combat à paliers payants avec fenêtre de validité saisonnière stricte créant une pression temporelle au jeu."
  - id: the-first-descendant:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-11-07"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-steam-storefront-audit-1220.md
    statement: "Boutique rotative à compte à rebours créant une urgence d'achat sur des skins et packs temporaires."
    evidence:
      - source_url: https://store.steampowered.com/app/2074920/
        archive_url: https://web.archive.org/web/20261107000000/https://store.steampowered.com/app/2074920/
        quote: "Présence de bannières avec décompte temporel pour les cosmétiques exclusifs de saison incitant à l'achat rapide."
  - id: the-first-descendant:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: observed
    checked_at: "2026-11-07"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-steam-storefront-audit-1220.md
    statement: "Vente directe de Légataires Ultimes, d'activateurs d'énergie et de catalyseurs augmentant directement la puissance des builds."
    evidence:
      - source_url: https://store.steampowered.com/app/2074920/
        archive_url: https://web.archive.org/web/20261107000000/https://store.steampowered.com/app/2074920/
        quote: "La boutique permet d'acquérir immédiatement des Légataires Ultimes et composants de puissance sans passer par le grind intensif de matériaux."
  - id: the-first-descendant:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-11-07"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-steam-storefront-audit-1220.md
    statement: "Looter-shooter jouable en continu sans barre d'énergie limitant le nombre de parties."
    evidence:
      - source_url: https://store.steampowered.com/app/2074920/
        archive_url: https://web.archive.org/web/20261107000000/https://store.steampowered.com/app/2074920/
        quote: "Les missions d'Infiltration et de Colosses sont accessibles sans restriction de jauge d'endurance horaire."
---

# The First Descendant

The First Descendant est un jeu de tir et de butin (looter-shooter) coopératif à la troisième personne développé par Nexon Games sous Unreal Engine 5.

Adoptant un modèle free-to-play, le titre repose sur une économie à base de monnaie intermédiaire (Caliber), de passes saisonniers expirants, de vitrines marchandes à durée limitée et d'achats directs d'éléments influant sur la puissance en jeu.
