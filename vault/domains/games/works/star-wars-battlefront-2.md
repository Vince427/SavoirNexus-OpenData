---
type: game
id: star-wars-battlefront-2
title: Star Wars Battlefront II
lang: fr
platforms: [pc, playstation, xbox]
monetization_model: premium-plus-mtx
coverage_status: audited
first_release: 2017-11-17
published_by: /domains/games/orgs/electronic-arts
aliases:
  - Star Wars Battlefront 2
  - SWBF2
tags: [premium, correction-rapide]

claims:

  - id: star-wars-battlefront-2:c01
    statement: >
      À la veille de la sortie commerciale, la progression du jeu reposait sur
      des coffres aléatoires payants pouvant conférer un avantage en
      confrontation, et l'accès à certains personnages emblématiques exigeait
      une quantité de monnaie de jeu jugée disproportionnée par les joueurs de
      la période d'accès anticipé.
    pattern: /patterns/coffre-aleatoire
    status: corrected
    confidence: proven
    severity: 4
    valid_until: 2017-11-17
    evidence:
      - kind: article
        source_url: https://www.forbes.com/sites/erikkain/2017/11/17/rebels-destroy-star-wars-battlefront-ii-micro-transactions-but-the-war-is-far-from-over/
        archive_url: http://web.archive.org/web/20250818093949/https://www.forbes.com/sites/erikkain/2017/11/17/rebels-destroy-star-wars-battlefront-ii-micro-transactions-but-the-war-is-far-from-over/
        captured: 2025-08-18
        rights: Article de presse, cité au titre du droit de citation.
        quote: >
          L'éditeur a désactivé l'ensemble des achats intégrés le 17 novembre
          2017, quelques heures avant la sortie commerciale.
    notes: >
      Correction la plus rapide du fonds : moins de vingt-quatre heures entre la
      contestation publique et la désactivation. Elle est volontaire, à la
      différence de celle documentée sur Fortnite.
observations:
  - id: star-wars-battlefront-2:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Accès illimité aux batailles multijoueur et solo sans jauge d'endurance."
    evidence:
      - source_url: https://store.steampowered.com/app/1237950/STAR_WARS_Battlefront_II/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/1237950/STAR_WARS_Battlefront_II/
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur star-wars-battlefront-2 : Accès illimité aux batailles multijoueur et solo sans jauge d'endurance."
  - id: star-wars-battlefront-2:obs-monnaie-intermediaire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les Cristaux ont été maintenus après la refonte de 2018 comme monnaie intermédiaire dédiée à l'achat d'apparences cosmétiques."
    evidence:
      - source_url: https://store.steampowered.com/app/1237950/STAR_WARS_Battlefront_II/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/1237950/STAR_WARS_Battlefront_II/
        quote: "Relevé d'audit Lot 4 [monnaie-intermediaire -> observed] sur star-wars-battlefront-2 : Les Cristaux ont été maintenus après la refonte de 2018 comme monnaie intermédiaire dédiée à l'achat d'apparences cosmétiques."
  - id: star-wars-battlefront-2:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Depuis la mise à jour de progression de mars 2018, les Cartes des Étoiles s'obtiennent uniquement par l'expérience de classe en jeu et non par achat."
    evidence:
      - source_url: https://store.steampowered.com/app/1237950/STAR_WARS_Battlefront_II/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/1237950/STAR_WARS_Battlefront_II/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur star-wars-battlefront-2 : Depuis la mise à jour de progression de mars 2018, les Cartes des Étoiles s'obtiennent uniquement par l'expérience de classe en jeu et non par achat."
  - id: star-wars-battlefront-2:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les apparences cosmétiques demeurent accessibles de façon permanente dans le menu des collections."
    evidence:
      - source_url: https://store.steampowered.com/app/1237950/STAR_WARS_Battlefront_II/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/1237950/STAR_WARS_Battlefront_II/
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> not_observed] sur star-wars-battlefront-2 : Les apparences cosmétiques demeurent accessibles de façon permanente dans le menu des collections."
  - id: star-wars-battlefront-2:obs-passe-saisonnier-expirant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucun passe de combat saisonnier payant ou expirant."
    evidence:
      - source_url: https://store.steampowered.com/app/1237950/STAR_WARS_Battlefront_II/
        archive_url: https://web.archive.org/web/20241015000000/https://store.steampowered.com/app/1237950/STAR_WARS_Battlefront_II/
        quote: "Relevé d'audit Lot 4 [passe-saisonnier-expirant -> not_observed] sur star-wars-battlefront-2 : Aucun passe de combat saisonnier payant ou expirant."

---

# Star Wars Battlefront II

Jeu de tir publié par [Electronic Arts](/domains/games/orgs/electronic-arts).

> **Cette fiche existe pour ce que l'éditeur a fait, pas pour ce qu'il avait
> prévu.** C'est le cas de correction volontaire le plus net du fonds.

## Ce qui s'est passé

Pendant la période d'accès anticipé de novembre 2017, les joueurs constatent que
la progression repose sur des coffres aléatoires payants, et que l'accès à des
personnages emblématiques demande un temps de jeu considéré comme
disproportionné.

La contestation est massive et publique. **Le 17 novembre 2017, quelques heures
avant la sortie commerciale, l'éditeur désactive l'intégralité des achats
intégrés.** Le système est ensuite entièrement reconçu avant leur réintroduction
sous une forme cosmétique.

## Pourquoi c'est le cas le plus important de la bibliothèque

Un projet capable de n'enregistrer que des griefs est un réquisitoire : il se
lit comme tel, se conteste comme tel, et se défend mal.

Ici, le claim est en statut **`corrected`**, avec sa date. Il **ne pèse rien**
dans le score de sévérité — la sanction du calcul est nulle, exactement comme si
la pratique n'avait jamais existé. Ce qui reste, c'est la trace historique et le
crédit.

Et le délai compte : moins de vingt-quatre heures entre la contestation et le
retrait. Aucune autorité n'était saisie, aucune sanction n'était encourue. C'est
une correction volontaire, et c'est affiché comme telle.

## La distinction avec le cas Fortnite

Les deux fiches portent un claim `corrected`, et le score les traite
identiquement. Mais les situations diffèrent :

| | Battlefront II | Fortnite |
|---|---|---|
| Déclencheur | contestation publique | ordonnance d'autorité |
| Nature | **volontaire** | imposée |
| Délai | moins de 24 h | plusieurs années |

Le modèle de données n'encode pas cette différence — `corrected` ne distingue
pas le motif. C'est une limite connue, signalée ici plutôt que masquée.

## Ce qui reste à documenter

Le système de progression **actuel**, qui n'a fait l'objet d'aucun relevé dans
ce fonds. L'absence de claim sur l'état présent ne vaut ni certification ni
soupçon : elle signifie qu'aucune preuve archivée n'a encore été versée.
