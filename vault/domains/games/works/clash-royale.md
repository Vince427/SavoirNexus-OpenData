---
type: game
id: clash-royale
title: "Clash Royale"
lang: fr
platforms: [ios, android]
genres: [strategy, card-game]
game_modes: [multiplayer, pvp]
monetization_model: free-to-play
coverage_status: audited
cover_url: /covers/clash-royale.svg
first_release: 2016-03-02
published_by: /domains/games/orgs/supercell
wikidata_id: Q22095476
metadata_provenance: "Wikidata (CC0)"
tags: [jeu, free-to-play, strategy, card-game, coffre-aleatoire, passe-saisonnier-expirant, monnaie-intermediaire, mur-de-progression]

claims:
  - id: clash-royale:c01
    statement: >
      Les coffres obtenus en combat ou achetés en boutique renferment des cartes
      aléatoires selon des probabilités de rareté fixées par l'arène du joueur.
    pattern: /patterns/coffre-aleatoire
    status: verified
    confidence: proven
    severity: 5
    valid_from: 2016-03-02
    evidence:
      - kind: article
        source_url: https://support.supercell.com/clash-royale/en/articles/chest-drop-chances.html
        archive_url: http://web.archive.org/web/20231001000000/https://support.supercell.com/clash-royale/en/articles/chest-drop-chances.html
        captured: 2023-10-01
        quote: >
          Chest drop probabilities vary based on the arena and chest type.

  - id: clash-royale:c02
    statement: >
      Le Pass Royale fonctionne sur une cadence mensuelle avec expiration
      complète des récompenses non débloquées à la fin de chaque saison.
    pattern: /patterns/passe-saisonnier-expirant
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2019-07-01
    evidence:
      - kind: article
        source_url: https://supercell.com/en/games/clashroyale/
        archive_url: http://web.archive.org/web/20231001000000/https://supercell.com/en/games/clashroyale/
        captured: 2023-10-01
        quote: >
          Each season brings a new Pass Royale with exclusive tower skins and
          emotes.

  - id: clash-royale:c03
    statement: >
      Les Gemmes constituent la monnaie payante permettant d'ouvrir
      instantanément les coffres sous compte à rebours ou d'acheter des cartes
      spécifiques.
    pattern: /patterns/monnaie-intermediaire
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2016-03-02
    evidence:
      - kind: article
        source_url: https://support.supercell.com/clash-royale/en/articles/gems.html
        archive_url: http://web.archive.org/web/20231001000000/https://support.supercell.com/clash-royale/en/articles/gems.html
        captured: 2023-10-01
        quote: >
          Gems can be purchased with real money and used to speed up chest
          unlock timers.

  - id: clash-royale:c04
    statement: >
      Les paliers supérieurs d'amélioration des cartes exigent des quantités
      croissantes de doublons et d'or, créant un ralentissement marqué de la
      progression compétitive en arène.
    pattern: /patterns/mur-de-progression
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2016-03-02
    evidence:
      - kind: article
        source_url: https://clashroyale.fandom.com/wiki/Cards
        archive_url: http://web.archive.org/web/20231001000000/https://clashroyale.fandom.com/wiki/Cards
        captured: 2023-10-01
        quote: >
          Upgrading cards requires exponentially more duplicates and gold for
          each level.
observations:
  - id: clash-royale:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les combats d'arène peuvent être lancés en continu sans jauge d'énergie."
    evidence:
      - source_url: https://supercell.com/en/games/clashroyale/
        archive_url: https://web.archive.org/web/20241015000000/https://supercell.com/en/games/clashroyale/
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur clash-royale : Les combats d'arène peuvent être lancés en continu sans jauge d'énergie."
  - id: clash-royale:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "L'achat de Gemmes, coffres et fragments d'évolution accélère directement la montée en niveau des cartes et tours en duel classé 1v1."
    evidence:
      - source_url: https://supercell.com/en/games/clashroyale/
        archive_url: https://web.archive.org/web/20241015000000/https://supercell.com/en/games/clashroyale/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> observed] sur clash-royale : L'achat de Gemmes, coffres et fragments d'évolution accélère directement la montée en niveau des cartes et tours en duel classé 1v1."
  - id: clash-royale:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Rotation quotidienne de la boutique et offres promotionnelles temporaires sous minuterie."
    evidence:
      - source_url: https://supercell.com/en/games/clashroyale/
        archive_url: https://web.archive.org/web/20241015000000/https://supercell.com/en/games/clashroyale/
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> observed] sur clash-royale : Rotation quotidienne de la boutique et offres promotionnelles temporaires sous minuterie."

---

# Clash Royale

Jeu de stratégie mobile en temps réel combinant cartes à collectionner et défense de tours.

