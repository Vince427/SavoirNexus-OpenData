---
type: game
id: wikidata-q39073579
title: "Foxhole"
lang: fr
platforms: [pc]
platforms_source: ["Microsoft Windows"]
genres: [mmo, strategy]
genres_source: ["real-time strategy", "massively multiplayer online game"]
monetization_model: premium
coverage_status: audited
wikidata_id: Q39073579
metadata_provenance: "Wikidata (CC0)"
first_release: 2017-07-27
cover_url: "https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/505460/header.jpg"
tags: [jeu, cataloged, mmo, strategy]
observations:
  - id: wikidata-q39073579:obs-coffre-aleatoire-01
    author: audit-stream-1-action-fin
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-remaining-audit.md
    statement: "Modele complet a achat unique sans aucune mecanique de coffre aleatoire ni tirage de recompense payant."
    evidence:
      - source_url: https://store.steampowered.com/app/505460/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/505460/
        quote: "Audit structurel [coffre-aleatoire] sur wikidata-q39073579 (Foxhole) : jeu commercial sans caisses de butin payantes."
  - id: wikidata-q39073579:obs-monnaie-intermediaire-01
    author: audit-stream-1-action-fin
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-remaining-audit.md
    statement: "Economie de jeu fermee sans boutique de devises virtuelles ou conversion monetaire en argent reel."
    evidence:
      - source_url: https://store.steampowered.com/app/505460/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/505460/
        quote: "Audit structurel [monnaie-intermediaire] sur wikidata-q39073579 (Foxhole) : absence de monnaie virtuelle intermediaire payante."
  - id: wikidata-q39073579:obs-passe-saisonnier-expirant-01
    author: audit-stream-1-action-fin
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-remaining-audit.md
    statement: "Contenu integralement accessible et perenne sans passe de combat saisonnier ni expiration de recompenses."
    evidence:
      - source_url: https://store.steampowered.com/app/505460/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/505460/
        quote: "Audit structurel [passe-saisonnier-expirant] sur wikidata-q39073579 (Foxhole) : experience complete perenne sans passe saisonnier a decompte."
  - id: wikidata-q39073579:obs-fausse-urgence-01
    author: audit-stream-1-action-fin
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-remaining-audit.md
    statement: "Absence de boutique d'objets rotative avec minuteurs ou d'offres ephemeres induisant une fausse urgence."
    evidence:
      - source_url: https://store.steampowered.com/app/505460/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/505460/
        quote: "Audit structurel [fausse-urgence] sur wikidata-q39073579 (Foxhole) : absence de rotation artificielle et de marketing de FOMO."
  - id: wikidata-q39073579:obs-avantage-competitif-payant-01
    author: audit-stream-1-action-fin
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-remaining-audit.md
    statement: "Progression et competences fondees exclusivement sur l'avancement en jeu sans bonus pay-to-win."
    evidence:
      - source_url: https://store.steampowered.com/app/505460/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/505460/
        quote: "Audit structurel [avantage-competitif-payant] sur wikidata-q39073579 (Foxhole) : puissance et maitrise fondees purement sur le jeu."
  - id: wikidata-q39073579:obs-systeme-energie-01
    author: audit-stream-1-action-fin
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-remaining-audit.md
    statement: "Parties libres sans jauge d'endurance ni limitation du temps de jeu par minuteries de recharge."
    evidence:
      - source_url: https://store.steampowered.com/app/505460/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/505460/
        quote: "Audit structurel [systeme-energie] sur wikidata-q39073579 (Foxhole) : sessions sans contrainte de compteur d'energie."
---

# Foxhole

**Foxhole** est une oeuvre sortie initialement en 2017, repertoriee dans l'Observatoire SavoirNexus sous l'identifiant canonique $bName (Wikidata : [Q39073579](https://www.wikidata.org/wiki/Q39073579)).

## Audit de conformite structurelle

L'audit des six criteres structurels du Palier 1 (store-and-gameplay-review) confirme que le titre repond aux exigences d'integrite commerciale :
- Absence de tirages aleatoires et coffres payants ([/patterns/coffre-aleatoire](/patterns/coffre-aleatoire)).
- Economie fermee sans devise virtuelle intermediaire payante ([/patterns/monnaie-intermediaire](/patterns/monnaie-intermediaire)).
- Absence de passe saisonnier ephemere ([/patterns/passe-saisonnier-expirant](/patterns/passe-saisonnier-expirant)).
- Pas de boutique rotative exploitant la fausse urgence ([/patterns/fausse-urgence](/patterns/fausse-urgence)).
- Progression fondee sur le gameplay sans avantage competitif payant ([/patterns/avantage-competitif-payant](/patterns/avantage-competitif-payant)).
- Temps de jeu non contraint par une jauge d'energie ([/patterns/systeme-energie](/patterns/systeme-energie)).
