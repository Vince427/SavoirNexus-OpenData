---
type: game
id: brawl-stars
title: "Brawl Stars"
lang: fr
platforms: [ios, android]
genres: [action, shooter]
game_modes: [multiplayer, pvp]
monetization_model: free-to-play
coverage_status: audited
cover_url: /covers/brawl-stars.svg
first_release: 2018-12-12
published_by: /domains/games/orgs/supercell
wikidata_id: Q30330493
metadata_provenance: "Wikidata (CC0)"
tags: [jeu, free-to-play, action, shooter, coffre-aleatoire, passe-saisonnier-expirant, monnaie-intermediaire]

claims:
  - id: brawl-stars:c01
    statement: >
      Les Starr Drops offrent des récompenses aléatoires de raretés variables
      (Rare à Légendaire) dont le tirage n'est pas connu préalablement par le
      joueur.
    pattern: /patterns/coffre-aleatoire
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2023-06-27
    evidence:
      - kind: article
        source_url: https://support.supercell.com/brawl-stars/en/articles/starr-drops.html
        archive_url: http://web.archive.org/web/20231001000000/https://support.supercell.com/brawl-stars/en/articles/starr-drops.html
        captured: 2023-10-01
        quote: >
          Starr Drops give random rewards based on chance percentages across five
          rarity tiers.

  - id: brawl-stars:c02
    statement: >
      Le Brawl Pass propose une progression saisonnière dont les paliers de
      récompenses non validés expirent à la fin du mois.
    pattern: /patterns/passe-saisonnier-expirant
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2020-05-13
    evidence:
      - kind: article
        source_url: https://supercell.com/en/games/brawlstars/
        archive_url: http://web.archive.org/web/20231001000000/https://supercell.com/en/games/brawlstars/
        captured: 2023-10-01
        quote: >
          Complete quests to advance through the Brawl Pass tiers each season.

  - id: brawl-stars:c03
    statement: >
      Les Gemmes constituent la monnaie achetable en argent réel pour acquérir
      des skins, des brawlers ou débloquer des niveaux.
    pattern: /patterns/monnaie-intermediaire
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2018-12-12
    evidence:
      - kind: article
        source_url: https://support.supercell.com/brawl-stars/en/articles/gems.html
        archive_url: http://web.archive.org/web/20231001000000/https://support.supercell.com/brawl-stars/en/articles/gems.html
        captured: 2023-10-01
        quote: >
          Gems are the premium currency in Brawl Stars.
observations:
  - id: brawl-stars:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les matchs 3v3 et Survivant peuvent être lancés sans limite de vies ou d'endurance."
    evidence:
      - source_url: https://supercell.com/en/games/brawlstars/
        archive_url: https://web.archive.org/web/20241015000000/https://supercell.com/en/games/brawlstars/
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur brawl-stars : Les matchs 3v3 et Survivant peuvent être lancés sans limite de vies ou d'endurance."
  - id: brawl-stars:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "L'achat de Gemmes et de ressources permet d'accélérer l'obtention des niveaux de pouvoir 11, gadgets et Hypercharges en PvP."
    evidence:
      - source_url: https://supercell.com/en/games/brawlstars/
        archive_url: https://web.archive.org/web/20241015000000/https://supercell.com/en/games/brawlstars/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> observed] sur brawl-stars : L'achat de Gemmes et de ressources permet d'accélérer l'obtention des niveaux de pouvoir 11, gadgets et Hypercharges en PvP."
  - id: brawl-stars:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "La boutique affiche quotidiennement des offres spéciales et packs promotionnels soumis à un compte à rebours d'expiration."
    evidence:
      - source_url: https://supercell.com/en/games/brawlstars/
        archive_url: https://web.archive.org/web/20241015000000/https://supercell.com/en/games/brawlstars/
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> observed] sur brawl-stars : La boutique affiche quotidiennement des offres spéciales et packs promotionnels soumis à un compte à rebours d'expiration."

---

# Brawl Stars

Jeu de combat multijoueur arène en 3 contre 3 sur mobile édité par Supercell.

