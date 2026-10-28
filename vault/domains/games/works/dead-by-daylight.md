---
type: game
id: dead-by-daylight
title: "Dead by Daylight"
lang: fr
platforms: [pc, playstation, xbox, nintendo-switch]
genres: [horror, action]
game_modes: [multiplayer, pvp]
monetization_model: premium-plus-mtx
coverage_status: audited
first_release: 2016-06-14
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/381210/header.jpg
published_by: /domains/games/orgs/behaviour-interactive
wikidata_id: Q24514682
metadata_provenance: "Wikidata (CC0)"
aliases:
  - "DBD"
tags: [jeu, premium-plus-mtx, horror, action, passe-saisonnier-expirant, monnaie-intermediaire, horreur, violence-graphique]

claims:
  - id: dead-by-daylight:c01
    statement: >
      Le système de passe saisonnier (La Faille) propose des récompenses
      cosmétiques réparties sur plusieurs dizaines de paliers qui expirent à la
      fin du cycle saisonnier.
    pattern: /patterns/passe-saisonnier-expirant
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2019-10-22
    evidence:
      - kind: article
        source_url: https://deadbydaylight.fandom.com/wiki/The_Rift
        archive_url: http://web.archive.org/web/20231001000000/https://deadbydaylight.fandom.com/wiki/The_Rift
        captured: 2023-10-01
        quote: >
          The Rift is a seasonal track system that closes at the end of each
          Tome.

  - id: dead-by-daylight:c02
    statement: >
      Les Cellules d'aura constituent la monnaie achetable en argent réel
      nécessaire pour débloquer les personnages sous licence et les passes de
      combat.
    pattern: /patterns/monnaie-intermediaire
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2018-06-12
    evidence:
      - kind: article
        source_url: https://deadbydaylight.fandom.com/wiki/Auric_Cells
        archive_url: http://web.archive.org/web/20231001000000/https://deadbydaylight.fandom.com/wiki/Auric_Cells
        captured: 2023-10-01
        quote: >
          Auric Cells are an in-game currency that can only be obtained through
          purchases with real money.

  - id: dead-by-daylight:c03
    statement: >
      L'ambiance générale et le gameplay sont entièrement fondés sur les codes
      du cinéma d'horreur slasher, avec traque anxiogène et climat de terreur.
    pattern: /patterns/horreur
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2016-06-14
    evidence:
      - kind: article
        source_url: https://www.esrb.org/ratings/34947/dead-by-daylight/
        archive_url: http://web.archive.org/web/20231001000000/https://www.esrb.org/ratings/34947/dead-by-daylight/
        captured: 2023-10-01
        quote: >
          Blood and Gore, Intense Violence, Strong Language. Players take on the
          role of a killer stalking survivors.

  - id: dead-by-daylight:c04
    statement: >
      Le jeu met en scène des exécutions sanglantes explicites (Mementos Mori),
      des empalements sur crochets et des mutilations visuelles.
    pattern: /patterns/violence-graphique
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2016-06-14
    evidence:
      - kind: article
        source_url: https://www.esrb.org/ratings/34947/dead-by-daylight/
        archive_url: http://web.archive.org/web/20231001000000/https://www.esrb.org/ratings/34947/dead-by-daylight/
        captured: 2023-10-01
        quote: >
          Characters are impaled on meat hooks, and killers execute graphic
          murder animations against survivors.
observations:
  - id: dead-by-daylight:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucune jauge d'endurance ne limite l'enchaînement des parties."
    evidence:
      - source_url: https://store.steampowered.com/app/381210/Dead_by_Daylight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/381210/Dead_by_Daylight/
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur dead-by-daylight : Aucune jauge d'endurance ne limite l'enchaînement des parties."
  - id: dead-by-daylight:obs-coffre-aleatoire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "La Toile de sang utilise uniquement des Points de sang gagnés en jouant, non achetables en argent réel."
    evidence:
      - source_url: https://store.steampowered.com/app/381210/Dead_by_Daylight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/381210/Dead_by_Daylight/
        quote: "Relevé d'audit Lot 4 [coffre-aleatoire -> not_observed] sur dead-by-daylight : La Toile de sang utilise uniquement des Points de sang gagnés en jouant, non achetables en argent réel."
  - id: dead-by-daylight:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les personnages sous licence dotés de compétences uniques (Perks) utilisables en PvP ne sont déblocables immédiatement qu'en argent réel ou Cellules d'aura."
    evidence:
      - source_url: https://store.steampowered.com/app/381210/Dead_by_Daylight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/381210/Dead_by_Daylight/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> observed] sur dead-by-daylight : Les personnages sous licence dotés de compétences uniques (Perks) utilisables en PvP ne sont déblocables immédiatement qu'en argent réel ou Cellules d'aura."
  - id: dead-by-daylight:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Le Temple des Secrets effectue une rotation hebdomadaire de 4 compétences et la boutique affiche des promotions temporaires."
    evidence:
      - source_url: https://store.steampowered.com/app/381210/Dead_by_Daylight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/381210/Dead_by_Daylight/
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> observed] sur dead-by-daylight : Le Temple des Secrets effectue une rotation hebdomadaire de 4 compétences et la boutique affiche des promotions temporaires."

---

# Dead by Daylight

Jeu d'horreur multijoueur asymétrique (4 contre 1) développé par Behaviour Interactive.
