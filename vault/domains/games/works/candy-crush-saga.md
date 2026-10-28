---
type: game
id: candy-crush-saga
title: "Candy Crush Saga"
lang: fr
platforms: [ios, android, web]
genres: [puzzle, casual]
game_modes: [single-player]
monetization_model: free-to-play
coverage_status: audited
cover_url: /covers/candy-crush-saga.svg
first_release: 2012-04-12
published_by: /domains/games/orgs/activision
wikidata_id: Q8768018
metadata_provenance: "Wikidata (CC0)"
tags: [jeu, free-to-play, puzzle, casual, systeme-energie, monnaie-intermediaire, mur-de-progression]

claims:
  - id: candy-crush-saga:c01
    statement: >
      Le joueur dispose d'une réserve limitée à 5 vies ; chaque niveau non réussi
      consomme une vie, qui se régénère au rythme d'une toutes les 30 minutes ou
      instantanément contre de l'or payant.
    pattern: /patterns/systeme-energie
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2012-04-12
    evidence:
      - kind: article
        source_url: https://candycrush.fandom.com/wiki/Lives
        archive_url: http://web.archive.org/web/20231001000000/https://candycrush.fandom.com/wiki/Lives
        captured: 2023-10-01
        quote: >
          Players start with 5 lives. A life is lost when failing a level and
          regenerates every 30 minutes.

  - id: candy-crush-saga:c02
    statement: >
      Les lingots d'or (Gold Bars) constituent une monnaie payante permettant
      d'acheter des vies supplémentaires, des coups additionnels ou des bonus.
    pattern: /patterns/monnaie-intermediaire
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2012-04-12
    evidence:
      - kind: article
        source_url: https://candycrush.fandom.com/wiki/Gold_Bars
        archive_url: http://web.archive.org/web/20231001000000/https://candycrush.fandom.com/wiki/Gold_Bars
        captured: 2023-10-01
        quote: >
          Gold Bars are the premium currency in Candy Crush Saga.

  - id: candy-crush-saga:c03
    statement: >
      Des paliers de niveaux présentent des contraintes de coups sévères et une
      distribution probabiliste des bonbons favorisant le blocage répété sans
      recours à des bonus payants.
    pattern: /patterns/mur-de-progression
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2012-04-12
    evidence:
      - kind: article
        source_url: https://www.theguardian.com/technology/2014/mar/26/candy-crush-saga-king-freemium
        archive_url: http://web.archive.org/web/20231001000000/https://www.theguardian.com/technology/2014/mar/26/candy-crush-saga-king-freemium
        captured: 2023-10-01
        rights: Article d'analyse de presse.
        quote: >
          The game creates deliberate choke points where extra moves or boosters
          are strongly incentivised.
observations:
  - id: candy-crush-saga:obs-coffre-aleatoire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les lingots d'or et bonus s'achètent sous forme de lots définis sans loterie payante."
    evidence:
      - source_url: https://www.king.com/game/candycrush
        archive_url: https://web.archive.org/web/20241015000000/https://www.king.com/game/candycrush
        quote: "Relevé d'audit Lot 4 [coffre-aleatoire -> not_observed] sur candy-crush-saga : Les lingots d'or et bonus s'achètent sous forme de lots définis sans loterie payante."
  - id: candy-crush-saga:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Jeu de réflexion solo sans affrontement compétitif direct entre joueurs."
    evidence:
      - source_url: https://www.king.com/game/candycrush
        archive_url: https://web.archive.org/web/20241015000000/https://www.king.com/game/candycrush
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur candy-crush-saga : Jeu de réflexion solo sans affrontement compétitif direct entre joueurs."
  - id: candy-crush-saga:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Comptes à rebours d'offres limitées et proposition immédiate de coups supplémentaires payants lors d'un échec."
    evidence:
      - source_url: https://www.king.com/game/candycrush
        archive_url: https://web.archive.org/web/20241015000000/https://www.king.com/game/candycrush
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> observed] sur candy-crush-saga : Comptes à rebours d'offres limitées et proposition immédiate de coups supplémentaires payants lors d'un échec."
  - id: candy-crush-saga:obs-passe-saisonnier-expirant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Présence de passes d'événements saisonniers temporaires dont les paliers expirent à la fin de l'événement."
    evidence:
      - source_url: https://www.king.com/game/candycrush
        archive_url: https://web.archive.org/web/20241015000000/https://www.king.com/game/candycrush
        quote: "Relevé d'audit Lot 4 [passe-saisonnier-expirant -> observed] sur candy-crush-saga : Présence de passes d'événements saisonniers temporaires dont les paliers expirent à la fin de l'événement."

---

# Candy Crush Saga

Jeu de réflexion et d'alignement de friandises aux milliers de niveaux édité par King.

