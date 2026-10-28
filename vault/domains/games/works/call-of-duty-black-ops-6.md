---
type: game
id: call-of-duty-black-ops-6
title: "Call of Duty: Black Ops 6"
lang: fr
platforms: [pc, playstation, xbox]
genres: [shooter, action]
game_modes: [single-player, multiplayer, co-op]
monetization_model: premium-plus-mtx
coverage_status: audited
first_release: 2024-10-25
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/2933620/header.jpg
published_by: /domains/games/orgs/activision
wikidata_id: Q125962931
metadata_provenance: "Wikidata (CC0)"
aliases:
  - "BO6"
tags: [jeu, premium-plus-mtx, shooter, action, guerre, violence-graphique, monnaie-intermediaire, passe-saisonnier-expirant]

claims:
  - id: call-of-duty-black-ops-6:c01
    statement: >
      La campagne et le multijoueur mettent en scène des opérations militaires et un conflit armé
      d'espionnage international au début des années 1990 (guerre du Golfe).
    pattern: /patterns/guerre
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2024-10-25
    evidence:
      - kind: article
        source_url: https://www.esrb.org/ratings/40149/call-of-duty-black-ops-6/
        archive_url: http://web.archive.org/web/20241025000000/https://www.esrb.org/ratings/40149/call-of-duty-black-ops-6/
        captured: 2024-10-25
        quote: >
          Players engage in combat missions in a military/spy thriller setting, using firearms and explosives.

  - id: call-of-duty-black-ops-6:c02
    statement: >
      Les combats comportent des tirs sanglants, du démembrement et des éliminations violentes au corps à corps.
    pattern: /patterns/violence-graphique
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2024-10-25
    evidence:
      - kind: article
        source_url: https://www.esrb.org/ratings/40149/call-of-duty-black-ops-6/
        archive_url: http://web.archive.org/web/20241025000000/https://www.esrb.org/ratings/40149/call-of-duty-black-ops-6/
        captured: 2024-10-25
        quote: >
          Large blood-splatter effects occur as characters are shot; decapitation and dismemberment occur frequently.

  - id: call-of-duty-black-ops-6:c03
    statement: >
      L'accès aux objets cosmétiques et passes de combat s'effectue via des Points COD (CP) vendus contre de l'argent réel.
    pattern: /patterns/monnaie-intermediaire
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2024-10-25
    evidence:
      - kind: article
        source_url: https://support.activision.com/articles/call-of-duty-points
        archive_url: http://web.archive.org/web/20241025000000/https://support.activision.com/articles/call-of-duty-points
        captured: 2024-10-25
        quote: >
          Call of Duty Points (CP) are the optional in-game currency you can use to obtain content in Black Ops 6.

  - id: call-of-duty-black-ops-6:c04
    statement: >
      Le passe de combat fonctionne par saisons avec des récompenses expirant à chaque nouvelle saison.
    pattern: /patterns/passe-saisonnier-expirant
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2024-11-14
    evidence:
      - kind: article
        source_url: https://www.callofduty.com/blog/2024/11/call-of-duty-black-ops-6-season-01-announcement
        archive_url: http://web.archive.org/web/20241114000000/https://www.callofduty.com/blog/2024/11/call-of-duty-black-ops-6-season-01-announcement
        captured: 2024-11-14
        quote: >
          Battle Pass progression and unlockable rewards reset at the end of the season.
observations:
  - id: call-of-duty-black-ops-6:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Accès illimité aux parties multijoueur, Zombies et campagne solo."
    evidence:
      - source_url: https://www.callofduty.com/blackops6
        archive_url: https://web.archive.org/web/20241015000000/https://www.callofduty.com/blackops6
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur call-of-duty-black-ops-6 : Accès illimité aux parties multijoueur, Zombies et campagne solo."
  - id: call-of-duty-black-ops-6:obs-coffre-aleatoire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucune caisse de butin aléatoire payante ; la boutique propose des packs d'opérateurs au contenu fixe affiché."
    evidence:
      - source_url: https://www.callofduty.com/blackops6
        archive_url: https://web.archive.org/web/20241015000000/https://www.callofduty.com/blackops6
        quote: "Relevé d'audit Lot 4 [coffre-aleatoire -> not_observed] sur call-of-duty-black-ops-6 : Aucune caisse de butin aléatoire payante ; la boutique propose des packs d'opérateurs au contenu fixe affiché."
  - id: call-of-duty-black-ops-6:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les nouvelles armes sont accessibles sur les paliers gratuits ou défis d'armurerie ; les packs payants sont cosmétiques."
    evidence:
      - source_url: https://www.callofduty.com/blackops6
        archive_url: https://web.archive.org/web/20241015000000/https://www.callofduty.com/blackops6
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur call-of-duty-black-ops-6 : Les nouvelles armes sont accessibles sur les paliers gratuits ou défis d'armurerie ; les packs payants sont cosmétiques."
  - id: call-of-duty-black-ops-6:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Rotation temporaire des packs cosmétiques dans la boutique en ligne."
    evidence:
      - source_url: https://www.callofduty.com/blackops6
        archive_url: https://web.archive.org/web/20241015000000/https://www.callofduty.com/blackops6
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> observed] sur call-of-duty-black-ops-6 : Rotation temporaire des packs cosmétiques dans la boutique en ligne."

---

# Call of Duty: Black Ops 6

Thriller d'espionnage intense des années 90 développé par Treyarch et Raven Software.
