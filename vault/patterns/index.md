# Patterns

Mécaniques de conception documentées, **transverses aux domaines**.

Un pattern décrit un mécanisme et sa base psychologique. Il ne porte pas de
claims : ce sont les œuvres qui l'exhibent, via la relation `exhibits`, et c'est
l'œuvre qui répond de ce qu'elle fait.

## La bibliothèque

| Pattern | Catégorie | Sévérité | Note |
|---|---|---|---|
| [Coffre aléatoire](/patterns/coffre-aleatoire) | monétisation | 5 | régulé — décision belge 2018 |
| [Achat accidentel](/patterns/achat-accidentel) | interface | 4 | régulé — ordonnance FTC 2023 |
| [Avantage compétitif payant](/patterns/avantage-competitif-payant) | monétisation | 4 | |
| [Paquet forcé](/patterns/paquet-force) | monétisation | 4 | dénoncé — plainte BEUC 2024 |
| [Résiliation difficile](/patterns/resiliation-difficile) | interface | 4 | le plus mesurable |
| [Fausse urgence](/patterns/fausse-urgence) | urgence | 3 | |
| [Monnaie intermédiaire](/patterns/monnaie-intermediaire) | monétisation | 3 | |
| [Publicité intrusive](/patterns/publicite-intrusive) | monétisation | 3 | friction artificielle |
| [Mur de progression](/patterns/mur-de-progression) | progression | 3 | le plus difficile à établir |
| [Passe saisonnier expirant](/patterns/passe-saisonnier-expirant) | urgence | 3 | |
| [Pression sociale](/patterns/pression-sociale) | social | 3 | |
| [Prix barré fictif](/patterns/prix-barre-fictif) | monétisation | 3 | |
| [Système d'énergie](/patterns/systeme-energie) | progression | 3 | |
| [Culpabilisation au refus](/patterns/confirmshaming) | interface | 2 | porte d'entrée pédagogique |
| [Récompense quotidienne](/patterns/recompense-quotidienne) | progression | 2 | nocif en combinaison |

## Pourquoi ils vivent ici et pas dans un domaine

La fausse urgence n'appartient pas aux jeux vidéo. On la retrouve dans le
e-commerce, la billetterie, l'abonnement de presse. La documenter au niveau
transverse signifie qu'un futur pack de domaine en hérite gratuitement, avec sa
base psychologique et ses régulations déjà établies.

Seul ce qui n'a de sens que pour un domaine descend dans son pack : un « mur de
progression » ne veut rien dire pour un film. Ceux-là sont déclarés en
`pattern_subcategories` dans `/ontology/domains/games.yaml`.

## Ce que porte chaque fiche

**`criteria`** — deux listes, `includes` et `excludes`, formulées de façon
**testable**. « Un compte à rebours qui se réinitialise sans que l'offre
change », pas « une urgence qui semble excessive ».

C'est la pièce la plus importante du dispositif. Un claim est factuel :
*« le compte à rebours se réinitialise à chaque session »*. Décider que **cela
constitue de la fausse urgence** est une interprétation — et c'est de là que
viendra toute contestation sérieuse.

En rendant les critères explicites et opposables, on déplace le débat au bon
endroit : on ne discute pas de la formulation d'un claim, on discute des
critères d'un pattern. Et les modifier exige une pull request motivée.

**`references`** — adosse la sévérité à des travaux publiés ou à des décisions
d'autorité. Une note de sévérité sans fondement est un jugement déguisé en
donnée.

## Le champ `severity_base`

Note de 1 à 5 attachée au pattern lui-même, avant toute contextualisation. Elle
est **pondérée par l'usage constaté** dans chaque claim — un pattern grave
employé marginalement peut peser moins qu'un pattern modéré employé
systématiquement.

Le calcul est dans `SavoirNexus.Core`, déterministe et couvert par des tests
golden. Trois points s'y jouent :

- un claim **corrigé** ne pèse plus rien — la pratique a cessé ;
- un claim **contesté** pèse moitié moins, le temps de l'instruction ;
- un claim **non publié** ne pèse pas.

## Ce que cette bibliothèque n'est pas

Une liste de griefs. Chaque fiche comporte une section « ce qui ne relève pas de
ce pattern », et ce n'est pas une précaution rhétorique : c'est ce qui rend le
pattern falsifiable. Un pattern qui engloberait tout ne documenterait rien.
