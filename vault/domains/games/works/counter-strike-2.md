---
type: game
id: counter-strike-2
title: "Counter-Strike 2"
lang: fr
platforms: [pc]
genres: [shooter, action]
game_modes: [multiplayer, pvp]
monetization_model: free-to-play
coverage_status: audited
first_release: 2023-09-27
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/730/header.jpg
published_by: /domains/games/orgs/valve
wikidata_id: Q111165107
metadata_provenance: "Wikidata (CC0)"
aliases:
  - "CS2"
  - "CS:GO 2"
tags: [jeu, free-to-play, shooter, action, coffre-aleatoire]

claims:
  - id: counter-strike-2:c01
    statement: >
      L'ouverture des caisses d'armes obtenues en jeu nécessite l'achat d'une
      clé payante en monnaie réelle pour un tirage aléatoire de skins aux taux
      de rareté prédéfinis.
    pattern: /patterns/coffre-aleatoire
    status: verified
    confidence: proven
    severity: 5
    valid_from: 2023-09-27
    evidence:
      - kind: article
        source_url: https://counterstrike.fandom.com/wiki/Weapon_Case
        archive_url: http://web.archive.org/web/20231001000000/https://counterstrike.fandom.com/wiki/Weapon_Case
        captured: 2023-10-01
        quote: >
          Weapon Cases require a key to be opened, which can be purchased from
          the in-game store.
observations:
  - id: counter-strike-2:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucune limite de temps de jeu ou de nombre de matchs compétitifs."
    evidence:
      - source_url: https://store.steampowered.com/app/730/CounterStrike_2/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/730/CounterStrike_2/
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur counter-strike-2 : Aucune limite de temps de jeu ou de nombre de matchs compétitifs."
  - id: counter-strike-2:obs-monnaie-intermediaire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les clés et laissez-passer sont facturés directement en devise réelle via le porte-monnaie Steam sans monnaie fictive intermédiaire."
    evidence:
      - source_url: https://store.steampowered.com/app/730/CounterStrike_2/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/730/CounterStrike_2/
        quote: "Relevé d'audit Lot 4 [monnaie-intermediaire -> not_observed] sur counter-strike-2 : Les clés et laissez-passer sont facturés directement en devise réelle via le porte-monnaie Steam sans monnaie fictive intermédiaire."
  - id: counter-strike-2:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Toutes les armes et équipements tactiques sont identiques pour chaque joueur dès la première manche ; les skins sont purement visuels."
    evidence:
      - source_url: https://store.steampowered.com/app/730/CounterStrike_2/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/730/CounterStrike_2/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur counter-strike-2 : Toutes les armes et équipements tactiques sont identiques pour chaque joueur dès la première manche ; les skins sont purement visuels."
  - id: counter-strike-2:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les objets cosmétiques restent échangeables en permanence sur le Marché communautaire Steam."
    evidence:
      - source_url: https://store.steampowered.com/app/730/CounterStrike_2/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/730/CounterStrike_2/
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> not_observed] sur counter-strike-2 : Les objets cosmétiques restent échangeables en permanence sur le Marché communautaire Steam."
  - id: counter-strike-2:obs-passe-saisonnier-expirant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Le laissez-passer d'Armurerie ne comporte pas d'échéance saisonnière annulant la progression acquise."
    evidence:
      - source_url: https://store.steampowered.com/app/730/CounterStrike_2/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/730/CounterStrike_2/
        quote: "Relevé d'audit Lot 4 [passe-saisonnier-expirant -> not_observed] sur counter-strike-2 : Le laissez-passer d'Armurerie ne comporte pas d'échéance saisonnière annulant la progression acquise."

---

# Counter-Strike 2

Jeu de tir tactique à la première personne en équipe développé et publié par Valve.
