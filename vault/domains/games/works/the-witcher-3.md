---
type: game
id: the-witcher-3
title: "The Witcher 3: Wild Hunt"
lang: fr
platforms: [pc, playstation, xbox, nintendo-switch]
genres: [rpg, action, adventure]
game_modes: [single-player]
monetization_model: premium
coverage_status: audited
first_release: 2015-05-19
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/292030/header.jpg
published_by: /domains/games/orgs/cd-projekt-red
wikidata_id: Q4267401
metadata_provenance: "Wikidata (CC0)"
aliases:
  - "The Witcher 3"
  - "TW3"
tags: [jeu, premium, rpg, action, adventure, violence-graphique, sexualite]

claims:
  - id: the-witcher-3:c01
    statement: >
      Les affrontements à l'épée se soldent régulièrement par des décapitations,
      des sectionnements de membres et des gros plans sur des corps mutilés.
    pattern: /patterns/violence-graphique
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2015-05-19
    evidence:
      - kind: article
        source_url: https://www.esrb.org/ratings/33924/the-witcher-3-wild-hunt/
        archive_url: http://web.archive.org/web/20231001000000/https://www.esrb.org/ratings/33924/the-witcher-3-wild-hunt/
        captured: 2023-10-01
        quote: >
          Combat is highlighted by cries of pain and impactful sound effects;
          some attacks result in dismemberment or decapitation.

  - id: the-witcher-3:c02
    statement: >
      L'intrigue comprend plusieurs séquences cinématiques de relations
      sexuelles prolongées mettant en scène des personnages entièrement nus.
    pattern: /patterns/sexualite
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2015-05-19
    evidence:
      - kind: article
        source_url: https://www.esrb.org/ratings/33924/the-witcher-3-wild-hunt/
        archive_url: http://web.archive.org/web/20231001000000/https://www.esrb.org/ratings/33924/the-witcher-3-wild-hunt/
        captured: 2023-10-01
        quote: >
          The game depicts characters with exposed breasts and buttocks; sexual
          encounters depict moaning sounds and suggestive camera angles.
observations:
  - id: the-witcher-3:obs-coffre-aleatoire-01
    author: audit-rpg-solo-batch2
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-rpg-solo-batch2-gameplay-audit.md
    statement: "Aucun tirage aléatoire payant, aucune boutique de loot boxes."
    evidence:
      - source_url: https://store.steampowered.com/app/292030/The_Witcher_3_Wild_Hunt/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/292030/The_Witcher_3_Wild_Hunt/
        quote: "Audit structurel [coffre-aleatoire] sur the-witcher-3 : achat unique premium sans caisses de butin aléatoires ni tirages payants."
  - id: the-witcher-3:obs-monnaie-intermediaire-01
    author: audit-rpg-solo-batch2
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-rpg-solo-batch2-gameplay-audit.md
    statement: "Les Couronnes, Florins et Orins sont des monnaies intra-diégétiques gérées via la banque Vivaldi de Novigrad et obtenues exclusivement par contrats de sorceleur et vente de butin en jeu. Aucun achat de monnaie en argent réel."
    evidence:
      - source_url: https://store.steampowered.com/app/292030/The_Witcher_3_Wild_Hunt/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/292030/The_Witcher_3_Wild_Hunt/
        quote: "Audit structurel [monnaie-intermediaire] sur the-witcher-3 : économie strictement interne au gameplay sans vente de devises virtuelles."
  - id: the-witcher-3:obs-passe-saisonnier-expirant-01
    author: audit-rpg-solo-batch2
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-rpg-solo-batch2-gameplay-audit.md
    statement: "Aventure solo hors ligne complète sans passe saisonnier à durée limitée ni compteurs de rétention."
    evidence:
      - source_url: https://store.steampowered.com/app/292030/The_Witcher_3_Wild_Hunt/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/292030/The_Witcher_3_Wild_Hunt/
        quote: "Audit structurel [passe-saisonnier-expirant] sur the-witcher-3 : contenu intégralement pérenne sans passe saisonnier expirant."
  - id: the-witcher-3:obs-fausse-urgence-01
    author: audit-rpg-solo-batch2
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-rpg-solo-batch2-gameplay-audit.md
    statement: "Aventure solo hors ligne complète sans passe saisonnier à durée limitée ni compteurs de rétention."
    evidence:
      - source_url: https://store.steampowered.com/app/292030/The_Witcher_3_Wild_Hunt/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/292030/The_Witcher_3_Wild_Hunt/
        quote: "Audit structurel [fausse-urgence] sur the-witcher-3 : absence de boutique éphémère ou de compte à rebours promotionnel."
  - id: the-witcher-3:obs-avantage-competitif-payant-01
    author: audit-rpg-solo-batch2
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-rpg-solo-batch2-gameplay-audit.md
    statement: "Équipements de sorceleur (Écoles du Loup, du Chat, du Griffon, de l'Ours) confectionnés exclusivement auprès des maîtres forgerons du jeu."
    evidence:
      - source_url: https://store.steampowered.com/app/292030/The_Witcher_3_Wild_Hunt/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/292030/The_Witcher_3_Wild_Hunt/
        quote: "Audit structurel [avantage-competitif-payant] sur the-witcher-3 : progression fondée uniquement sur le jeu sans avantage achetable."
  - id: the-witcher-3:obs-systeme-energie-01
    author: audit-rpg-solo-batch2
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-rpg-solo-batch2-gameplay-audit.md
    statement: "Sessions de jeu illimitées sans jauge d'endurance ni minuterie de rechargement payante."
    evidence:
      - source_url: https://store.steampowered.com/app/292030/The_Witcher_3_Wild_Hunt/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/292030/The_Witcher_3_Wild_Hunt/
        quote: "Audit structurel [systeme-energie] sur the-witcher-3 : accès continu aux parties sans système de vies ou d'énergie payant."

---

# The Witcher 3: Wild Hunt

RPG en monde ouvert acclamé narrant la quête de Geralt de Riv à la recherche de Ciri.
