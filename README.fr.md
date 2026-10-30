# Ai Prompts Hub

[English](README.md) | **Français** | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

La bibliothèque de prompts communautaire — ajoute le tien, fusion auto

La bibliothèque de la communauté prompte

Ajoutez votre meilleur prompt — le robot fusionne automatiquement des PR valides. Parcourez [`prompts.md`](prompts.md) ou les catégories ci-dessous.

Contribution
1. Fork → modifier `prompts.md` → ajouter votre invite dans la bonne catégorie
2. Ouvrir un PR → **auto-fusionné**
3. Format rapide:
```markdown
### [Name](link-to-author)
> The prompt text. Explain briefly what it does.
```

Catégories de démarrage
- **Codage** — débogage, refactor, expliquer, générer
- **Ecrit** — billets de blog, documents, traduction
- **Analyse** — résumé, extrait, comparaison
- **Agents** — prompts système, design persona
- **Image** — Recettes rapides Midjourney/SDXL

Voir `prompts.md` pour la liste en direct.

L'éducation invite

```
Act as a Socratic tutor for [TOPIC]. Never give me the answer directly — ask me questions that lead me to it. Grade my reasoning after each exchange.
```

```
Create a spaced-repetition quiz on [TOPIC]. Ask one question at a time, wait for my answer, then show the correct answer with a memory hook.
```

```
Explain [CONCEPT] at three levels: to a 10-year-old, to a college student, and to a domain expert. Highlight what changes at each level.
```

Courriel et communication

```
Rewrite this email to be 40% shorter while keeping the ask unmistakably clear. Then give me a version that's firmer and one that's warmer. [EMAIL]
```

```
Draft a polite decline for this request that preserves the relationship: [CONTEXT]. Include a soft alternative I could offer.
```

Systèmes de productivité

```
Be my weekly review coach. Ask me these questions one at a time: What shipped? What slipped? What's the single most important thing next week? Then write my plan.
```

```
Extract every task, deadline, and owner from these meeting notes. Output as a markdown table sorted by deadline. [NOTES]
```

## Ajouter des développeurs

```
Act as a strict code reviewer. Review this diff for: correctness, security issues, performance, and style. Be brutally honest but specific. [CODE]
```

```
Write a minimal reproduction case for this bug, then list the 3 most likely root causes ordered by probability. [ERROR + CODE]
```

---
## Contribuer

Les pull requests sont les bienvenues : ouvre une PR, elle sera relue et fusionnée. Maintenu par [aixisstudio](https://github.com/aixisstudio), auteur de [Snitch](https://github.com/aixisstudio/Snitch), pare-feu applicatif open source.

## Licence: MIT
