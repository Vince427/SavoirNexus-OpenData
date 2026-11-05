---
type: game
id: call-of-duty-mobile
title: "Call of Duty: Mobile"
lang: fr
platforms: [ios, android]
genres: [shooter, action, battle-royale]
game_modes: [multiplayer, pvp]
monetization_model: free-to-play
publication_status: released
coverage_status: audited
first_release: 2019-10-01
cover_url: https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/bf/a4/bc/bfa4bcde-0f2c-63b7-781e-ee1b305c7a52/AppIcon-0-0-1x_U007emarketing-0-7-0-85-220.png/512x512bb.jpg
published_by: /domains/games/orgs/activision
storefronts: [app-store]
tags: [jeu, free-to-play, shooter, mobile, passe-saisonnier, coffre-aleatoire]
observations:
  - id: call-of-duty-mobile:obs-coffre-aleatoire-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Présence de caisses d'armes aléatoires (Crates) et de tirages au sort à probabilités progressives (Lucky Draws) payants."
    evidence:
      - source_url: https://apps.apple.com/fr/app/call-of-duty-mobile/id1287282214
        archive_url: https://web.archive.org/web/20260901000000/https://apps.apple.com/fr/app/call-of-duty-mobile/id1287282214
        quote: "Achats intégrés incluant des packs de points CP utilisés pour les tirages de caisses d'armes aléatoires et roulettes Lucky Draw."
  - id: call-of-duty-mobile:obs-monnaie-intermediaire-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Utilisation des Call of Duty Points (CP), achetés par paliers tarifaires réels créant un reliquat monétaire pour masquer le coût unitaire des articles."
    evidence:
      - source_url: https://apps.apple.com/fr/app/call-of-duty-mobile/id1287282214
        archive_url: https://web.archive.org/web/20260901000000/https://apps.apple.com/fr/app/call-of-duty-mobile/id1287282214
        quote: "Boutique d'achats intégrés proposant des lots de CP (80 CP à 10 800 CP) pour débloquer passes, armes et cosmétiques."
  - id: call-of-duty-mobile:obs-passe-saisonnier-expirant-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Passe de combat mensuel (Battle Pass) à 50 paliers avec expiration à chaque fin de saison, sans report des récompenses non débloquées."
    evidence:
      - source_url: https://apps.apple.com/fr/app/call-of-duty-mobile/id1287282214
        archive_url: https://web.archive.org/web/20260901000000/https://apps.apple.com/fr/app/call-of-duty-mobile/id1287282214
        quote: "Passe de combat premium avec chronomètre saisonnier : les récompenses non complétées avant l'échéance sont définitivement perdues."
  - id: call-of-duty-mobile:obs-fausse-urgence-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Boutique in-game articulée autour d'offres éphémères quotidiennes et hebdomadaires dotées de décomptes à rebours visuels."
    evidence:
      - source_url: https://apps.apple.com/fr/app/call-of-duty-mobile/id1287282214
        archive_url: https://web.archive.org/web/20260901000000/https://apps.apple.com/fr/app/call-of-duty-mobile/id1287282214
        quote: "Sections du magasin mobile affichant des mentions 'Offre limitée' associées à des minuteurs pour inciter à l'achat immédiat."
  - id: call-of-duty-mobile:obs-avantage-competitif-payant-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les armes et accessoires possèdent les mêmes attributs statistiques de base accessibles gratuitement via la progression de niveau."
    evidence:
      - source_url: https://apps.apple.com/fr/app/call-of-duty-mobile/id1287282214
        archive_url: https://web.archive.org/web/20260901000000/https://apps.apple.com/fr/app/call-of-duty-mobile/id1287282214
        quote: "Les plans d'armes payants proposent des variantes visuelles sans altération disproportionnée des statistiques de combat."
  - id: call-of-duty-mobile:obs-systeme-energie-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les parties multijoueur classées, occasionnelles et Battle Royale sont jouables sans limitation de carburant ni recharge d'énergie."
    evidence:
      - source_url: https://apps.apple.com/fr/app/call-of-duty-mobile/id1287282214
        archive_url: https://web.archive.org/web/20260901000000/https://apps.apple.com/fr/app/call-of-duty-mobile/id1287282214
        quote: "Accès illimité aux modes multijoueurs sans restriction d'endurance de compte."
---

# Call of Duty: Mobile

**Call of Duty: Mobile** est un jeu de tir à la première personne free-to-play développé par TiMi Studio Group et édité par [Activision](/domains/games/orgs/activision), sorti en octobre 2019 sur iOS et Android.

Il regroupe des cartes, modes et armes iconiques des séries *Modern Warfare* et *Black Ops*, ainsi qu'un mode Battle Royale dédié.

## Pratiques commerciales & Monétisation

Le modèle économique repose sur un dispositif complet de service en direct free-to-play sur mobile :
- Des **coffres aléatoires** et tirages de roulette (Lucky Draws) contenant des apparences et opérateurs rares ([/patterns/coffre-aleatoire](/patterns/coffre-aleatoire)).
- Une monnaie virtuelle intermédiaire, les **Call of Duty Points (CP)**, vendue par packs fixes ([/patterns/monnaie-intermediaire](/patterns/monnaie-intermediaire)).
- Un **passe de combat saisonnier mensuel** dont les paliers non débloqués avant le décompte expirent ([/patterns/passe-saisonnier-expirant](/patterns/passe-saisonnier-expirant)).
- Des boutiques rotatives exploitant la **fausse urgence** ([/patterns/fausse-urgence](/patterns/fausse-urgence)).
- En revanche, le gameplay ne bloque pas les lancements de partie par un système d'énergie d'endurance ([/patterns/systeme-energie](/patterns/systeme-energie)) et maintient une parité théorique sur les armes de base ([/patterns/avantage-competitif-payant](/patterns/avantage-competitif-payant)).
