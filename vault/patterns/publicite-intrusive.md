---
type: pattern
id: publicite-intrusive
title: Publicité intrusive
lang: fr
category: monetization
severity_base: 3
domains: [games]
aliases:
  - publicité forcée
  - interstitiel forcé
  - forced ads
  - interstitial ads
psychology: >
  Dégradation délibérée de l'ergonomie et rupture d'immersion (friction artificielle).
  L'agacement provoqué par l'interruption contrainte incite le joueur à payer pour
  retrouver une expérience normale, ou monétise son attention passive sans consentement actif.
criteria:
  includes:
    - Diffusion de publicités interstitielles (vidéos, pleins écrans) non déclenchées par une demande expresse du joueur
    - Interruption forcée du flux de jeu exigeant un temps d'attente incompressible ou le paiement d'une option payante
    - Bannières publicitaires occupant une portion significative de l'écran ou superposées aux contrôles
  excludes:
    - Publicités récompensées (« rewarded ads ») activées exclusivement par le joueur en échange d'un bonus facultatif
    - Mention passive des crédits, éditeurs ou partenaires sur l'écran titre sans interruption de partie
    - Annonces promotionnelles internes facultatives au lancement sans coupure en pleine session
references:
  - title: "Dark Patterns in Mobile Applications: An In-Depth Study"
    authors: Di Geronimo, Braz, Fregnan, Palomba, Bacchelli
    venue: ACM Transactions on Software Engineering and Methodology (TOSEM)
    year: 2020
  - title: Deceptive patterns — Forced action & intrusive advertisements
    authors: Brignull
    url: https://www.deceptive.design/types
tags: [monétisation, friction, interface, mobile]
---

# Publicité intrusive

Une interruption publicitaire imposée qui dégrade l'expérience de jeu pour forcer l'achat d'une option « sans publicité » ou monétiser l'attention captive.

## Mécanisme

Le joueur est interrompu en pleine session ou entre deux niveaux par des encarts publicitaires non sollicités (vidéos de 15 à 30 secondes, bannières bloquantes, fenêtres surgissantes).

Ce modèle crée une **friction artificielle négative** : le jeu ne vend pas du contenu additionnel, il vend **la suppression d'une nuisance** qu'il a lui-même injectée dans l'interface.

## Pourquoi c'est un pattern de monétisation déloyale

1. **La monétisation de la frustration** : L'option payante « Supprimer les publicités » monétise le soulagement d'une gêne programmée.
2. **Le piège du clic accidentel** : Les boutons de fermeture (« X » microscopique ou retardé) provoquent des redirections involontaires vers des magasins d'applications.

## Comment le vérifier

- Lancer une partie et progresser à travers plusieurs niveaux.
- Constater si des publicités vidéo ou des bannières bloquantes se déclenchent sans sollicitation préalable de l'utilisateur.
- Vérifier si une transaction payante est proposée pour désactiver ces affichages.
