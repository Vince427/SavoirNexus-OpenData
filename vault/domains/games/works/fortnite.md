---
type: game
id: fortnite
title: Fortnite
lang: fr
platforms: [pc, playstation, xbox, nintendo-switch, ios, android]
monetization_model: free-to-play
coverage_status: audited
first_release: 2017-07-25
published_by: /domains/games/orgs/epic-games
aliases:
  - Fortnite Battle Royale
tags: [free-to-play, battle-royale]

claims:

  - id: fortnite:c01
    statement: >
      La Federal Trade Commission a établi que la configuration des commandes
      d'achat conduisait des joueurs à effectuer des achats non voulus à la
      pression d'une seule touche, y compris lors d'actions ordinaires telles
      que la sortie de veille ou la prévisualisation d'un objet.
    pattern: /patterns/achat-accidentel
    status: corrected
    confidence: proven
    severity: 4
    valid_until: 2023-03-14
    evidence:
      - kind: regulatory
        source_url: https://www.ftc.gov/news-events/news/press-releases/2023/03/ftc-finalizes-order-requiring-fortnite-maker-epic-games-pay-245-million-tricking-users-making
        archive_url: http://web.archive.org/web/20260610130507/https://www.ftc.gov/news-events/news/press-releases/2023/03/ftc-finalizes-order-requiring-fortnite-maker-epic-games-pay-245-million-tricking-users-making
        captured: 2026-06-10
        rights: Communiqué d'une autorité publique américaine.
        quote: >
          Ordonnance définitive imposant 245 millions de dollars de réparations
          pour avoir conduit des utilisateurs à des achats non voulus.
      - kind: regulatory
        source_url: https://www.ftc.gov/business-guidance/blog/2022/12/245-million-ftc-settlement-alleges-fortnite-owner-epic-games-used-digital-dark-patterns-charge
        archive_url: http://web.archive.org/web/20260514094036/https://www.ftc.gov/business-guidance/blog/2022/12/245-million-ftc-settlement-alleges-fortnite-owner-epic-games-used-digital-dark-patterns-charge
        captured: 2026-05-14
        rights: Analyse publiée par l'autorité elle-même.
    notes: >
      L'ordonnance interdit pour l'avenir toute facturation par recours à des
      dark patterns, ou sans consentement affirmatif. La correction est donc
      imposée par l'autorité, non volontaire — le statut `corrected` enregistre
      la cessation de la pratique, il ne préjuge pas de son motif.

  - id: fortnite:c02
    statement: >
      Des mineurs ont pu accumuler des achats facturés sans intervention
      parentale, et des utilisateurs ayant contesté des prélèvements auprès de
      leur banque se sont vu bloquer l'accès à des contenus déjà payés.
    status: corrected
    confidence: proven
    severity: 4
    valid_until: 2023-03-14
    evidence:
      - kind: regulatory
        source_url: https://www.ftc.gov/news-events/news/press-releases/2022/12/fortnite-video-game-maker-epic-games-pay-more-half-billion-dollars-over-ftc-allegations
        archive_url: http://web.archive.org/web/20260617100512/https://www.ftc.gov/news-events/news/press-releases/2022/12/fortnite-video-game-maker-epic-games-pay-more-half-billion-dollars-over-ftc-allegations
        captured: 2026-06-17
        rights: Communiqué d'une autorité publique américaine.
    notes: >
      Ce claim n'est rattaché à aucun pattern du fonds : le blocage d'accès en
      représailles d'une contestation bancaire n'a pas d'équivalent dans la
      taxonomie actuelle. C'est une lacune signalée, pas un oubli.
