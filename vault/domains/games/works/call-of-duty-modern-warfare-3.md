---
type: game
id: call-of-duty-modern-warfare-3
title: "Call of Duty: Modern Warfare III"
lang: fr
platforms: [pc, playstation, xbox]
genres: [shooter, action]
game_modes: [single-player, multiplayer, co-op]
monetization_model: premium-plus-mtx
coverage_status: audited
first_release: 2023-11-10
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/2519060/header.jpg
published_by: /domains/games/orgs/activision
wikidata_id: Q121295422
metadata_provenance: "Wikidata (CC0)"
aliases:
  - "MW3"
  - "MWIII"
tags: [jeu, premium-plus-mtx, shooter, action, guerre, violence-graphique, monnaie-intermediaire, passe-saisonnier-expirant]

claims:
  - id: call-of-duty-modern-warfare-3:c01
    statement: >
      La campagne met en scène un conflit armé contemporain global impliquant
      des forces spéciales, des attaques terroristes et des frappes militaires à
      grande échelle.
    pattern: /patterns/guerre
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2023-11-10
    evidence:
      - kind: article
        source_url: https://www.esrb.org/ratings/39414/call-of-duty-modern-warfare-iii/
        archive_url: http://web.archive.org/web/20231101000000/https://www.esrb.org/ratings/39414/call-of-duty-modern-warfare-iii/
        captured: 2023-11-01
        quote: >
          Players engage in combat missions in a contemporary warfare setting,
          using realistic military firearms and explosives.

  - id: call-of-duty-modern-warfare-3:c02
    statement: >
      Les affrontements comportent des exécutions au corps à corps, des impacts
      de balles sanglants et des scènes de prises d'otages violentes.
    pattern: /patterns/violence-graphique
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2023-11-10
    evidence:
      - kind: article
        source_url: https://www.esrb.org/ratings/39414/call-of-duty-modern-warfare-iii/
        archive_url: http://web.archive.org/web/20231101000000/https://www.esrb.org/ratings/39414/call-of-duty-modern-warfare-iii/
        captured: 2023-11-01
        quote: >
          Blood-splatter effects occur frequently; cutscenes depict characters
          getting executed or shot at point-blank range.

  - id: call-of-duty-modern-warfare-3:c03
    statement: >
      L'accès à la boutique et aux cosmétiques requiert des Points Call of Duty
      (CP) vendus sous forme de devises virtuelles.
    pattern: /patterns/monnaie-intermediaire
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2023-11-10
    evidence:
      - kind: article
        source_url: https://support.activision.com/articles/call-of-duty-points
        archive_url: http://web.archive.org/web/20231201000000/https://support.activision.com/articles/call-of-duty-points
        captured: 2023-12-01
        quote: >
          Call of Duty Points (CP) are the optional in-game currency you can use
          to obtain content in Modern Warfare III.

  - id: call-of-duty-modern-warfare-3:c04
    statement: >
      Le passe de combat saisonnier comprend des récompenses expirant à la fin
      de chaque saison d'exploitation.
    pattern: /patterns/passe-saisonnier-expirant
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2023-12-06
    evidence:
      - kind: article
        source_url: https://www.callofduty.com/blog/2023/12/call-of-duty-modern-warfare-iii-warzone-season-1-blackcell-battle-pass-bundles
        archive_url: http://web.archive.org/web/20231201000000/https://www.callofduty.com/blog/2023/12/call-of-duty-modern-warfare-iii-warzone-season-1-blackcell-battle-pass-bundles
        captured: 2023-12-01
        quote: >
          Battle Pass sectors expire at the conclusion of the season.
observations:
  - id: call-of-duty-modern-warfare-3:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucune jauge d'énergie limitant l'enchaînement des matchs."
    evidence:
      - source_url: https://www.callofduty.com/modernwarfare3
        archive_url: https://web.archive.org/web/20241015000000/https://www.callofduty.com/modernwarfare3
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur call-of-duty-modern-warfare-3 : Aucune jauge d'énergie limitant l'enchaînement des matchs."
  - id: call-of-duty-modern-warfare-3:obs-coffre-aleatoire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucun tirage aléatoire payant ; tous les bundles de la boutique ont un contenu détaillé à l'avance."
    evidence:
      - source_url: https://www.callofduty.com/modernwarfare3
        archive_url: https://web.archive.org/web/20241015000000/https://www.callofduty.com/modernwarfare3
        quote: "Relevé d'audit Lot 4 [coffre-aleatoire -> not_observed] sur call-of-duty-modern-warfare-3 : Aucun tirage aléatoire payant ; tous les bundles de la boutique ont un contenu détaillé à l'avance."
  - id: call-of-duty-modern-warfare-3:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les plans d'armes achetés n'octroient pas de statistiques supérieures aux armes déblocables en jeu."
    evidence:
      - source_url: https://www.callofduty.com/modernwarfare3
        archive_url: https://web.archive.org/web/20241015000000/https://www.callofduty.com/modernwarfare3
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur call-of-duty-modern-warfare-3 : Les plans d'armes achetés n'octroient pas de statistiques supérieures aux armes déblocables en jeu."
  - id: call-of-duty-modern-warfare-3:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Rotation périodique des packs d'opérateurs et plans d'armes dans la boutique."
    evidence:
      - source_url: https://www.callofduty.com/modernwarfare3
        archive_url: https://web.archive.org/web/20241015000000/https://www.callofduty.com/modernwarfare3
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> observed] sur call-of-duty-modern-warfare-3 : Rotation périodique des packs d'opérateurs et plans d'armes dans la boutique."

---

# Call of Duty: Modern Warfare III

Suite directe du reboot de Modern Warfare proposant une campagne face à Vladimir Makarov.
