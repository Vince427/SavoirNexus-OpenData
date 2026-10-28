---
type: game
id: ea-sports-fc
title: EA Sports FC (anciennement FIFA)
lang: fr
platforms: [pc, playstation, xbox, nintendo-switch, ios, android]
monetization_model: premium-plus-mtx
coverage_status: audited
published_by: /domains/games/orgs/electronic-arts
aliases:
  - FIFA Ultimate Team
  - FUT
  - EA Sports FC Ultimate Team
tags: [sport, coffre-aléatoire, contentieux]

claims:

  - id: ea-sports-fc:c01
    statement: >
      Le mode Ultimate Team propose des pochettes de cartes achetables en
      monnaie réelle, dont le contenu est déterminé par le hasard au moment de
      l'ouverture.
    pattern: /patterns/coffre-aleatoire
    status: verified
    confidence: proven
    severity: 4
    valid_from: 2018-01-01
    evidence:
      - kind: regulatory
        source_url: https://www.videogameschronicle.com/news/dutch-judge-rules-that-ea-should-be-fined-e250k-every-week-until-it-removes-fifa-loot-boxes/
        archive_url: http://web.archive.org/web/20260722174733/https://www.videogameschronicle.com/news/dutch-judge-rules-that-ea-should-be-fined-e250k-every-week-until-it-removes-fifa-loot-boxes/
        captured: 2026-07-22
        rights: Article de presse rapportant une décision de justice.
        quote: >
          L'autorité néerlandaise des jeux de hasard avait retenu en 2018 que le
          mécanisme des pochettes Ultimate Team contrevenait à la loi sur les
          jeux de hasard.
      - kind: regulatory
        source_url: https://www.videogameschronicle.com/news/dutch-court-overrules-decision-to-fine-ea-e10-million-for-fifa-loot-boxes/
        archive_url: http://web.archive.org/web/20260416182241/https://www.videogameschronicle.com/news/dutch-court-overrules-decision-to-fine-ea-e10-million-for-fifa-loot-boxes/
        captured: 2026-04-16
        rights: Article de presse rapportant une décision de justice.
        quote: >
          La juridiction suprême néerlandaise a annulé l'amende de 10 millions
          d'euros, retenant que les pochettes ne constituaient pas un jeu de
          hasard distinct mais s'inscrivaient dans un jeu d'adresse plus large.
    notes: >
      Ce claim porte exclusivement sur le FAIT — des pochettes payantes au
      contenu aléatoire — qui n'a jamais été contesté par aucune partie. Il ne
      porte pas sur la qualification juridique de ce fait, qui a été retenue
      puis rejetée par des juridictions successives. Voir le corps de la fiche.
observations:
  - id: ea-sports-fc:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucune restriction du nombre de matchs jouables."
    evidence:
      - source_url: https://www.ea.com/fr-fr/games/ea-sports-fc
        archive_url: https://web.archive.org/web/20241015000000/https://www.ea.com/fr-fr/games/ea-sports-fc
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur ea-sports-fc : Aucune restriction du nombre de matchs jouables."
  - id: ea-sports-fc:obs-monnaie-intermediaire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les Points FC sont vendus par lots forfaitaires en devise réelle pour l'achat de packs et d'entrées Draft dans Ultimate Team."
    evidence:
      - source_url: https://www.ea.com/fr-fr/games/ea-sports-fc
        archive_url: https://web.archive.org/web/20241015000000/https://www.ea.com/fr-fr/games/ea-sports-fc
        quote: "Relevé d'audit Lot 4 [monnaie-intermediaire -> observed] sur ea-sports-fc : Les Points FC sont vendus par lots forfaitaires en devise réelle pour l'achat de packs et d'entrées Draft dans Ultimate Team."
  - id: ea-sports-fc:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "L'achat de packs en Points FC permet d'aligner ou de revendre des joueurs aux statistiques supérieures dans les compétitions en ligne Ultimate Team."
    evidence:
      - source_url: https://www.ea.com/fr-fr/games/ea-sports-fc
        archive_url: https://web.archive.org/web/20241015000000/https://www.ea.com/fr-fr/games/ea-sports-fc
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> observed] sur ea-sports-fc : L'achat de packs en Points FC permet d'aligner ou de revendre des joueurs aux statistiques supérieures dans les compétitions en ligne Ultimate Team."
  - id: ea-sports-fc:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Offres promotionnelles sous compte à rebours et packs Lightning Rounds en quantité globale limitée dans la boutique Ultimate Team."
    evidence:
      - source_url: https://www.ea.com/fr-fr/games/ea-sports-fc
        archive_url: https://web.archive.org/web/20241015000000/https://www.ea.com/fr-fr/games/ea-sports-fc
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> observed] sur ea-sports-fc : Offres promotionnelles sous compte à rebours et packs Lightning Rounds en quantité globale limitée dans la boutique Ultimate Team."
  - id: ea-sports-fc:obs-passe-saisonnier-expirant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Paliers d'objectifs saisonniers Ultimate Team expirant à la fin de chaque saison de 4 à 6 semaines."
    evidence:
      - source_url: https://www.ea.com/fr-fr/games/ea-sports-fc
        archive_url: https://web.archive.org/web/20241015000000/https://www.ea.com/fr-fr/games/ea-sports-fc
        quote: "Relevé d'audit Lot 4 [passe-saisonnier-expirant -> observed] sur ea-sports-fc : Paliers d'objectifs saisonniers Ultimate Team expirant à la fin de chaque saison de 4 à 6 semaines."

