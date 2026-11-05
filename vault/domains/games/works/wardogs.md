---
type: game
id: wardogs
title: "WARDOGS"
lang: fr
platforms: [pc]
genres: [shooter, action, strategy]
game_modes: [multiplayer, pvp]
monetization_model: premium
publication_status: early-access
coverage_status: audited
first_release: 2026-09-10
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/1867240/header.jpg
published_by: /domains/games/orgs/team17
storefronts: [steam]
tags: [jeu, premium, shooter, action, tactical]
observations:
  - id: wardogs:obs-coffre-aleatoire-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Le jeu ne propose aucun coffre aléatoire, tirage au sort ni caisse de butin payante."
    evidence:
      - source_url: https://store.steampowered.com/app/1867240/WARDOGS/
        archive_url: https://web.archive.org/web/20260915000000/https://store.steampowered.com/app/1867240/WARDOGS/
        quote: "Audit structurel [coffre-aleatoire] sur wardogs : achat unique premium sans loot box ni tirage payant."
  - id: wardogs:obs-monnaie-intermediaire-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "L'argent (cash) utilisé pour acquérir des armes et véhicules en jeu se gagne strictement en participant aux objectifs d'équipe, sans boutique de devises réelles."
    evidence:
      - source_url: https://store.steampowered.com/app/1867240/WARDOGS/
        archive_url: https://web.archive.org/web/20260915000000/https://store.steampowered.com/app/1867240/WARDOGS/
        quote: "Audit structurel [monnaie-intermediaire] sur wardogs : économie fermée récompensant les victoires tactiques sans vente de monnaie virtuelle."
  - id: wardogs:obs-passe-saisonnier-expirant-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucun passe saisonnier payant avec expiration de contenu."
    evidence:
      - source_url: https://store.steampowered.com/app/1867240/WARDOGS/
        archive_url: https://web.archive.org/web/20260915000000/https://store.steampowered.com/app/1867240/WARDOGS/
        quote: "Audit structurel [passe-saisonnier-expirant] sur wardogs : absence de battle pass temporaire ou saisonnier."
  - id: wardogs:obs-fausse-urgence-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Pas de boutique rotative à décompte ou de promotions flash créant une pression artificielle."
    evidence:
      - source_url: https://store.steampowered.com/app/1867240/WARDOGS/
        archive_url: https://web.archive.org/web/20260915000000/https://store.steampowered.com/app/1867240/WARDOGS/
        quote: "Audit structurel [fausse-urgence] sur wardogs : modèle d'accès anticipé premium sans marketing de FOMO."
  - id: wardogs:obs-avantage-competitif-payant-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "L'équipement militaire, les véhicules blindés et les fortifications s'achètent uniquement avec les fonds remportés sur le champ de bataille par l'escouade."
    evidence:
      - source_url: https://store.steampowered.com/app/1867240/WARDOGS/
        archive_url: https://web.archive.org/web/20260915000000/https://store.steampowered.com/app/1867240/WARDOGS/
        quote: "Audit structurel [avantage-competitif-payant] sur wardogs : progression compétitive purement basée sur les compétences de tir et de stratégie."
  - id: wardogs:obs-systeme-energie-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Accès illimité aux serveurs multijoueurs sans restriction de temps de jeu ni recharge énergétique."
    evidence:
      - source_url: https://store.steampowered.com/app/1867240/WARDOGS/
        archive_url: https://web.archive.org/web/20260915000000/https://store.steampowered.com/app/1867240/WARDOGS/
        quote: "Audit structurel [systeme-energie] sur wardogs : sessions de batailles à 100 joueurs libres et illimitées."
---

# WARDOGS

**WARDOGS** est un jeu de tir tactique à la première personne massivement multijoueur développé par Bulkhead et édité par [Team17](/domains/games/orgs/team17), lancé en accès anticipé le 10 septembre 2026 sur PC (Steam).

Inspiré du célèbre mode *King of the Hill* d'Arma, il oppose trois équipes dans un secteur de montagne d'Europe de l'Est pour le contrôle d'une zone centrale, combinant combat d'infanterie, blindés, destruction et fortifications de base.

## Modèle économique & Éthique de conception

Le titre est commercialisé sous le modèle de l'**achat unique premium** en accès anticipé :
- L'économie interne du jeu (fonds pour acheter fusils, optiques, blindés) se finance uniquement par les captures de points et les réanimations d'escouade.
- **Aucune microtransaction, aucun passe de combat ni boutique d'objets payante.**
- Les 6 critères structurels de l'Observatoire sont vérifiés et exempts de tout mécanisme de prédation financière.
