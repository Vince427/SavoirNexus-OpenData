---
type: game
id: balatro
title: "Balatro"
lang: fr
platforms: [pc, playstation, xbox, nintendo-switch, ios, android]
genres: [card-game, puzzle, roguelike]
game_modes: [single-player]
monetization_model: premium
coverage_status: audited
first_release: 2024-02-20
wikidata_id: Q124357469
wikidata_status: verified
metadata_provenance: "Wikidata (CC0)"
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/2379780/header.jpg
published_by: /domains/games/orgs/playstack
observations:
  - id: balatro:obs-coffre-aleatoire-01
    author: audit-indies-batch1
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-indies-batch1-gameplay-audit.md
    statement: "Les boosters de cartes (Arcanes, Célestes, Standard, Bouffon) s'achètent exclusivement dans le magasin de run avec les dollars fictifs gagnés lors des blinds. Zéro achat avec de l'argent réel."
    evidence:
      - source_url: https://store.steampowered.com/app/2379780/Balatro/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/2379780/Balatro/
        quote: "Audit structurel [coffre-aleatoire] sur balatro : achat unique premium sans caisses de butin aléatoires ni tirages payants."
  - id: balatro:obs-monnaie-intermediaire-01
    author: audit-indies-batch1
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-indies-batch1-gameplay-audit.md
    statement: "Aucun achat intégré de monnaie virtuelle. Les dollars en jeu sont strictement limités à la partie en cours."
    evidence:
      - source_url: https://store.steampowered.com/app/2379780/Balatro/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/2379780/Balatro/
        quote: "Audit structurel [monnaie-intermediaire] sur balatro : économie strictement interne au gameplay sans vente de devises virtuelles."
  - id: balatro:obs-passe-saisonnier-expirant-01
    author: audit-indies-batch1
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-indies-batch1-gameplay-audit.md
    statement: "Zéro passe de combat ou contenu sous calendrier d'expiration."
    evidence:
      - source_url: https://store.steampowered.com/app/2379780/Balatro/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/2379780/Balatro/
        quote: "Audit structurel [passe-saisonnier-expirant] sur balatro : contenu intégralement pérenne sans passe saisonnier expirant."
  - id: balatro:obs-fausse-urgence-01
    author: audit-indies-batch1
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-indies-batch1-gameplay-audit.md
    statement: "Absence de décompte commercial ou de FOMO ; le joueur prend tout le temps souhaité pour analyser ses mains."
    evidence:
      - source_url: https://store.steampowered.com/app/2379780/Balatro/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/2379780/Balatro/
        quote: "Audit structurel [fausse-urgence] sur balatro : absence de boutique éphémère ou de compte à rebours promotionnel."
  - id: balatro:obs-avantage-competitif-payant-01
    author: audit-indies-batch1
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-indies-batch1-gameplay-audit.md
    statement: "Jeu solo pur ; aucun bonus payant n'existe."
    evidence:
      - source_url: https://store.steampowered.com/app/2379780/Balatro/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/2379780/Balatro/
        quote: "Audit structurel [avantage-competitif-payant] sur balatro : progression fondée uniquement sur le jeu sans avantage achetable."
  - id: balatro:obs-systeme-energie-01
    author: audit-indies-batch1
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-indies-batch1-gameplay-audit.md
    statement: "Runs illimités, zéro temps de rechargement artificiel."
    evidence:
      - source_url: https://store.steampowered.com/app/2379780/Balatro/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/2379780/Balatro/
        quote: "Audit structurel [systeme-energie] sur balatro : accès continu aux parties sans système de vies ou d'énergie payant."

---

# Balatro

Rogue-like hypnotique basé sur le poker et les synergies de cartes Joker surpuissantes.
