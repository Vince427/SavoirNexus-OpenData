---
type: pattern
id: anti-triche-noyau
title: Anti-triche au niveau noyau (Ring 0) ou DRM intrusif
lang: fr
category: data
severity_base: 3
domains: [games]
aliases:
  - kernel-level anti-cheat
  - ring 0 anti-cheat
  - intrusive drm
  - pilote noyau
psychology: >
  Impose une concession de souveraineté système et de sécurité informatique
  (accès noyau privilégié, souvent persistant hors session de jeu) en échange
  de l'accès à un logiciel acheté, parfois sans compatibilité Linux / Steam Deck.
criteria:
  includes:
    - Installation obligatoire d'un pilote noyau (Ring 0) ou service résident à privilèges système pour lancer le jeu ou son mode solo
    - Maintien d'un service ou pilote actif en arrière-plan après la fermeture du jeu ou au démarrage du système
    - Incompatibilité délibérée avec les environnements alternatifs (Linux / Proton / machines virtuelles) malgré l'absence de nécessité pour le jeu hors-ligne
  excludes:
    - Anti-triche exécuté strictement en espace utilisateur (user-space) actif uniquement pendant une session multijoueur
    - Vérification côté serveur sans installation de pilote privilégie sur le poste client
    - Mécanisme de protection léger n'imposant ni pilote noyau ni connexion obligatoire hors-ligne
references:
  - title: Windows Kernel-Mode Driver Security & Consumer Software Transparency Reports
    authors: EFF / Recherche sécurité logicielle
    year: 2024
tags: [données, sécurité, vie-privée, drm, technique]
---

# Anti-triche au niveau noyau (Ring 0) ou DRM intrusif

Exigence technique d'installer un pilote système privilégié (Ring 0) ou un DRM lourd contrôlant le matériel et les processus de l'utilisateur pour exécuter le jeu.

## Impacts documentés

Outre l'exposition accrue de la surface d'attaque du système d'exploitation et les problèmes de confidentialité, ces dispositifs bloquent fréquemment l'exécution sur SteamOS / Linux et continuent parfois de s'exécuter en dehors de toute partie.

## Comment le vérifier

- Consulter la fiche magasin (avertissement obligatoire sur Steam pour les anti-triches kernel-level et DRM tiers).
- Vérifier la présence d'un service ou pilote `.sys` installé au niveau système dans les notes techniques officielles.
