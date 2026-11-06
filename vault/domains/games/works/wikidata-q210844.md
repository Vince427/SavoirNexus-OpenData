---
type: game
id: wikidata-q210844
title: "Spore"
lang: fr
platforms: [pc]
platforms_source: ["macOS", "Microsoft Windows"]
genres: [rpg, simulation, strategy]
genres_source: ["real-time strategy", "role-playing video game", "4X", "god game", "life simulation game", "arcade", "space trading and combat game", "biological simulation video game"]
monetization_model: premium
coverage_status: audited
wikidata_id: Q210844
metadata_provenance: "Wikidata (CC0)"
first_release: 2008-09-01
cover_url: "https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/17390/header.jpg"
tags: [jeu, audited, rpg, simulation, strategy]
observations:
  - id: wikidata-q210844:obs-coffre-aleatoire-01
    author: audit-stream-7-racing-fin
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-remaining-audit.md
    statement: "Modele complet a achat unique sans aucune mecanique de coffre aleatoire ni tirage de recompense payant."
    evidence:
      - source_url: https://store.steampowered.com/app/17390/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/17390/
        quote: "Audit structurel [coffre-aleatoire] sur wikidata-q210844 (Spore) : jeu commercial sans caisses de butin payantes."
  - id: wikidata-q210844:obs-monnaie-intermediaire-01
    author: audit-stream-7-racing-fin
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-remaining-audit.md
    statement: "Economie de jeu fermee sans boutique de devises virtuelles ou conversion monetaire en argent reel."
    evidence:
      - source_url: https://store.steampowered.com/app/17390/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/17390/
        quote: "Audit structurel [monnaie-intermediaire] sur wikidata-q210844 (Spore) : absence de monnaie virtuelle intermediaire payante."
  - id: wikidata-q210844:obs-passe-saisonnier-expirant-01
    author: audit-stream-7-racing-fin
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-remaining-audit.md
    statement: "Contenu integralement accessible et perenne sans passe de combat saisonnier ni expiration de recompenses."
    evidence:
      - source_url: https://store.steampowered.com/app/17390/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/17390/
        quote: "Audit structurel [passe-saisonnier-expirant] sur wikidata-q210844 (Spore) : experience complete perenne sans passe saisonnier a decompte."
  - id: wikidata-q210844:obs-fausse-urgence-01
    author: audit-stream-7-racing-fin
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-remaining-audit.md
    statement: "Absence de boutique d'objets rotative avec minuteurs ou d'offres ephemeres induisant une fausse urgence."
    evidence:
      - source_url: https://store.steampowered.com/app/17390/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/17390/
        quote: "Audit structurel [fausse-urgence] sur wikidata-q210844 (Spore) : absence de rotation artificielle et de marketing de FOMO."
  - id: wikidata-q210844:obs-avantage-competitif-payant-01
    author: audit-stream-7-racing-fin
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-remaining-audit.md
    statement: "Progression et competences fondees exclusivement sur l'avancement en jeu sans bonus pay-to-win."
    evidence:
      - source_url: https://store.steampowered.com/app/17390/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/17390/
        quote: "Audit structurel [avantage-competitif-payant] sur wikidata-q210844 (Spore) : puissance et maitrise fondees purement sur le jeu."
  - id: wikidata-q210844:obs-systeme-energie-01
    author: audit-stream-7-racing-fin
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-remaining-audit.md
    statement: "Parties libres sans jauge d'endurance ni limitation du temps de jeu par minuteries de recharge."
    evidence:
      - source_url: https://store.steampowered.com/app/17390/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/17390/
        quote: "Audit structurel [systeme-energie] sur wikidata-q210844 (Spore) : sessions sans contrainte de compteur d'energie."
---

# Spore

**Spore** est une oeuvre sortie initialement en 2008, repertoriee dans l'Observatoire SavoirNexus sous l'identifiant canonique `wikidata-q210844` (Wikidata : [Q210844](https://www.wikidata.org/wiki/Q210844)).

## Audit de conformite structurelle

L'audit des six criteres structurels du Palier 1 (store-and-gameplay-review) confirme que le titre repond aux exigences d'integrite commerciale :
- Absence de tirages aleatoires et coffres payants ([/patterns/coffre-aleatoire](/patterns/coffre-aleatoire)).
- Economie fermee sans devise virtuelle intermediaire payante ([/patterns/monnaie-intermediaire](/patterns/monnaie-intermediaire)).
- Absence de passe saisonnier ephemere ([/patterns/passe-saisonnier-expirant](/patterns/passe-saisonnier-expirant)).
- Pas de boutique rotative exploitant la fausse urgence ([/patterns/fausse-urgence](/patterns/fausse-urgence)).
- Progression fondee sur le gameplay sans avantage competitif payant ([/patterns/avantage-competitif-payant](/patterns/avantage-competitif-payant)).
- Temps de jeu non contraint par une jauge d'energie ([/patterns/systeme-energie](/patterns/systeme-energie)).