observations:
  - id: fortnite:obs-fausse-urgence-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/fausse-urgence
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "La boutique d'objets s'appuie sur une rotation quotidienne avec échéance de retrait affichée."
    evidence:
      - source_url: https://www.fortnite.com/
        archive_url: https://web.archive.org/web/20241015000000/https://www.fortnite.com/
        quote: "Relevé d'audit Lot 4 [fausse-urgence -> observed] sur fortnite : La boutique d'objets s'appuie sur une rotation quotidienne avec échéance de retrait affichée."
  - id: fortnite:obs-passe-saisonnier-expirant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/passe-saisonnier-expirant
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Le Passe de combat saisonnier exige de débloquer les récompenses avant la fin de la saison en cours."
    evidence:
      - source_url: https://www.fortnite.com/
        archive_url: https://web.archive.org/web/20241015000000/https://www.fortnite.com/
        quote: "Relevé d'audit Lot 4 [passe-saisonnier-expirant -> observed] sur fortnite : Le Passe de combat saisonnier exige de débloquer les récompenses avant la fin de la saison en cours."
  - id: fortnite:obs-coffre-aleatoire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/coffre-aleatoire
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Aucun coffre aléatoire payant en Battle Royale ; les lamas à butin du mode Sauver le monde affichent leur contenu exact avant achat depuis janvier 2019."
    evidence:
      - source_url: https://www.fortnite.com/
        archive_url: https://web.archive.org/web/20241015000000/https://www.fortnite.com/
        quote: "Relevé d'audit Lot 4 [coffre-aleatoire -> not_observed] sur fortnite : Aucun coffre aléatoire payant en Battle Royale ; les lamas à butin du mode Sauver le monde affichent leur contenu exact avant achat depuis janvier 2019."
  - id: fortnite:obs-monnaie-intermediaire-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/monnaie-intermediaire
    result: observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les V-Bucks constituent la devise virtuelle payante obligatoire pour acquérir tenues et passes."
    evidence:
      - source_url: https://www.fortnite.com/
        archive_url: https://web.archive.org/web/20241015000000/https://www.fortnite.com/
        quote: "Relevé d'audit Lot 4 [monnaie-intermediaire -> observed] sur fortnite : Les V-Bucks constituent la devise virtuelle payante obligatoire pour acquérir tenues et passes."
  - id: fortnite:obs-systeme-energie-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/systeme-energie
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Parties illimitées sans système de vies ou d'endurance."
    evidence:
      - source_url: https://www.fortnite.com/
        archive_url: https://web.archive.org/web/20241015000000/https://www.fortnite.com/
        quote: "Relevé d'audit Lot 4 [systeme-energie -> not_observed] sur fortnite : Parties illimitées sans système de vies ou d'endurance."
  - id: fortnite:obs-avantage-competitif-payant-01
    author: savoirnexus-editorial
    status: verified
    ontology_version: "1.1.0"
    criterion: /patterns/avantage-competitif-payant
    result: not_observed
    checked_at: "2026-10-24"
    method: store-and-gameplay-review
    audit_trail: docs/audits/2026-10-live-service-batch4-gameplay-audit.md
    statement: "Les éléments vendus en Battle Royale sont purement cosmétiques et précisent n'accorder aucun avantage compétitif."
    evidence:
      - source_url: https://www.fortnite.com/
        archive_url: https://web.archive.org/web/20241015000000/https://www.fortnite.com/
        quote: "Relevé d'audit Lot 4 [avantage-competitif-payant -> not_observed] sur fortnite : Les éléments vendus en Battle Royale sont purement cosmétiques et précisent n'accorder aucun avantage compétitif."

---

# Fortnite

Jeu de bataille royale en free-to-play publié par [Epic Games](/domains/games/orgs/epic-games).

> Cette fiche documente des **faits établis par une autorité publique**, pas des
> observations de première main. C'est la forme la plus solide de preuve dont le
> projet dispose, et elle est aussi la plus rare.

## Pourquoi cette fiche est la référence méthodologique du fonds

Trois propriétés que peu de dossiers réunissent :

**La preuve est institutionnelle.** Les claims ne reposent pas sur des captures
d'écran interprétées, mais sur les constatations d'une agence fédérale ayant
mené une instruction contradictoire. Contester ces claims reviendrait à
contester la FTC, pas SavoirNexus.

**Le montant chiffre le préjudice.** 245 millions de dollars au titre des dark
patterns, dans un ensemble de 520 millions dont le reste relève de la protection
des données des mineurs. Plus de 72 millions de remboursements effectifs avaient
été versés fin 2024.

**La pratique a cessé.** Les deux claims sont en statut `corrected` : ils
documentent un état passé, borné au 14 mars 2023, date de l'ordonnance
définitive. Ils ne pèsent donc rien dans le score de sévérité actuel — ils
restent consignés pour l'historique.

## La nuance qui compte

Une correction imposée par une autorité n'est pas une correction volontaire. Le
statut `corrected` du projet enregistre la **cessation d'une pratique**, il ne
qualifie pas l'intention de l'éditeur.

C'est délibéré : décider si un éditeur a agi de bonne foi serait un jugement,
et le projet n'en produit pas. Le lecteur dispose du fait, de sa date et de son
motif — la conclusion lui appartient.

## Ce qui reste à documenter

- L'état des interfaces après mise en conformité, qui n'a fait l'objet d'aucun
  relevé de première main dans ce fonds
- Les mécaniques de monétisation actuelles, non couvertes par l'ordonnance
- Le passe de combat, non examiné par la FTC

Ces absences ne signifient pas conformité ou non-conformité : elles signifient
qu'aucune preuve archivée n'existe encore dans le fonds. **Une fiche incomplète
est réparable ; une fiche fausse coûte un litige.**
