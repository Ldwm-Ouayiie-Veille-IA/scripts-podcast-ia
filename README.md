# Scripts podcast — Veille IA hebdomadaire

Dépôt des **scripts de podcast de 45 minutes** produits chaque lundi matin à partir de la méta-synthèse globale du dimanche précédent.

## Rythme de publication

- **Lundi 8h Paris** (6h UTC en été CEST) : un script par semaine.
- Source unique : la méta-synthèse du dimanche de la veille, depuis le repo [veille-meta-hebdo](https://github.com/Ldwm-Ouayiie-Veille-IA/veille-meta-hebdo).

## 📂 Accéder aux scripts

➡️ **[Ouvrir le dossier des scripts](scripts/2026/)**

Depuis `scripts/2026/` : choisir le mois (ex: `04-Avril/`), puis ouvrir le fichier `AAAA-MM-JJ_script-podcast.md` du lundi voulu.

```
scripts/
└── 2026/                                ← tu arrives ici
    └── 04-Avril/
        ├── 2026-04-27_script-podcast.md
        └── 2026-05-04_script-podcast.md
```

## La chaîne éditoriale complète

Ce repo est la **dernière étape** de la chaîne de veille IA. L'architecture complète :

1. **Veilles journalières** (8 repos sectoriels) → du lundi au samedi
2. **Synthèses hebdomadaires** (dans chaque repo sectoriel) → dimanche 20h-22h30
3. **Méta-synthèse globale transversale** (repo [veille-meta-hebdo](https://github.com/Ldwm-Ouayiie-Veille-IA/veille-meta-hebdo)) → dimanche 23h
4. **Script podcast 45 min** (ce repo) → lundi 8h

## Ce que fait le script agent

Pour chaque lundi :

1. **Lit** la méta-synthèse globale du dimanche précédent (un seul fichier).
2. **Classe** les histoires par densité narrative et potentiel audio.
3. **Écrit** un script de 45 minutes prêt à être lu au micro, avec cold open, fil rouge transversal, 2-3 segments thématiques, tour rapide des terrains calmes, signaux à surveiller, outro.
4. **Intègre** citations, chiffres et sources directement depuis la méta (pas de recherche web additionnelle).
5. **Mentionne** au moins une fois chacun des 8 thèmes (même en une phrase pour les thèmes calmes).

## Format du script

- Durée cible : **45 minutes** lues à voix haute (~6500-7000 mots).
- Animateur **solo** (voix unique).
- Indications de régie intégrées (`[CHAPITRE]`, `[RESPIRATION]`, `[CITATION]`).
- Prose orale, phrases courtes, pas de jargon corporate, vouvoiement par défaut.

## Cadre éditorial

Voir [CLAUDE.md](CLAUDE.md) pour le format détaillé, la méthodologie, les règles anti-hallucination et les consignes de ton oral.

## Pull requests

Chaque script arrive sous forme de **pull request** sur une branche `claude/script-podcast-*`. Relire, merger pour archiver dans `main`.
