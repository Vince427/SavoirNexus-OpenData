---
type: pattern
id: connexion-permanente-solo
title: Connexion permanente en mode solo / obsolescence serveur
lang: fr
category: progression
severity_base: 4
domains: [games]
aliases:
  - always-online single-player
  - drm connexion permanente
  - stop killing games
  - obsolescence serveur
psychology: >
  Prive l'acheteur du contrôle effectif sur un bien numérique acquis à titre
  onéreux et crée une dépendance unilatérale envers la disponibilité des
  serveurs de l'éditeur, exposant l'œuvre à devenir totalement injouable
  après l'arrêt du support.
criteria:
  includes:
    - Une connexion Internet active et authentifiée aux serveurs de l'éditeur est exigée pour lancer ou poursuivre une campagne strictement solo
    - L'interruption réseau ou la fermeture des serveurs rend le jeu solo inaccessible ou efface la progression locale
    - Aucun mode hors-ligne complet ni plan de fin de vie pérenne (patch hors-ligne ou serveur communautaire) n'est fourni
  excludes:
    - Jeu strictement multijoueur en ligne ou MMO par nature dont le principe repose sur la synchronisation entre joueurs
    - Vérification ponctuelle unique à l'activation initiale suivie d'un fonctionnement hors-ligne illimité
    - Mode solo intégralement jouable hors connexion sans dégradation ni perte de sauvegarde
references:
  - title: Initiative citoyenne européenne « Stop Destroying Videogames / Stop Killing Games »
    authors: European Citizens' Initiative / DG JUST
    url: https://citizens-initiative.europa.eu/initiatives/details/2024/000007_en
    year: 2024
  - regulation: /regulations/eu-digital-fairness-act
regulated_by:
  - /regulations/eu-digital-fairness-act
tags: [obsolescence, drm, hors-ligne, europe, stop-killing-games]
---

# Connexion permanente en mode solo / obsolescence serveur

Exigence technique imposant une liaison continue aux serveurs de l'éditeur pour jouer seul, exposant le titre à une obsolescence définitive lors de la fermeture des serveurs.

## Mécanisme

Un jeu commercialisé avec une campagne ou un mode solo complet refuse de démarrer ou coupe la session en cours dès que le serveur distant est injoignable. Lorsque l'éditeur met fin à l'exploitation commerciale du service, les exemplaires achetés par les joueurs deviennent inutilisables sans correctif de préservation hors-ligne.

## Cadre européen

Cette pratique est au cœur des travaux européens sur la durabilité numérique et l'initiative citoyenne **Stop Killing Games** examinée dans le sillage du **Digital Fairness Act**.

## Comment le vérifier

- Lancer le mode solo après avoir coupé l'accès réseau de la machine ou de la console.
- Consulter les conditions d'utilisation et fiches produit (mention « Connexion Internet requise » sur un jeu solo).
- Vérifier s'il existe un patch officiel permettant l'exécution hors-ligne après la fin du support commercial.
