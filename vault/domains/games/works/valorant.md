---
type: game
id: valorant
title: "Valorant"
lang: fr
platforms: [pc, playstation, xbox]
genres: [shooter, action]
game_modes: [multiplayer, pvp]
monetization_model: free-to-play
coverage_status: audited
first_release: 2020-06-02
cover_url: https://brand.riotgames.com/static/images/valorant/logo-thumbnail.png
published_by: /domains/games/orgs/riot-games
wikidata_id: Q86919275
metadata_provenance: "Wikidata (CC0)"
tags: [jeu, free-to-play, shooter, action, fausse-urgence, monnaie-intermediaire]

claims:
  - id: valorant:c01
    statement: >
      Les offres d'armes individuelles sont renouvelées toutes les 24 heures
      sans catalogue permanent complet, créant un sentiment d'urgence d'achat.
    pattern: /patterns/fausse-urgence
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2020-06-02
    evidence:
      - kind: article
        source_url: https://valorant.fandom.com/wiki/Store
        archive_url: http://web.archive.org/web/20230501000000/https://valorant.fandom.com/wiki/Store
        captured: 2023-05-01
        quote: >
          The Offers section features four individual weapon skins that rotate
          every 24 hours.

  - id: valorant:c02
    statement: >
      L'amélioration des effets visuels d'un cosmétique nécessite des points
      Radianite, distincts des Valorant Points utilisés pour l'achat du modèle
      de base.
    pattern: /patterns/monnaie-intermediaire
    status: verified
    confidence: proven
    severity: 3
    valid_from: 2020-06-02
    evidence:
      - kind: article
        source_url: https://support-valorant.riotgames.com/hc/en-us/articles/360045814094
        archive_url: http://web.archive.org/web/20230501000000/https://support-valorant.riotgames.com/hc/en-us/articles/360045814094
        captured: 2023-05-01
        quote: >
          Radianite Points (RP) can be used to evolve certain weapon skins and
          other in-game content.
observations:
  - id: valorant:obs-coffre-aleatoire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucune caisse de butin aléatoire ; les skins d'armes achetés en boutique sont toujours identifiés."
    evidence:
      - source_url: https://playvalorant.com/fr-fr/
        archive_url: https://web.archive.org/web/20241015000000/https://playvalorant.com/fr-fr/
        quote: "Relevé d'audit Lot 4 [coffre-aleatoire -> not_observed] sur valorant : Aucune caisse de butin aléatoire ; les skins d'armes achetés en boutique sont toujours identifiés."
  - id: valorant:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les skins d'armes sont strictement cosmétiques et ne modifient ni les dégâts ni la précision en match compétitif."
    evidence:
      - source_url: https://playvalorant.com/fr-fr/
        archive_url: https://web.archive.org/web/20241015000000/https://playvalorant.com/fr-fr/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur valorant : Les skins d'armes sont strictement cosmétiques et ne modifient ni les dégâts ni la précision en match compétitif."
  - id: valorant:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucune limite du nombre de parties compétitives ou non classées."
    evidence:
      - source_url: https://playvalorant.com/fr-fr/
        archive_url: https://web.archive.org/web/20241015000000/https://playvalorant.com/fr-fr/
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur valorant : Aucune limite du nombre de parties compétitives ou non classées."
  - id: valorant:obs-passe-saisonnier-expirant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Passe de combat par Acte dont les paliers non atteints expirent à la clôture de l'Acte."
    evidence:
      - source_url: https://playvalorant.com/fr-fr/
        archive_url: https://web.archive.org/web/20241015000000/https://playvalorant.com/fr-fr/
        quote: "Relevé d'audit Lot 4 [passe-saisonnier-expirant -> observed] sur valorant : Passe de combat par Acte dont les paliers non atteints expirent à la clôture de l'Acte."

---

# Valorant

Jeu de tir tactique à la première personne avec agents et capacités édité par Riot Games.
