---
type: game
id: diablo-immortal
title: Diablo Immortal
lang: fr
platforms: [pc, ios, android]
monetization_model: free-to-play
coverage_status: audited
first_release: 2022-06-02
published_by: /domains/games/orgs/blizzard-entertainment
tags: [free-to-play, coffre-aléatoire, retrait-de-marché]

claims:

  - id: diablo-immortal:c01
    statement: >
      Le jeu n'a pas été mis à disposition en Belgique ni aux Pays-Bas, l'éditeur
      ayant indiqué que ses mécaniques étaient incompatibles avec la
      réglementation de ces pays sur les coffres aléatoires.
    pattern: /patterns/coffre-aleatoire
    status: verified
    confidence: proven
    severity: 5
    valid_from: 2022-06-02
    evidence:
      - kind: article
        source_url: https://www.engadget.com/diablo-immortal-loot-box-laws-belgium-netherlands-141234104.html
        archive_url: http://web.archive.org/web/20260312193845/https://www.engadget.com/diablo-immortal-loot-box-laws-belgium-netherlands-141234104.html
        captured: 2026-03-12
        rights: Article de presse, cité au titre du droit de citation.
        quote: >
          Le jeu n'est disponible ni aux Pays-Bas ni en Belgique, sur PC comme
          sur mobile, en raison des lois encadrant les coffres aléatoires.
      - kind: article
        source_url: https://www.gamesradar.com/diablo-immortal-pulled-from-launch-in-belgium-and-the-netherlands-over-loot-box-laws/
        archive_url: http://web.archive.org/web/20240823232022/https://www.gamesradar.com/diablo-immortal-pulled-from-launch-in-belgium-and-the-netherlands-over-loot-box-laws/
        captured: 2024-08-23
        rights: Article de presse, cité au titre du droit de citation.
    notes: >
      Le fait documenté est l'indisponibilité et son motif déclaré. Le détail
      des mécaniques concernées n'a fait l'objet d'aucun relevé de première main
      dans ce fonds — d'où l'absence de claim distinct sur leur fonctionnement.
observations:
  - id: diablo-immortal:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucune jauge d'énergie ne bloque l'accès aux donjons et failles."
    evidence:
      - source_url: https://diabloimmortal.blizzard.com/fr-fr/
        archive_url: https://web.archive.org/web/20241015000000/https://diabloimmortal.blizzard.com/fr-fr/
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur diablo-immortal : Aucune jauge d'énergie ne bloque l'accès aux donjons et failles."
  - id: diablo-immortal:obs-monnaie-intermediaire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les Orbes éternels achetés en argent réel sont convertis en Platine ou en Emblèmes légendaires selon des paliers forfaitaires."
    evidence:
      - source_url: https://diabloimmortal.blizzard.com/fr-fr/
        archive_url: https://web.archive.org/web/20241015000000/https://diabloimmortal.blizzard.com/fr-fr/
        quote: "Relevé d'audit Lot 4 [monnaie-intermediaire -> observed] sur diablo-immortal : Les Orbes éternels achetés en argent réel sont convertis en Platine ou en Emblèmes légendaires selon des paliers forfaitaires."
  - id: diablo-immortal:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les Gemmes légendaires 5 étoiles obtenues via Emblèmes payants augmentent directement la Résonance et la puissance en PvP Champ de bataille."
    evidence:
      - source_url: https://diabloimmortal.blizzard.com/fr-fr/
        archive_url: https://web.archive.org/web/20241015000000/https://diabloimmortal.blizzard.com/fr-fr/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> observed] sur diablo-immortal : Les Gemmes légendaires 5 étoiles obtenues via Emblèmes payants augmentent directement la Résonance et la puissance en PvP Champ de bataille."
  - id: diablo-immortal:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Packs promotionnels temporaires déclenchés lors de la progression avec indication de valeur multipliée."
    evidence:
      - source_url: https://diabloimmortal.blizzard.com/fr-fr/
        archive_url: https://web.archive.org/web/20241015000000/https://diabloimmortal.blizzard.com/fr-fr/
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> observed] sur diablo-immortal : Packs promotionnels temporaires déclenchés lors de la progression avec indication de valeur multipliée."
  - id: diablo-immortal:obs-passe-saisonnier-expirant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Passe de combat mensuel à 40 paliers dont les récompenses non réclamées expirent en fin de saison."
    evidence:
      - source_url: https://diabloimmortal.blizzard.com/fr-fr/
        archive_url: https://web.archive.org/web/20241015000000/https://diabloimmortal.blizzard.com/fr-fr/
        quote: "Relevé d'audit Lot 4 [passe-saisonnier-expirant -> observed] sur diablo-immortal : Passe de combat mensuel à 40 paliers dont les récompenses non réclamées expirent en fin de saison."

---

# Diablo Immortal

Jeu d'action-RPG en free-to-play publié par [Blizzard Entertainment](/domains/games/orgs/blizzard-entertainment).

> **Le seul cas du fonds où la régulation a produit un effet visible sans
> qu'aucune sanction ne soit prononcée.**

## Ce que ce dossier montre

À la sortie de juin 2022, le jeu n'est mis à disposition ni en Belgique ni aux
Pays-Bas. Le motif communiqué par l'éditeur est explicite : ses mécaniques sont
incompatibles avec la réglementation locale sur les coffres aléatoires — voir
[la décision belge de 2018](/regulations/be-loot-boxes-2018).

L'éditeur avait deux options : modifier la monétisation, ou retirer le produit
de ces marchés. **Il a choisi la seconde.**

Ce fait est enregistré sans commentaire. Retirer un produit d'un marché est une
décision commerciale parfaitement licite, et le projet ne la qualifie pas. Ce
qu'elle établit, en revanche, est vérifiable : les mécaniques en cause étaient
suffisamment centrales pour que leur suppression ne soit pas envisagée.

## Pourquoi la sévérité maximale malgré l'absence de sanction

Le claim porte une sévérité de 5 parce qu'il est rattaché au
[coffre aléatoire](/patterns/coffre-aleatoire), seul pattern du fonds à cumuler
trois facteurs : qualification de jeu de hasard par une autorité européenne,
coût indéterminable à l'avance, et exposition de publics mineurs.

La sévérité provient du **pattern**, pas d'une appréciation sur cette œuvre en
particulier. C'est la mécanique même du calcul : un pattern grave employé
marginalement peut peser moins qu'un pattern modéré employé systématiquement.

## Ce qui reste à documenter

Le détail des mécaniques concernées. Le fonds sait que l'éditeur les a jugées
incompatibles avec deux réglementations ; il ne dispose d'aucun relevé de
première main sur leur fonctionnement, leurs taux ou leurs prix.

C'est pourquoi cette fiche ne porte **qu'un seul claim**, sur l'indisponibilité
et son motif — des faits établis — plutôt que sur les mécaniques elles-mêmes,
qui demanderaient des captures que personne n'a encore versées.
