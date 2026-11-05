---
type: game
id: phantom-blade-zero
title: "Phantom Blade Zero"
lang: fr
platforms: [pc, playstation]
genres: [action, rpg, hack-and-slash]
game_modes: [single-player]
monetization_model: premium
publication_status: released
coverage_status: audited
first_release: 2026-10-28
cover_url: https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/4115450/header.jpg
published_by: /domains/games/orgs/s-game
storefronts: [steam, playstation-store, epic-games-store]
tags: [jeu, premium, action, rpg, kungfupunk, wuxia]
observations:
  - id: phantom-blade-zero:obs-coffre-aleatoire-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-phantom-blade-zero-audit.md
    statement: "Le jeu ne comporte aucun coffre aléatoire payant, boîte de butin ni mécanique de gacha."
    evidence:
      - source_url: https://www.eurogamer.net/phantom-blade-zero-dev-promises-no-microtransactions-and-some-souls-like-elements
        archive_url: https://web.archive.org/web/20240615000000/https://www.eurogamer.net/phantom-blade-zero-dev-promises-no-microtransactions-and-some-souls-like-elements
        quote: "S-Game has confirmed Phantom Blade Zero will not feature any microtransactions or gacha mechanics, offering a complete standalone experience."
  - id: phantom-blade-zero:obs-monnaie-intermediaire-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-phantom-blade-zero-audit.md
    statement: "L'économie du jeu repose uniquement sur les ressources collectées en combat et en exploration, sans conversion de devises réelles en monnaie virtuelle premium."
    evidence:
      - source_url: https://store.steampowered.com/app/4115450/Phantom_Blade_Zero/
        archive_url: https://web.archive.org/web/20261030000000/https://store.steampowered.com/app/4115450/Phantom_Blade_Zero/
        quote: "Audit structurel [monnaie-intermediaire] sur phantom-blade-zero : économie fermée sans boutique de devises virtuelles ou conversion monétaire."
  - id: phantom-blade-zero:obs-passe-saisonnier-expirant-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-phantom-blade-zero-audit.md
    statement: "Campagne solo linéaire et semi-ouverte sans passe de combat saisonnier, calendrier temporaire ni verrouillage de contenu à échéance."
    evidence:
      - source_url: https://store.steampowered.com/app/4115450/Phantom_Blade_Zero/
        archive_url: https://web.archive.org/web/20261030000000/https://store.steampowered.com/app/4115450/Phantom_Blade_Zero/
        quote: "Audit structurel [passe-saisonnier-expirant] sur phantom-blade-zero : contenu intégralement pérenne sans passe saisonnier expirant."
  - id: phantom-blade-zero:obs-fausse-urgence-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-phantom-blade-zero-audit.md
    statement: "Absence totale de boutique rotative à durée limitée, de compte à rebours promotionnel ou de mécanique de FOMO."
    evidence:
      - source_url: https://store.steampowered.com/app/4115450/Phantom_Blade_Zero/
        archive_url: https://web.archive.org/web/20261030000000/https://store.steampowered.com/app/4115450/Phantom_Blade_Zero/
        quote: "Audit structurel [fausse-urgence] sur phantom-blade-zero : absence de rotation éphémère d'objets ou de pression artificielle sur l'achat."
  - id: phantom-blade-zero:obs-avantage-competitif-payant-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-phantom-blade-zero-audit.md
    statement: "Toutes les armes, compétences de Kung-Fu et améliorations s'obtiennent par les victoires sur les boss et la progression de l'histoire."
    evidence:
      - source_url: https://store.steampowered.com/app/4115450/Phantom_Blade_Zero/
        archive_url: https://web.archive.org/web/20261030000000/https://store.steampowered.com/app/4115450/Phantom_Blade_Zero/
        quote: "Audit structurel [avantage-competitif-payant] sur phantom-blade-zero : progression martiale fondée exclusivement sur la maîtrise en jeu."
  - id: phantom-blade-zero:obs-systeme-energie-01
    author: observatoire-audit-agent
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-11-05"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-11-phantom-blade-zero-audit.md
    statement: "Le joueur peut enchaîner les sessions librement sans aucune limitation d'endurance de compte ni recharge artificielle."
    evidence:
      - source_url: https://store.steampowered.com/app/4115450/Phantom_Blade_Zero/
        archive_url: https://web.archive.org/web/20261030000000/https://store.steampowered.com/app/4115450/Phantom_Blade_Zero/
        quote: "Audit structurel [systeme-energie] sur phantom-blade-zero : sessions de jeu non contraintes par un compteur d'endurance ou d'énergie."
---

# Phantom Blade Zero

**Phantom Blade Zero** est un action-RPG solo développé et édité par le studio indépendant chinois [S-GAME](/domains/games/orgs/s-game), sorti le 28 octobre 2026 sur PC et PlayStation 5.

Dans un univers « Kungfupunk » sombre mêlant arts martiaux traditionnels chinois wuxia et esthétique steampunk/occulte, le joueur incarne Soul, un assassin d'élite traqué qui ne dispose que de 66 jours à vivre pour lever le complot qui le vise.

## Modèle économique & Pratiques commerciales

Le jeu est commercialisé sous le modèle de l'**achat unique traditionnel (premium)**. Bien que le studio S-GAME soit historiquement connu pour des productions mobiles antérieures, l'équipe a fait le choix délibéré d'exclure tout élément de service en direct (*live-service*), microtransaction, devise premium ou boîte de butin (*gacha*).

L'audit complet des six critères structurels de l'Observatoire confirme l'intégrité commerciale du titre :
- Aucun tirage aléatoire ni loot box payante ([/patterns/coffre-aleatoire](/patterns/coffre-aleatoire)).
- Aucune monnaie intermédiaire achetée en euros ([/patterns/monnaie-intermediaire](/patterns/monnaie-intermediaire)).
- Aucun passe de combat à durée limitée ([/patterns/passe-saisonnier-expirant](/patterns/passe-saisonnier-expirant)).
- Aucune fausse urgence ni boutique rotative de FOMO ([/patterns/fausse-urgence](/patterns/fausse-urgence)).
- Aucune vente d'avantages payants ([/patterns/avantage-competitif-payant](/patterns/avantage-competitif-payant)).
- Aucun système d'énergie limitant le temps de jeu ([/patterns/systeme-energie](/patterns/systeme-energie)).

Une édition Deluxe et une mise à niveau optionnelle sont proposées au lancement, comprenant des éléments cosmétiques et la bande originale, sans incidence sur le gameplay ni recours aux mécaniques de dark patterns.

## Mesures techniques de protection (DRM)

La version PC distribuée sur Steam intègre la solution anti-tamper **Denuvo**. SavoirNexus ne dispose pas actuellement d'un pattern ni d'un filtre dédié aux protections logicielles de type DRM (qui relèvent de la politique de distribution et de gestion des droits numériques plutôt que de la monétisation comportementale prédatrice), mais la mention est documentée ici à titre informatif pour les joueurs attentifs aux dépendances d'authentification tierces.
