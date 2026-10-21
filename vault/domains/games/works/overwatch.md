---
type: game
id: overwatch
title: Overwatch
lang: fr
platforms: [pc, playstation, xbox, nintendo-switch]
monetization_model: premium-plus-mtx
coverage_status: partially_audited
first_release: 2016-05-24
published_by: /domains/games/orgs/blizzard-entertainment
aliases:
  - Overwatch 1
tags: [correction, coffre-aléatoire]

claims:

  - id: overwatch:c01
    statement: >
      Les objets cosmétiques s'obtenaient principalement par des coffres
      aléatoires, achetables en monnaie réelle. Ce système a été supprimé : les
      coffres ont cessé d'être vendus le 30 août 2022, ceux déjà détenus ont été
      ouverts automatiquement, et l'acquisition est passée à un passe de combat
      et une boutique à prix affichés.
    pattern: /patterns/coffre-aleatoire
    status: corrected
    confidence: proven
    severity: 3
    valid_until: 2022-08-30
    evidence:
      - kind: article
        source_url: https://www.forbes.com/sites/krisholt/2022/06/16/overwatch-2-has-a-battle-pass-and-loot-boxes-are-being-removed-as-it-goes-free-to-play/
        archive_url: http://web.archive.org/web/20251205123219/https://www.forbes.com/sites/krisholt/2022/06/16/overwatch-2-has-a-battle-pass-and-loot-boxes-are-being-removed-as-it-goes-free-to-play/
        captured: 2025-12-05
        rights: Article de presse, cité au titre du droit de citation.
        quote: >
          Annonce en juin 2022 de la suppression complète des coffres
          aléatoires, remplacés par un passe de combat et une boutique.
      - kind: article
        source_url: https://www.nintendolife.com/news/2022/06/overwatch-2-is-getting-rid-of-loot-boxes-in-favour-of-a-battle-pass
        archive_url: http://web.archive.org/web/20250916222641/https://www.nintendolife.com/news/2022/06/overwatch-2-is-getting-rid-of-loot-boxes-in-favour-of-a-battle-pass
        captured: 2025-09-16
        rights: Article de presse, cité au titre du droit de citation.
    notes: >
      Les objets déjà achetés n'ont pas été perdus : les coffres détenus ont été
      ouverts automatiquement avant la bascule. C'est un point de méthode — une
      correction qui aurait effacé des achats aurait créé un préjudice nouveau.
---

# Overwatch

Jeu de tir en équipe publié par [Blizzard Entertainment](/domains/games/orgs/blizzard-entertainment).

> **Un pattern retiré, remplacé par un autre.** Cette fiche est la plus utile du
> fonds pour comprendre ce que le projet ne fait pas.

## Ce qui a changé

Le système de coffres aléatoires — mécanique d'acquisition principale des objets
cosmétiques depuis 2016 — a été supprimé en 2022. Les coffres ont cessé d'être
vendus le 30 août, ceux déjà détenus ont été ouverts automatiquement, et
l'acquisition est passée à un passe de combat assorti d'une boutique à prix
affichés.

Le claim est en statut **`corrected`**, et il ne pèse plus rien dans le score.

## Le point qui empêche de conclure trop vite

Supprimer un coffre aléatoire supprime le hasard payant. Ça ne rend pas la
monétisation neutre pour autant : un passe de combat relève d'un autre pattern
du fonds, le [passe saisonnier expirant](/patterns/passe-saisonnier-expirant),
et une boutique à prix affichés peut relever de la
[monnaie intermédiaire](/patterns/monnaie-intermediaire).

**Aucun claim n'est ouvert ici sur le système de remplacement**, parce
qu'aucun relevé de première main n'a été versé au fonds. Ni les prix, ni la
cadence de déblocage, ni le sort des récompenses non débloquées n'ont été
documentés avec preuve archivée.

C'est une lacune, et elle est déclarée. La tentation serait d'écrire « le
remplacement est pire » — c'est une opinion largement partagée, et elle n'a rien
à faire dans une fiche sans relevé chiffré.

## Ce que ça dit du calcul de sévérité

Le score actuel de cette œuvre est **nul**, puisque son unique claim est
corrigé. Un lecteur pourrait en conclure que la monétisation ne pose plus aucune
question — et il aurait tort.

Un score bas signifie **« rien de pesant n'est documenté »**, pas « rien de
pesant n'existe ». La différence est capitale, et c'est pourquoi le projet
n'affiche jamais de classement : un jeu peu documenté y apparaîtrait vertueux.

## Ce qui reste à documenter

- Cadence de déblocage du passe et sort des récompenses non réclamées
- Grille de prix de la boutique et existence d'un solde résiduel
- Comparaison du coût d'acquisition avant et après la bascule
