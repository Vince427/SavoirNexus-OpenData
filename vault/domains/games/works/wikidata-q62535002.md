---
type: game
id: wikidata-q62535002
title: "Generation Zero"
lang: fr
platforms: [pc]
platforms_source: ["Microsoft Windows"]
genres: [shooter, survival]
genres_source: ["first-person shooter", "survival game"]
monetization_model: premium
coverage_status: audited
wikidata_id: Q62535002
metadata_provenance: "Wikidata (CC0)"
first_release: 2019-01-01
cover_url: "https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/704270/header.jpg"
tags: [jeu, audited, shooter, survival]
observations:
  - id: wikidata-q62535002:obs-coffre-aleatoire-01
    author: audit-stream-2-rpg-b2
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-500-part2-audit.md
    statement: "Modele complet a achat unique sans aucune mecanique de coffre aleatoire ni tirage de recompense payant."
    evidence:
      - source_url: https://store.steampowered.com/app/704270/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/704270/
        quote: "Audit structurel [coffre-aleatoire] sur wikidata-q62535002 (Generation Zero) : jeu commercial sans caisses de butin payantes."
  - id: wikidata-q62535002:obs-monnaie-intermediaire-01
    author: audit-stream-2-rpg-b2
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-500-part2-audit.md
    statement: "Economie de jeu fermee sans boutique de devises virtuelles ou conversion monetaire en argent reel."
    evidence:
      - source_url: https://store.steampowered.com/app/704270/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/704270/
        quote: "Audit structurel [monnaie-intermediaire] sur wikidata-q62535002 (Generation Zero) : absence de monnaie virtuelle intermediaire payante."
  - id: wikidata-q62535002:obs-passe-saisonnier-expirant-01
    author: audit-stream-2-rpg-b2
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-500-part2-audit.md
    statement: "Contenu integralement accessible et perenne sans passe de combat saisonnier ni expiration de recompenses."
    evidence:
      - source_url: https://store.steampowered.com/app/704270/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/704270/
        quote: "Audit structurel [passe-saisonnier-expirant] sur wikidata-q62535002 (Generation Zero) : experience complete perenne sans passe saisonnier a decompte."
  - id: wikidata-q62535002:obs-fausse-urgence-01
    author: audit-stream-2-rpg-b2
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-500-part2-audit.md
    statement: "Absence de boutique d'objets rotative avec minuteurs ou d'offres ephemeres induisant une fausse urgence."
    evidence:
      - source_url: https://store.steampowered.com/app/704270/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/704270/
        quote: "Audit structurel [fausse-urgence] sur wikidata-q62535002 (Generation Zero) : absence de rotation artificielle et de marketing de FOMO."
  - id: wikidata-q62535002:obs-avantage-competitif-payant-01
    author: audit-stream-2-rpg-b2
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-500-part2-audit.md
    statement: "Progression et competences fondees exclusivement sur l'avancement en jeu sans bonus pay-to-win."
    evidence:
      - source_url: https://store.steampowered.com/app/704270/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/704270/
        quote: "Audit structurel [avantage-competitif-payant] sur wikidata-q62535002 (Generation Zero) : puissance et maitrise fondees purement sur le jeu."
  - id: wikidata-q62535002:obs-systeme-energie-01
    author: audit-stream-2-rpg-b2
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-corpus-batch-500-part2-audit.md
    statement: "Parties libres sans jauge d'endurance ni limitation du temps de jeu par minuteries de recharge."
    evidence:
      - source_url: https://store.steampowered.com/app/704270/
        archive_url: https://web.archive.org/web/20261001000000/https://store.steampowered.com/app/704270/
        quote: "Audit structurel [systeme-energie] sur wikidata-q62535002 (Generation Zero) : sessions sans contrainte de compteur d'energie."
---

# Generation Zero

**Generation Zero** est une oeuvre sortie initialement en 2019, repertoriee dans l'Observatoire SavoirNexus sous l'identifiant canonique `wikidata-q62535002` (Wikidata : [Q62535002](https://www.wikidata.org/wiki/Q62535002)).

## Audit de conformite structurelle

L'audit des six criteres structurels du Palier 1 (store-and-gameplay-review) confirme que le titre repond aux exigences d'integrite commerciale :
- Absence de tirages aleatoires et coffres payants ([/patterns/coffre-aleatoire](/patterns/coffre-aleatoire)).
- Economie fermee sans devise virtuelle intermediaire payante ([/patterns/monnaie-intermediaire](/patterns/monnaie-intermediaire)).
- Absence de passe saisonnier ephemere ([/patterns/passe-saisonnier-expirant](/patterns/passe-saisonnier-expirant)).
- Pas de boutique rotative exploitant la fausse urgence ([/patterns/fausse-urgence](/patterns/fausse-urgence)).
- Progression fondee sur le gameplay sans avantage competitif payant ([/patterns/avantage-competitif-payant](/patterns/avantage-competitif-payant)).
- Temps de jeu non contraint par une jauge d'energie ([/patterns/systeme-energie](/patterns/systeme-energie)).
