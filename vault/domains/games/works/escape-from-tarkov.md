---
type: game
id: escape-from-tarkov
title: "Escape from Tarkov"
lang: fr
platforms: [pc]
genres: [shooter, rpg, survival]
game_modes: [multiplayer, pvp]
monetization_model: premium
coverage_status: audited
cover_url: /covers/escape-from-tarkov.svg
first_release: 2017-07-28
published_by: /domains/games/orgs/battlestate-games
wikidata_id: Q23038939
metadata_provenance: "Wikidata (CC0)"
aliases:
  - "EFT"
  - "Tarkov"
tags: [jeu, premium, shooter, rpg, survival, guerre, violence-graphique]

claims:
  - id: escape-from-tarkov:c01
    statement: >
      Le jeu simule un conflit armé contemporain réaliste dans une zone de guerre fictive (Norvinsk)
      opposant deux compagnies militaires privées (USEC et BEAR) et des milices armées.
    pattern: /patterns/guerre
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2017-07-28
    evidence:
      - kind: article
        source_url: https://www.escapefromtarkov.com/
        archive_url: http://web.archive.org/web/20231201000000/https://www.escapefromtarkov.com/
        captured: 2023-12-01
        quote: >
          Escape from Tarkov is a hardcore and realistic online first-person action RPG/Simulator with MMO features set in the fictional Norvinsk region warzone.

  - id: escape-from-tarkov:c02
    statement: >
      Les combats au corps à corps et tirs d'armes à feu comportent des blessures hémorragiques, des démembrements et des représentations réalistes de la létalité.
    pattern: /patterns/violence-graphique
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2017-07-28
    evidence:
      - kind: article
        source_url: https://www.escapefromtarkov.com/
        archive_url: http://web.archive.org/web/20231201000000/https://www.escapefromtarkov.com/
        captured: 2023-12-01
        quote: >
          Realistic ballistics, terminal damage, bleeding, fractures, and severe physical trauma simulation.
observations:
  - id: escape-from-tarkov:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Pas de boutique cosmétique rotative sous compte à rebours en jeu."
    evidence:
      - source_url: https://www.escapefromtarkov.com/
        archive_url: https://web.archive.org/web/20241015000000/https://www.escapefromtarkov.com/
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> not_observed] sur escape-from-tarkov : Pas de boutique cosmétique rotative sous compte à rebours en jeu."
  - id: escape-from-tarkov:obs-passe-saisonnier-expirant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucun passe de combat saisonnier payant dans le jeu principal."
    evidence:
      - source_url: https://www.escapefromtarkov.com/
        archive_url: https://web.archive.org/web/20241015000000/https://www.escapefromtarkov.com/
        quote: "Relevé d'audit Lot 4 [passe-saisonnier-expirant -> not_observed] sur escape-from-tarkov : Aucun passe de combat saisonnier payant dans le jeu principal."
  - id: escape-from-tarkov:obs-coffre-aleatoire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucun coffre aléatoire payant en argent réel."
    evidence:
      - source_url: https://www.escapefromtarkov.com/
        archive_url: https://web.archive.org/web/20241015000000/https://www.escapefromtarkov.com/
        quote: "Relevé d'audit Lot 4 [coffre-aleatoire -> not_observed] sur escape-from-tarkov : Aucun coffre aléatoire payant en argent réel."
  - id: escape-from-tarkov:obs-monnaie-intermediaire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les éditions et extensions de réserve sont facturées directement en devise réelle sur le site officiel sans monnaie intermédiaire."
    evidence:
      - source_url: https://www.escapefromtarkov.com/
        archive_url: https://web.archive.org/web/20241015000000/https://www.escapefromtarkov.com/
        quote: "Relevé d'audit Lot 4 [monnaie-intermediaire -> not_observed] sur escape-from-tarkov : Les éditions et extensions de réserve sont facturées directement en devise réelle sur le site officiel sans monnaie intermédiaire."
  - id: escape-from-tarkov:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les raids avec l'opérateur principal PMC ne sont soumis à aucune jauge d'énergie payante."
    evidence:
      - source_url: https://www.escapefromtarkov.com/
        archive_url: https://web.archive.org/web/20241015000000/https://www.escapefromtarkov.com/
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur escape-from-tarkov : Les raids avec l'opérateur principal PMC ne sont soumis à aucune jauge d'énergie payante."
  - id: escape-from-tarkov:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les éditions supérieures accordent dès le début de chaque wipe un conteneur sécurisé agrandi (Gamma 3x3), une réserve étendue et un équipement de départ supérieur en PvP."
    evidence:
      - source_url: https://www.escapefromtarkov.com/
        archive_url: https://web.archive.org/web/20241015000000/https://www.escapefromtarkov.com/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> observed] sur escape-from-tarkov : Les éditions supérieures accordent dès le début de chaque wipe un conteneur sécurisé agrandi (Gamma 3x3), une réserve étendue et un équipement de départ supérieur en PvP."

---

# Escape from Tarkov

Jeu de tir d'extraction hardcore et simulateur de combat militaire réaliste à la première personne.

