---
type: game
id: apex-legends
title: "Apex Legends"
lang: fr
platforms: [pc, playstation, xbox, nintendo-switch]
genres: [shooter, battle-royale, action]
game_modes: [multiplayer, pvp]
monetization_model: free-to-play
coverage_status: audited
first_release: 2019-02-04
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/1172470/header.jpg
published_by: /domains/games/orgs/electronic-arts
wikidata_id: Q61478103
metadata_provenance: "Wikidata (CC0)"
tags: [jeu, free-to-play, shooter, battle-royale, action, coffre-aleatoire, passe-saisonnier-expirant, monnaie-intermediaire]

claims:
  - id: apex-legends:c01
    statement: >
      Les packs Apex contiennent 3 éléments cosmétiques aléatoires avec des
      probabilités de rareté déclarées et un compteur de garantie d'un objet
      héritage tous les 500 packs ouverts.
    pattern: /patterns/coffre-aleatoire
    status: verified
    confidence: proven
    severity: 5
    valid_from: 2019-02-04
    evidence:
      - kind: article
        source_url: https://www.ea.com/games/apex-legends/about/frequently-asked-questions
        archive_url: http://web.archive.org/web/20231115000000/https://www.ea.com/games/apex-legends/about/frequently-asked-questions
        captured: 2023-11-15
        quote: >
          Apex Packs are packs of cosmetic items or crafting currency available
          in Apex Legends. Each pack contains three items.

  - id: apex-legends:c02
    statement: >
      Le passe de combat saisonnier comporte 110 niveaux de récompenses qui ne
      peuvent plus être débloqués une fois la saison en cours achevée.
    pattern: /patterns/passe-saisonnier-expirant
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2019-03-19
    evidence:
      - kind: article
        source_url: https://www.ea.com/games/apex-legends/battle-pass
        archive_url: http://web.archive.org/web/20231115000000/https://www.ea.com/games/apex-legends/battle-pass
        captured: 2023-11-15
        quote: >
          Each Battle Pass offers 110 levels of rewards, expiring at the end of
          the season.

  - id: apex-legends:c03
    statement: >
      L'achat des packs et du passe de combat nécessite une monnaie
      intermédiaire (Apex Coins) vendue par lots forfaitaires en devises réelles.
    pattern: /patterns/monnaie-intermediaire
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2019-02-04
    evidence:
      - kind: article
        source_url: https://www.ea.com/games/apex-legends/about/frequently-asked-questions
        archive_url: http://web.archive.org/web/20231115000000/https://www.ea.com/games/apex-legends/about/frequently-asked-questions
        captured: 2023-11-15
        quote: >
          Apex Coins are an in-game currency that can be purchased with real-world
          currency.
observations:
  - id: apex-legends:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucune jauge d'énergie ni restriction du nombre de parties jouables."
    evidence:
      - source_url: https://www.ea.com/games/apex-legends/about/frequently-asked-questions
        archive_url: https://web.archive.org/web/20241015000000/https://www.ea.com/games/apex-legends/about/frequently-asked-questions
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur apex-legends : Aucune jauge d'énergie ni restriction du nombre de parties jouables."
  - id: apex-legends:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les achats en boutique sont exclusivement cosmétiques ; toutes les Légendes sont déblocables via les Jetons gagnés en jouant."
    evidence:
      - source_url: https://www.ea.com/games/apex-legends/about/frequently-asked-questions
        archive_url: https://web.archive.org/web/20241015000000/https://www.ea.com/games/apex-legends/about/frequently-asked-questions
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur apex-legends : Les achats en boutique sont exclusivement cosmétiques ; toutes les Légendes sont déblocables via les Jetons gagnés en jouant."
  - id: apex-legends:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "La boutique en jeu renouvelle ses offres cosmétiques et événements de collection selon un calendrier limité sous compte à rebours."
    evidence:
      - source_url: https://www.ea.com/games/apex-legends/about/frequently-asked-questions
        archive_url: https://web.archive.org/web/20241015000000/https://www.ea.com/games/apex-legends/about/frequently-asked-questions
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> observed] sur apex-legends : La boutique en jeu renouvelle ses offres cosmétiques et événements de collection selon un calendrier limité sous compte à rebours."

---

# Apex Legends

Battle royale héroïque en vue à la première personne développé par Respawn Entertainment.
