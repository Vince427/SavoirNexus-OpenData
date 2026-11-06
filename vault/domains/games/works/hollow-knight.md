---
type: game
id: hollow-knight
title: "Hollow Knight"
lang: fr
platforms: [pc, playstation, xbox, nintendo-switch]
genres: [action, adventure, platformer]
game_modes: [single-player]
monetization_model: premium
coverage_status: audited
first_release: 2017-02-24
wikidata_id: Q29300592
wikidata_status: verified
metadata_provenance: "Wikidata (CC0)"
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/367520/header.jpg
published_by: /domains/games/orgs/team-cherry
observations:
  - id: hollow-knight:obs-coffre-aleatoire-01
    author: audit-indies-batch1
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-indies-batch1-gameplay-audit.md
    statement: "Les charmes, fragments de masque et réceptacles d'âme sont disposés dans le monde ou vendus par des marchands PNJ. Aucun coffre ou tirage aléatoire payant."
    evidence:
      - source_url: https://store.steampowered.com/app/367520/Hollow_Knight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/367520/Hollow_Knight/
        quote: "Audit structurel [coffre-aleatoire] sur hollow-knight : achat unique premium sans caisses de butin aléatoires ni tirages payants."
  - id: hollow-knight:obs-monnaie-intermediaire-01
    author: audit-indies-batch1
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-indies-batch1-gameplay-audit.md
    statement: "La monnaie du jeu (les Géos) se récolte uniquement en éliminant des ennemis et en cassant des gisements d'insectes dans Hallownest."
    evidence:
      - source_url: https://store.steampowered.com/app/367520/Hollow_Knight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/367520/Hollow_Knight/
        quote: "Audit structurel [monnaie-intermediaire] sur hollow-knight : économie strictement interne au gameplay sans vente de devises virtuelles."
  - id: hollow-knight:obs-passe-saisonnier-expirant-01
    author: audit-indies-batch1
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-indies-batch1-gameplay-audit.md
    statement: "Toutes les extensions majeures (Hidden Dreams, The Grimm Troupe, Lifeblood, Godmaster) ont été intégrées gratuitement et de manière permanente au jeu de base."
    evidence:
      - source_url: https://store.steampowered.com/app/367520/Hollow_Knight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/367520/Hollow_Knight/
        quote: "Audit structurel [passe-saisonnier-expirant] sur hollow-knight : contenu intégralement pérenne sans passe saisonnier expirant."
  - id: hollow-knight:obs-fausse-urgence-01
    author: audit-indies-batch1
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-indies-batch1-gameplay-audit.md
    statement: "Aucune boutique en ligne ni compte à rebours promotionnel."
    evidence:
      - source_url: https://store.steampowered.com/app/367520/Hollow_Knight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/367520/Hollow_Knight/
        quote: "Audit structurel [fausse-urgence] sur hollow-knight : absence de boutique éphémère ou de compte à rebours promotionnel."
  - id: hollow-knight:obs-avantage-competitif-payant-01
    author: audit-indies-batch1
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-indies-batch1-gameplay-audit.md
    statement: "Aventure d'action solo pure ; la puissance du Chevalier dépend uniquement de l'exploration et de l'habileté."
    evidence:
      - source_url: https://store.steampowered.com/app/367520/Hollow_Knight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/367520/Hollow_Knight/
        quote: "Audit structurel [avantage-competitif-payant] sur hollow-knight : progression fondée uniquement sur le jeu sans avantage achetable."
  - id: hollow-knight:obs-systeme-energie-01
    author: audit-indies-batch1
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-21"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-indies-batch1-gameplay-audit.md
    statement: "Aucune minuterie de session ou barrière d'endurance."
    evidence:
      - source_url: https://store.steampowered.com/app/367520/Hollow_Knight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/367520/Hollow_Knight/
        quote: "Audit structurel [systeme-energie] sur hollow-knight : accès continu aux parties sans système de vies ou d'énergie payant."
  - id: hollow-knight:obs-mur-de-progression-01
    author: audit-palier2-contextuel
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/mur-de-progression
    result: not_observed
    checked_at: "2026-11-06"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-palier2-contextual-indicators-audit.md
    statement: "Progression fondée purement sur l'acquisition d'aptitudes et la maîtrise des boss. Aucun mur de difficulté artificiel ni voie de contournement payante."
    evidence:
      - source_url: https://store.steampowered.com/app/367520/Hollow_Knight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/367520/Hollow_Knight/
        quote: "Relevé Palier 2 [mur-de-progression -> not_observed] sur hollow-knight : progression organique sans grind payant."
  - id: hollow-knight:obs-recompense-quotidienne-01
    author: audit-palier2-contextuel
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/recompense-quotidienne
    result: not_observed
    checked_at: "2026-11-06"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-palier2-contextual-indicators-audit.md
    statement: "Absence de calendrier de connexion, de primes journalières ou de boucle de rétention par obligation temporelle."
    evidence:
      - source_url: https://store.steampowered.com/app/367520/Hollow_Knight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/367520/Hollow_Knight/
        quote: "Relevé Palier 2 [recompense-quotidienne -> not_observed] sur hollow-knight : respect total du temps du joueur sans rituel quotidien."
  - id: hollow-knight:obs-pression-sociale-01
    author: audit-palier2-contextuel
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/pression-sociale
    result: not_observed
    checked_at: "2026-11-06"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-palier2-contextual-indicators-audit.md
    statement: "Expérience solo intégrale et autonome sans hub multijoueur, classement en ligne ou comparaison compétitive de statut."
    evidence:
      - source_url: https://store.steampowered.com/app/367520/Hollow_Knight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/367520/Hollow_Knight/
        quote: "Relevé Palier 2 [pression-sociale -> not_observed] sur hollow-knight : absence de fonctionnalités sociales incitatives."
  - id: hollow-knight:obs-prix-barre-fictif-01
    author: audit-palier2-contextuel
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/prix-barre-fictif
    result: not_observed
    checked_at: "2026-11-06"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-palier2-contextual-indicators-audit.md
    statement: "Aucune boutique interne au jeu ; distribution commerciale transparente à tarif fixe honnête."
    evidence:
      - source_url: https://store.steampowered.com/app/367520/Hollow_Knight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/367520/Hollow_Knight/
        quote: "Relevé Palier 2 [prix-barre-fictif -> not_observed] sur hollow-knight : absence d'ancrage tarifaire trompeur."
  - id: hollow-knight:obs-publicite-intrusive-01
    author: audit-palier2-contextuel
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/publicite-intrusive
    result: not_observed
    checked_at: "2026-11-06"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-palier2-contextual-indicators-audit.md
    statement: "Immersion totale sans interruption commerciale, bannière publicitaire ou vidéo promotionnelle forcée."
    evidence:
      - source_url: https://store.steampowered.com/app/367520/Hollow_Knight/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/367520/Hollow_Knight/
        quote: "Relevé Palier 2 [publicite-intrusive -> not_observed] sur hollow-knight : zéro affichage publicitaire tiers."
