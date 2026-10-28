---
type: game
id: hearts-of-iron-iv
title: Hearts of Iron IV
lang: fr
platforms: [pc]
genres: [simulation, strategy]
game_modes: [single-player, multiplayer, co-op]
monetization_model: premium
coverage_status: audited
first_release: 2016-06-06
cover_url: https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/394360/67bbd0057627fc2244793bcdd09260c2539499cf/header.jpg?t=1787738793
published_by: /domains/games/orgs/paradox-interactive
wikidata_id: Q15642646
wikidata_status: verified
metadata_provenance: "Wikidata (CC0) / Steam API"
tags: [jeu, premium, simulation, strategy, guerre]

claims:
  - id: hearts-of-iron-iv:c01
    statement: >
      Le jeu est une simulation stratégique mondiale centrée exclusivement sur la Seconde Guerre mondiale
      et la conduite des opérations militaires, terrestres, aériennes et navales.
    pattern: /patterns/guerre
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2016-06-06
    evidence:
      - kind: article
        source_url: https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        archive_url: http://web.archive.org/web/20231201000000/https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        captured: 2023-12-01
        quote: >
          Victory is at your fingertips! Your ability to lead your nation is your supreme weapon, the strategy game Hearts of Iron IV lets you take command of any nation in World War II.
observations:
  - id: hearts-of-iron-iv:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Catalogue d'extensions permanent sans boutique rotative en jeu."
    evidence:
      - source_url: https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> not_observed] sur hearts-of-iron-iv : Catalogue d'extensions permanent sans boutique rotative en jeu."
  - id: hearts-of-iron-iv:obs-passe-saisonnier-expirant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les Expansion Passes sont des lots d'extensions permanentes et non des passes de combat expirants."
    evidence:
      - source_url: https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        quote: "Relevé d'audit Lot 4 [passe-saisonnier-expirant -> not_observed] sur hearts-of-iron-iv : Les Expansion Passes sont des lots d'extensions permanentes et non des passes de combat expirants."
  - id: hearts-of-iron-iv:obs-coffre-aleatoire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucun tirage aléatoire ni loot box dans le jeu ou ses extensions."
    evidence:
      - source_url: https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        quote: "Relevé d'audit Lot 4 [coffre-aleatoire -> not_observed] sur hearts-of-iron-iv : Aucun tirage aléatoire ni loot box dans le jeu ou ses extensions."
  - id: hearts-of-iron-iv:obs-monnaie-intermediaire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les extensions DLC sont vendues directement en devise réelle sur Steam sans monnaie virtuelle intermédiaire."
    evidence:
      - source_url: https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        quote: "Relevé d'audit Lot 4 [monnaie-intermediaire -> not_observed] sur hearts-of-iron-iv : Les extensions DLC sont vendues directement en devise réelle sur Steam sans monnaie virtuelle intermédiaire."
  - id: hearts-of-iron-iv:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Campagnes solo et multijoueur sans limite de temps de jeu."
    evidence:
      - source_url: https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur hearts-of-iron-iv : Campagnes solo et multijoueur sans limite de temps de jeu."
  - id: hearts-of-iron-iv:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "En multijoueur, l'hôte de la partie partage gratuitement toutes ses extensions DLC avec l'ensemble des participants."
    evidence:
      - source_url: https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/394360/Hearts_of_Iron_IV/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur hearts-of-iron-iv : En multijoueur, l'hôte de la partie partage gratuitement toutes ses extensions DLC avec l'ensemble des participants."

---

# Hearts of Iron IV

La victoire est à votre portée! Votre capacité à diriger votre nation est votre arme suprême. Le jeu de stratégie Hearts of Iron IV vous permet de prendre les commandes de n'importe quelle nation engagée dans la Seconde Guerre mondiale, le conflit le plus captivant de l'histoire.
