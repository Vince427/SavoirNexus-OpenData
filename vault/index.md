---
okf_version: "0.1"
title: SavoirNexus
description: >
  Commun documentaire, vérifiable et contestable, sur les anti-patterns des
  œuvres interactives.
license: CC-BY-SA-4.0
license_url: https://creativecommons.org/licenses/by-sa/4.0/
schema: /ontology/core.yaml
domain_packs:
  - /ontology/domains/games.yaml
canonical: https://github.com/Vince427/SavoirNexus
updated: 2026-07-22
---

# SavoirNexus — vault

Ce dossier est le **canonique**. Tout le reste du dépôt — index SQLite, API,
site — en est une projection reconstructible par une commande. Si les
projections disparaissent, rien n'est perdu ; si ce dossier disparaît, tout
l'est.

C'est un bundle [OKF v0.1](https://okf.md/spec/) : rien que du markdown à
frontmatter YAML, lisible dans Obsidian, rendu par GitHub, consommable par tout
outil compatible OKF sans intégration spécifique.

> ⚠️ **Fonds en constitution.** Les fiches présentes portent sur des œuvres et
> des organisations **réelles**, et chaque claim est adossé à une preuve
> archivée et vérifiée. Mais le fonds est **très partiel** : cinq œuvres, et la
> majorité des patterns n'est encore illustrée par aucun cas documenté.
>
> Une œuvre absente du fonds, ou dépourvue de claim sur un pattern donné, ne
> doit **jamais** être lue comme conforme : elle n'a simplement pas encore été
> documentée. L'absence de preuve n'est pas une preuve d'absence.

## Organisation

| Dossier | Contenu |
|---|---|
| [`ontology/`](/ontology/migrations/index) | Méta-schéma `core.yaml` et packs de domaine |
| [`patterns/`](/patterns/index) | Patterns transverses, tagués par domaine |
| `domains/games/works/` | Fiches d'œuvres |
| `domains/games/orgs/` | Studios, éditeurs, détenteurs de plateforme |
| `regulations/` | Textes normatifs applicables aux patterns |
| [`disputes/`](/disputes/index) | Réclamations reçues et leur instruction |
| [`inbox/`](/inbox/index) | Candidates en attente d'arbitrage — **hors canonique** |
| `assets/` | Captures référencées par les preuves |
| `fr/`, `en/` | Pages de prose du site |

## Où vit quoi

Une **œuvre** vit une seule fois, sous `domains/`, avec son champ `lang`. Elle
n'a pas deux identités selon la langue. Les dossiers `fr/` et `en/` ne
contiennent que de la prose éditoriale — méthodologie, transparence, mentions
légales — reliée par `translation_of`.

L'`inbox/` n'est **pas** de la connaissance : rien n'y est indexé, servi ni
affiché. Une candidate devient vérité au merge d'une pull request, pas avant.

## Les invariants

1. Tout claim porte au moins une preuve, chacune avec une `archive_url`.
2. Tout claim a un statut, et les transitions sont contraintes.
3. Aucun claim ne cible une personne physique.
4. Un `id` ne change jamais.

Ce ne sont pas des recommandations : `SavoirNexus.Ingestion validate` refuse
tout ce qui s'en écarte. Voir [CONTRIBUTING.md](https://github.com/Vince427/SavoirNexus/blob/main/CONTRIBUTING.md).
