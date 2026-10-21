# 🌐 SavoirNexus — Open Data

> **Observatoire ouvert, indépendant et contradictoire des pratiques commerciales et de la monétisation dans les jeux vidéo.**  
> Données sous licence **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**.

---

## 🎯 Mission

SavoirNexus aide les joueurs, les parents et la communauté à identifier les jeux qui respectent leurs limites (temps, argent, absence de monnaies intermédiaires prédatrices, pas de coffres aléatoires, pas de passe saisonnier expirant).

Ce dépôt contient l'intégralité du **catalogue public** :
- **20 900+ fiches de jeux vidéo** (ault/domains/games/works/)
- **Éditeurs et développeurs** (ault/domains/games/organizations/)
- **Ontologie formelle des pratiques commerciales** (ault/ontology/)
- **Claims d'audit et preuves archivées**

---

## 📂 Structure du Vault (OKF v0.1)

Le vault respecte la spécification [OKF (Open Knowledge File)](https://okf.md/spec/) :
- Tous les documents sont au format **Markdown** avec un frontmatter YAML standardisé.
- Zéro base de données opaque : **Git est la seule source de vérité**.
- Chaque claim est vérifiable par une capture d'écran, un lien de magasin officiel ou une archive archivée.

`
vault/
├── ontology/
│   ├── core.yaml                  # Méta-schéma des claims, entités et relations
│   └── domains/games.yaml         # Ontologie spécifique aux jeux vidéo
├── domains/games/
│   ├── works/                     # Fiches de jeux et audits
│   └── organizations/             # Studios et éditeurs
└── inbox/
    └── pending/                   # Propositions d'audits et contributions
`

---

## 🤝 Comment Contribuer

Vous pouvez proposer un audit ou signaler une pratique commerciale sur un jeu vidéo :
1. Créez un fichier candidate dans `vault/inbox/pending/candidate-<id-du-jeu>.md`.
2. Ouvrez une **Pull Request** sur ce dépôt.
3. Le validateur formel vérifie la conformité des schémas et des preuves.

---

## ⚖️ Licence

Le contenu et les données de ce dépôt sont publiés sous licence **[CC BY-SA 4.0](LICENSE)**.
