# 📚 SavoirNexus — Open Data Catalog (CC BY-SA 4.0)

> **🌍 Language / Langue :** [🇬🇧 English](#-english-documentation) | [🇫🇷 Français](#-documentation-française)

---

## 🇬🇧 English Documentation

> **Public, sourced, and contestable knowledge base for video game preservation, consumer protection, and monetization transparency.**

This repository contains **exclusively the public Open Data catalog** (`vault/`) of the **SavoirNexus** project, licensed under [Creative Commons BY-SA 4.0](LICENSE).

*(Note: The web platform engine, real-time evaluation pipelines, and agentic verification tools are maintained in a separate repository to guarantee the integrity and security of the public dataset.)*

### 📊 Catalog Figures (October 2026)

| Category | Count | Path in Repository |
| :--- | :---: | :--- |
| **Canonical Video Game Entries** | **6,814** | [`vault/domains/games/works/`](vault/domains/games/works/) |
| **Fully Audited Games (Sourced Claims + Transparency Score)** | **69** | [`vault/domains/games/works/`](vault/domains/games/works/) |
| **Studios, Publishers & Holders** | **196** | [`vault/domains/games/orgs/`](vault/domains/games/orgs/) |
| **Documented Dark Patterns & Monetization Mechanics** | **21** | [`vault/patterns/`](vault/patterns/) |
| **Consumer Protection & Regulatory Frameworks** | **2** | [`vault/regulations/`](vault/regulations/) |
| **Formal Ontologies (`core` + `games`)** | **2** | [`vault/ontology/`](vault/ontology/) |

### 📂 Repository Structure

```text
SavoirNexus-OpenData/
├── vault/
│   ├── ontology/
│   │   ├── core.yaml                 ← Core epistemic & provenance schema
│   │   └── domains/
│   │       └── games.yaml            ← Video game preservation & monetization ontology
│   ├── domains/
│   │   └── games/
│   │       ├── works/                ← 6,814 game entries (.md with YAML frontmatter)
│   │       └── orgs/                 ← 196 studios, publishers & platforms
│   ├── patterns/                     ← 21 dark patterns (FOMO, loot boxes, server shutdowns...)
│   ├── regulations/                  ← Consumer laws & regulatory references (EU DSA/CPC, Stop Killing Games...)
│   └── inbox/
│       └── pending/                  ← Community & agent proposals awaiting human review
└── LICENSE                           ← Creative Commons Attribution-ShareAlike 4.0 International
```

### 🤝 How to Contribute (Zero Account Required on SavoirNexus)

Every claim in **SavoirNexus** must be backed by a verifiable primary source (`proven` or `inferred` with explicit provenance):

1. **Edit an existing game or studio entry**: Open the corresponding `.md` file in `vault/domains/games/works/` or `vault/domains/games/orgs/`, click the **Pencil icon (Edit)** on GitHub, and submit a Pull Request with your source URL.
2. **Propose a new fact or correction**: Create a file in `vault/inbox/pending/` using the standard candidate frontmatter:

```yaml
---
type: candidate
proposal:
  kind: fact # fact | fiche | correction | supersede
  scope: /vault/domains/games/works/the-crew
  confidence: proven
  source: https://www.stopkillinggames.com/
  rationale: >
    Added official server shutdown date and offline patch verification status.
---

Detailed description of the sourced fact or correction...
```

---

## 🇫🇷 Documentation Française

> **Base de connaissance publique, sourcée et contestable dédiée à la préservation du jeu vidéo, à la protection des consommateurs et à la transparence économique.**

Ce dépôt contient **exclusivement les données ouvertes publiques** (`vault/`) du projet **SavoirNexus**, publiées sous licence libre [Creative Commons BY-SA 4.0](LICENSE).

*(Note : Le moteur applicatif, l'interface web et les outils d'audit déterministes sont maintenus dans un dépôt séparé afin de garantir la sécurité et l'intégrité du serveur).*

### 📊 Chiffres Clés du Catalogue (Octobre 2026)

| Catégorie | Volume | Emplacement dans le dépôt |
| :--- | :---: | :--- |
| **Fiches de Jeux Vidéo Canoniques** | **6 814** | [`vault/domains/games/works/`](vault/domains/games/works/) |
| **Jeux Entièrement Audités (Faits Sourcés + Score de Transparence)** | **69** | [`vault/domains/games/works/`](vault/domains/games/works/) |
| **Studios, Éditeurs & Ayants Droit** | **196** | [`vault/domains/games/orgs/`](vault/domains/games/orgs/) |
| **Dark Patterns & Mécaniques de Monétisation Documentés** | **21** | [`vault/patterns/`](vault/patterns/) |
| **Cadres Réglementaires & Droits des Joueurs** | **2** | [`vault/regulations/`](vault/regulations/) |
| **Ontologies Formelles (`core` + `games`)** | **2** | [`vault/ontology/`](vault/ontology/) |

### 🤝 Comment Contribuer ?

1. **Corriger ou enrichir une fiche existante** : Parcourez `vault/domains/games/works/`, cliquez sur l'icône **Crayon (Modifier)** en haut à droite sur GitHub et soumettez une Pull Request accompagnée d'une source primaire vérifiable.
2. **Proposer une nouvelle fiche ou alerte consommateur** : Déposez un fichier Markdown dans `vault/inbox/pending/` en suivant le format YAML `type: candidate` présenté ci-dessus.

---

## ⚖️ License / Licence

All data in this repository is licensed under the **[Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](LICENSE)**.