---

# EA Sports FC (anciennement FIFA)

Série de jeux de football publiée par [Electronic Arts](/domains/games/orgs/electronic-arts).

> **La fiche la plus importante du fonds sur le plan de la méthode.** Elle
> montre comment documenter un mécanisme dont la qualification juridique a été
> tranchée dans les deux sens.

## Ce que le claim dit, et ce qu'il ne dit pas

Le claim `ea-sports-fc:c01` affirme une seule chose : **les pochettes sont
payantes et leur contenu est aléatoire.** Ce fait n'a jamais été contesté, par
personne, à aucun stade de la procédure. C'est de la description, et c'est
vérifiable en une capture de l'écran d'achat.

Il n'affirme **pas** qu'il s'agit d'un jeu de hasard. Cette qualification
appartient aux juridictions, et elles se sont prononcées — dans les deux sens.

## Le contentieux néerlandais, dans l'ordre

| Étape | Décision |
|---|---|
| 2018 | L'autorité néerlandaise des jeux de hasard retient que le mécanisme contrevient à la loi |
| — | Amende de **10 millions d'euros**, assortie d'une astreinte hebdomadaire |
| — | Une juridiction inférieure confirme |
| **Dernière instance** | **Annulation.** L'amende est écartée. |

Le motif de l'annulation mérite d'être lu attentivement : la juridiction suprême
a retenu que les pochettes **ne constituent pas un jeu de hasard autonome**,
puisqu'elles s'inscrivent dans un mode de jeu relevant plus largement de
l'adresse.

C'est un raisonnement de droit, et il s'oppose frontalement à celui de la
[Commission belge en 2018](/regulations/be-loot-boxes-2018), qui avait retenu la
qualification de jeu de hasard sur un mécanisme comparable.

## Pourquoi ce dossier est le meilleur test du projet

**Deux autorités européennes, deux qualifications opposées, sur des faits
identiques.** Un site qui prétendrait trancher se tromperait nécessairement pour
au moins une des deux juridictions.

SavoirNexus ne tranche pas. Il enregistre :

- le **fait**, incontesté, dans un claim `verified` ;
- les **deux qualifications juridiques**, avec leurs sources archivées, dans le
  corps de la fiche ;
- et **rien d'autre**.

C'est ce que signifie « documenter des pratiques et les rattacher aux textes
applicables, sans conclure à l'illégalité ». Ce n'est pas une prudence
rhétorique : c'est la seule position tenable quand les juridictions elles-mêmes
divergent.

## La conséquence, contre-intuitive

Le claim reste `verified` **alors même que l'amende a été annulée**. Ce n'est pas
une provocation.

Le statut porte sur la véracité du fait, pas sur son illicéité. L'annulation
n'établit pas que les pochettes ne sont pas payantes et aléatoires — elle
établit qu'elles ne relèvent pas de la loi néerlandaise sur les jeux de hasard.
Deux affirmations distinctes, dont une seule est documentée ici.

Si l'éditeur estime que cette fiche laisse entendre autre chose, la
[voie de réclamation](/fr/reclamation) est ouverte, et sa réponse serait publiée
à côté du claim.

## Ce qui reste à documenter

- Les taux de tirage, s'ils sont publiés
- La grille des prix des pochettes et l'existence d'un solde résiduel
- L'état du contentieux dans les autres juridictions
