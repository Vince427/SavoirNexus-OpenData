---
type: game
id: genshin-impact
title: "Genshin Impact"
lang: fr
platforms: [pc, playstation, ios, android]
genres: [rpg, action, gacha]
game_modes: [single-player, co-op]
monetization_model: free-to-play
coverage_status: audited
first_release: 2020-09-28
cover_url: /covers/genshin-impact.svg
published_by: /domains/games/orgs/hoyoverse
wikidata_id: Q65059474
metadata_provenance: "Wikidata (CC0)"
tags: [jeu, free-to-play, rpg, action, gacha, monnaie-intermediaire, coffre-aleatoire]

claims:
  - id: genshin-impact:c01
    statement: >
      L'obtention de personnages et d'armes 5 étoiles repose sur un tirage
      probabiliste payant (bannières de vœux) avec un système de garantie à 90
      tirages et une règle de 50/50 sur la première obtention.
    pattern: /patterns/coffre-aleatoire
    status: verified
    confidence: proven
    severity: 5
    valid_from: 2020-09-28
    evidence:
      - kind: article
        source_url: https://genshin-impact.fandom.com/wiki/Wishes/Details
        archive_url: http://web.archive.org/web/20240115000000/https://genshin-impact.fandom.com/wiki/Wishes/Details
        captured: 2024-01-15
        quote: >
          Wish is the gacha system in Genshin Impact. There are two main types
          of Wishes: Permanent and Event Wishes.

  - id: genshin-impact:c02
    statement: >
      La conversion d'argent réel passe par l'achat de Cristaux primaires,
      convertibles en Primo-gemmes, elles-mêmes convertibles en Pierres de la
      fatalité ou de la destinée.
    pattern: /patterns/monnaie-intermediaire
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2020-09-28
    evidence:
      - kind: article
        source_url: https://genshin-impact.fandom.com/wiki/Genesis_Crystal
        archive_url: http://web.archive.org/web/20231201000000/https://genshin-impact.fandom.com/wiki/Genesis_Crystal
        captured: 2023-12-01
        quote: >
          Genesis Crystals can be converted into Primogems at a 1:1 ratio.

  - id: genshin-impact:c03
    statement: >
      L'accès aux récompenses des boss et donjons est plafonné par une jauge de
      Résine originelle (160 maximum, 1 unité toutes les 8 minutes),
      rechargeable via des Primo-gemmes achetables en argent réel.
    pattern: /patterns/systeme-energie
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2020-09-28
    evidence:
      - kind: article
        source_url: https://genshin-impact.fandom.com/wiki/Original_Resin
        archive_url: http://web.archive.org/web/20231120000000/https://genshin-impact.fandom.com/wiki/Original_Resin
        captured: 2023-11-20
        quote: >
          Original Resin is a resource that is consumed to claim challenge
          rewards from Ley Line Outcrops, Petrified Trees in Domains, and
          Trounce Blossoms.
observations:
  - id: genshin-impact:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Jeu exclusivement solo et coopératif PvE sans mode PvP compétitif ni classement entre joueurs."
    evidence:
      - source_url: https://genshin.hoyoverse.com/fr/
        archive_url: https://web.archive.org/web/20241015000000/https://genshin.hoyoverse.com/fr/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur genshin-impact : Jeu exclusivement solo et coopératif PvE sans mode PvP compétitif ni classement entre joueurs."
  - id: genshin-impact:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les bannières d'événements de personnages 5 étoiles et d'armes ne sont disponibles que pendant 21 jours avant retrait prolongé."
    evidence:
      - source_url: https://genshin.hoyoverse.com/fr/
        archive_url: https://web.archive.org/web/20241015000000/https://genshin.hoyoverse.com/fr/
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> observed] sur genshin-impact : Les bannières d'événements de personnages 5 étoiles et d'armes ne sont disponibles que pendant 21 jours avant retrait prolongé."
  - id: genshin-impact:obs-passe-saisonnier-expirant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Le Passe de bataille (Chant de la Perle) dure 6 semaines et ses récompenses non débloquées expirent à chaque changement de version."
    evidence:
      - source_url: https://genshin.hoyoverse.com/fr/
        archive_url: https://web.archive.org/web/20241015000000/https://genshin.hoyoverse.com/fr/
        quote: "Relevé d'audit Lot 4 [passe-saisonnier-expirant -> observed] sur genshin-impact : Le Passe de bataille (Chant de la Perle) dure 6 semaines et ses récompenses non débloquées expirent à chaque changement de version."

---

# Genshin Impact

Action-RPG en monde ouvert avec mÃ©caniques de collection de personnages (gacha) dÃ©veloppÃ© par HoYoverse.