---

# Hollow Knight

Metroidvania magistral en 2D explorant le royaume d'insectes déchu d'Hallownest.

## Audit de conformite structurelle (Palier 1)
Les 6 critères structurels du Palier 1 sont tous validés et confirmés absents (6/6 Not Observed).

## Audit des indicateurs contextuels & Dark Patterns (Palier 2)
L'examen approfondi du Palier 2 confirme l'exemplarité absolue de l'œuvre :
- **[NON OBSERVE] Mur de progression** ([/patterns/mur-de-progression](/patterns/mur-de-progression))
- **[NON OBSERVE] Récompense quotidienne** ([/patterns/recompense-quotidienne](/patterns/recompense-quotidienne))
- **[NON OBSERVE] Pression sociale** ([/patterns/pression-sociale](/patterns/pression-sociale))
- **[NON OBSERVE] Prix barré fictif** ([/patterns/prix-barre-fictif](/patterns/prix-barre-fictif))
- **[NON OBSERVE] Publicité intrusive** ([/patterns/publicite-intrusive](/patterns/publicite-intrusive))
- **[NON OBSERVE] Paquet forcé** ([/patterns/paquet-force](/patterns/paquet-force))
- **[NON OBSERVE] Achat accidentel** ([/patterns/achat-accidentel](/patterns/achat-accidentel))
- **[NON OBSERVE] Confirmshaming** ([/patterns/confirmshaming](/patterns/confirmshaming))
- **[NON OBSERVE] Résiliation difficile** ([/patterns/resiliation-difficile](/patterns/resiliation-difficile))
