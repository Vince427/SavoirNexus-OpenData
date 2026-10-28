---
type: game
id: resident-evil-4-remake
title: "Resident Evil 4"
lang: fr
platforms: [pc, playstation, xbox, ios]
genres: [action, horror]
game_modes: [single-player]
monetization_model: premium
coverage_status: audited
first_release: 2023-03-24
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/2050650/header.jpg
published_by: /domains/games/orgs/capcom
wikidata_id: Q112231148
metadata_provenance: "Wikidata (CC0)"
aliases:
  - "RE4 Remake"
tags: [jeu, premium, action, horror, horreur, violence-graphique]

claims:
  - id: resident-evil-4-remake:c01
    statement: >
      Le jeu repose sur les mécaniques fondamentales du survival horror avec
      créatures parasitaires monstrueuses, gestion de panique et ambiance de
      terreur viscérale.
    pattern: /patterns/horreur
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2023-03-24
    evidence:
      - kind: article
        source_url: https://www.esrb.org/ratings/38992/resident-evil-4/
        archive_url: http://web.archive.org/web/20230301000000/https://www.esrb.org/ratings/38992/resident-evil-4/
        captured: 2023-03-01
        quote: >
          Players assume the role of an agent in a hostile rural village filled
          with mutated parasite creatures in a high-tension horror atmosphere.

  - id: resident-evil-4-remake:c02
    statement: >
      Les affrontements comportent des mises à mort graphiques incluant des
      décapitations à la tronçonneuse contre le joueur et des démembrements
      détaillés d'ennemis.
    pattern: /patterns/violence-graphique
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2023-03-24
    evidence:
      - kind: article
        source_url: https://www.esrb.org/ratings/38992/resident-evil-4/
        archive_url: http://web.archive.org/web/20230301000000/https://www.esrb.org/ratings/38992/resident-evil-4/
        captured: 2023-03-01
        quote: >
          Attacks often result in decapitation and dismemberment; enemies can
          impale or decapitate the player with chainsaws.
observations:
  - id: resident-evil-4-remake:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Absence de boutique rotative ou d'offres temporaires en jeu."
    evidence:
      - source_url: https://store.steampowered.com/app/2050650/Resident_Evil_4/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/2050650/Resident_Evil_4/
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> not_observed] sur resident-evil-4-remake : Absence de boutique rotative ou d'offres temporaires en jeu."
  - id: resident-evil-4-remake:obs-passe-saisonnier-expirant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aventure solo narrative sans saison ni passe de combat."
    evidence:
      - source_url: https://store.steampowered.com/app/2050650/Resident_Evil_4/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/2050650/Resident_Evil_4/
        quote: "Relevé d'audit Lot 4 [passe-saisonnier-expirant -> not_observed] sur resident-evil-4-remake : Aventure solo narrative sans saison ni passe de combat."
  - id: resident-evil-4-remake:obs-coffre-aleatoire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucun coffre aléatoire payant en argent réel ; les porte-bonheurs du stand de tir utilisent uniquement des jetons gagnés en jeu."
    evidence:
      - source_url: https://store.steampowered.com/app/2050650/Resident_Evil_4/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/2050650/Resident_Evil_4/
        quote: "Relevé d'audit Lot 4 [coffre-aleatoire -> not_observed] sur resident-evil-4-remake : Aucun coffre aléatoire payant en argent réel ; les porte-bonheurs du stand de tir utilisent uniquement des jetons gagnés en jeu."
  - id: resident-evil-4-remake:obs-monnaie-intermediaire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les contenus téléchargeables sont vendus directement en devise réelle sur le magasin sans monnaie virtuelle intermédiaire."
    evidence:
      - source_url: https://store.steampowered.com/app/2050650/Resident_Evil_4/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/2050650/Resident_Evil_4/
        quote: "Relevé d'audit Lot 4 [monnaie-intermediaire -> not_observed] sur resident-evil-4-remake : Les contenus téléchargeables sont vendus directement en devise réelle sur le magasin sans monnaie virtuelle intermédiaire."
  - id: resident-evil-4-remake:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Sessions de jeu solo illimitées sans système d'énergie."
    evidence:
      - source_url: https://store.steampowered.com/app/2050650/Resident_Evil_4/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/2050650/Resident_Evil_4/
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur resident-evil-4-remake : Sessions de jeu solo illimitées sans système d'énergie."
  - id: resident-evil-4-remake:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Jeu strictement solo sans mode PvP compétitif."
    evidence:
      - source_url: https://store.steampowered.com/app/2050650/Resident_Evil_4/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/2050650/Resident_Evil_4/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur resident-evil-4-remake : Jeu strictement solo sans mode PvP compétitif."

---

# Resident Evil 4

Réinvention magistrale du monument du survival horror d'action par Capcom.
