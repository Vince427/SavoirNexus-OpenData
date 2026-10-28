---
type: game
id: destiny-2
title: "Destiny 2"
lang: fr
platforms: [pc, playstation, xbox]
genres: [shooter, rpg, mmo]
game_modes: [multiplayer, co-op, pvp]
monetization_model: free-to-play
coverage_status: audited
first_release: 2017-09-06
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/1085660/header.jpg
published_by: /domains/games/orgs/bungie
wikidata_id: Q29045915
metadata_provenance: "Wikidata (CC0)"
tags: [jeu, free-to-play, shooter, rpg, mmo, passe-saisonnier-expirant, monnaie-intermediaire]

claims:
  - id: destiny-2:c01
    statement: >
      Les passes saisonniers (ou épisodes) comportent 100 paliers de
      récompenses dont la progression n'est plus accessible une fois l'événement
      saisonnier clos.
    pattern: /patterns/passe-saisonnier-expirant
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2019-10-01
    evidence:
      - kind: article
        source_url: https://www.bungie.net/7/en/Seasons
        archive_url: http://web.archive.org/web/20231001000000/https://www.bungie.net/7/en/Seasons
        captured: 2023-10-01
        quote: >
          Season Pass rewards must be earned before the season concludes.

  - id: destiny-2:c02
    statement: >
      L'achat de cosmétiques à la boutique Everversum s'effectue au moyen
      d'Argentum (Silver), monnaie achetable par paliers tarifaires prédéfinis.
    pattern: /patterns/monnaie-intermediaire
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2017-09-06
    evidence:
      - kind: article
        source_url: https://help.bungie.net/hc/en-us/articles/360049498251
        archive_url: http://web.archive.org/web/20231001000000/https://help.bungie.net/hc/en-us/articles/360049498251
        captured: 2023-10-01
        quote: >
          Silver is an in-game currency that can be spent in the Eververse store.
observations:
  - id: destiny-2:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Sessions de jeu illimitées sans système d'énergie payant."
    evidence:
      - source_url: https://store.steampowered.com/app/1085660/Destiny_2/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/1085660/Destiny_2/
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur destiny-2 : Sessions de jeu illimitées sans système d'énergie payant."
  - id: destiny-2:obs-coffre-aleatoire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les Engrammes brillants ne sont plus vendus contre de l'Argentum ; la boutique Everversum vend des ornements identifiés."
    evidence:
      - source_url: https://store.steampowered.com/app/1085660/Destiny_2/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/1085660/Destiny_2/
        quote: "Relevé d'audit Lot 4 [coffre-aleatoire -> not_observed] sur destiny-2 : Les Engrammes brillants ne sont plus vendus contre de l'Argentum ; la boutique Everversum vend des ornements identifiés."
  - id: destiny-2:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les achats en Argentum dans la boutique Everversum sont cosmétiques."
    evidence:
      - source_url: https://store.steampowered.com/app/1085660/Destiny_2/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/1085660/Destiny_2/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur destiny-2 : Les achats en Argentum dans la boutique Everversum sont cosmétiques."
  - id: destiny-2:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Rotation hebdomadaire du catalogue mis en avant dans la boutique Everversum."
    evidence:
      - source_url: https://store.steampowered.com/app/1085660/Destiny_2/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/1085660/Destiny_2/
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> observed] sur destiny-2 : Rotation hebdomadaire du catalogue mis en avant dans la boutique Everversum."

---

# Destiny 2

Jeu de tir à la première personne et MMO d'action cosmique développé par Bungie.
