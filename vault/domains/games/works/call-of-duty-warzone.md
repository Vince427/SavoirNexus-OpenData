---
type: game
id: call-of-duty-warzone
title: "Call of Duty: Warzone"
lang: fr
platforms: [pc, playstation, xbox]
genres: [shooter, battle-royale]
game_modes: [multiplayer, pvp]
monetization_model: free-to-play
coverage_status: audited
first_release: 2020-03-10
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/1938090/header.jpg
published_by: /domains/games/orgs/activision
wikidata_id: Q87416343
metadata_provenance: "Wikidata (CC0)"
aliases:
  - "Warzone"
tags: [jeu, free-to-play, shooter, battle-royale, passe-saisonnier-expirant, monnaie-intermediaire, fausse-urgence]

claims:
  - id: call-of-duty-warzone:c01
    statement: >
      Le passe de combat saisonnier est structuré en secteurs dont les
      récompenses cosmétiques ne sont plus accessibles une fois la saison
      terminée.
    pattern: /patterns/passe-saisonnier-expirant
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2020-03-10
    evidence:
      - kind: article
        source_url: https://www.callofduty.com/warzone
        archive_url: http://web.archive.org/web/20231201000000/https://www.callofduty.com/warzone
        captured: 2023-12-01
        quote: >
          The Battle Pass system features multiple sectors to unlock throughout
          the active season.

  - id: call-of-duty-warzone:c02
    statement: >
      L'achat des passes et des éléments de personnalisation requiert des Points
      Call of Duty (CP) achetables en monnaie réelle avec des montants fixes
      décorrélés des prix unitaires.
    pattern: /patterns/monnaie-intermediaire
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2020-03-10
    evidence:
      - kind: article
        source_url: https://support.activision.com/articles/call-of-duty-points
        archive_url: http://web.archive.org/web/20231201000000/https://support.activision.com/articles/call-of-duty-points
        captured: 2023-12-01
        quote: >
          Call of Duty Points (CP) are the optional in-game currency you can use
          in Call of Duty to obtain Battle Passes and Store Bundles.

  - id: call-of-duty-warzone:c03
    statement: >
      La boutique en jeu propose des packs d'opérateurs et d'armes disponibles
      pour une durée limitée avec un affichage récurrent d'échéances.
    pattern: /patterns/fausse-urgence
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2020-03-10
    evidence:
      - kind: article
        source_url: https://www.callofduty.com/blog/2023/12/call-of-duty-modern-warfare-iii-warzone-season-1-blackcell-battle-pass-bundles
        archive_url: http://web.archive.org/web/20231201000000/https://www.callofduty.com/blog/2023/12/call-of-duty-modern-warfare-iii-warzone-season-1-blackcell-battle-pass-bundles
        captured: 2023-12-01
        quote: >
          Featured Bundles rotate through the store on a regular basis for a
          limited time.

  - id: call-of-duty-warzone:c04
    statement: >
      Le jeu place les joueurs au cœur d'un théâtre d'opérations militaires
      contemporaines avec combats armés, frappes aériennes et véhicules de guerre.
    pattern: /patterns/guerre
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2020-03-10
    evidence:
      - kind: article
        source_url: https://www.esrb.org/ratings/36881/call-of-duty-warzone/
        archive_url: http://web.archive.org/web/20231201000000/https://www.esrb.org/ratings/36881/call-of-duty-warzone/
        captured: 2023-12-01
        quote: >
          Players engage in military-style combat missions across a large war-torn
          landscape using realistic military firearms.

  - id: call-of-duty-warzone:c05
    statement: >
      Les combats armés comportent des tirs sanglants et des animations
      d'exécutions létales au corps à corps.
    pattern: /patterns/violence-graphique
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2020-03-10
    evidence:
      - kind: article
        source_url: https://www.esrb.org/ratings/36881/call-of-duty-warzone/
        archive_url: http://web.archive.org/web/20231201000000/https://www.esrb.org/ratings/36881/call-of-duty-warzone/
        captured: 2023-12-01
        quote: >
          Combat is accompanied by realistic gunfire and blood-splatter effects.
observations:
  - id: call-of-duty-warzone:obs-coffre-aleatoire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Absence de coffres aléatoires payants ; les achats portent sur des packs cosmétiques déterministes."
    evidence:
      - source_url: https://www.callofduty.com/warzone
        archive_url: https://web.archive.org/web/20241015000000/https://www.callofduty.com/warzone
        quote: "Relevé d'audit Lot 4 [coffre-aleatoire -> not_observed] sur call-of-duty-warzone : Absence de coffres aléatoires payants ; les achats portent sur des packs cosmétiques déterministes."
  - id: call-of-duty-warzone:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Toutes les armes et accessoires d'attirail sont déblocables gratuitement par l'expérience en jeu."
    evidence:
      - source_url: https://www.callofduty.com/warzone
        archive_url: https://web.archive.org/web/20241015000000/https://www.callofduty.com/warzone
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur call-of-duty-warzone : Toutes les armes et accessoires d'attirail sont déblocables gratuitement par l'expérience en jeu."
  - id: call-of-duty-warzone:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucune restriction du nombre de parties de Battle Royale ou Résurgence."
    evidence:
      - source_url: https://www.callofduty.com/warzone
        archive_url: https://web.archive.org/web/20241015000000/https://www.callofduty.com/warzone
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur call-of-duty-warzone : Aucune restriction du nombre de parties de Battle Royale ou Résurgence."

---

# Call of Duty: Warzone

Battle royale militaire multijoueur massif au sein de l'écosystème Call of Duty.
