# Ai Prompts Hub

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | **中文** | [日本語](README.ja.md) | [Русский](README.ru.md)

社区提示词库 — 添加你的提示词，自动合并

_详细内容（列表、链接、描述）以英文维护 — 以下章节为你指引。_

## 🧠 The community prompt library

Add your best prompt — the bot auto-merges valid PRs. Browse [`prompts.md`](prompts.md) or the categories below.

## 🪜 Contribute
1. Fork → edit `prompts.md` → add your prompt under the right category
2. Open a PR → **auto-merged** ✅
3. Prompt format:
```markdown
### [Name](link-to-author)
> The prompt text. Explain briefly what it does.
```

## 📚 Starter categories
- **Coding** — debug, refactor, explain, generate
- **Writing** — blog posts, docs, translation
- **Analysis** — summarize, extract, compare
- **Agents** — system prompts, persona design
- **Image** — Midjourney/SDXL prompt recipes

See `prompts.md` for the live list.

## 🎓 Education prompts

```
Act as a Socratic tutor for [TOPIC]. Never give me the answer directly — ask me questions that lead me to it. Grade my reasoning after each exchange.
```

```
Create a spaced-repetition quiz on [TOPIC]. Ask one question at a time, wait for my answer, then show the correct answer with a memory hook.
```

```
Explain [CONCEPT] at three levels: to a 10-year-old, to a college student, and to a domain expert. Highlight what changes at each level.
```

## 📧 Email & communication

```
Rewrite this email to be 40% shorter while keeping the ask unmistakably clear. Then give me a version that's firmer and one that's warmer. [EMAIL]
```

```
Draft a polite decline for this request that preserves the relationship: [CONTEXT]. Include a soft alternative I could offer.
```

## 🧰 Productivity systems

```
Be my weekly review coach. Ask me these questions one at a time: What shipped? What slipped? What's the single most important thing next week? Then write my plan.
```

```
Extract every task, deadline, and owner from these meeting notes. Output as a markdown table sorted by deadline. [NOTES]
```

## 💻 Developer extras

```
Act as a strict code reviewer. Review this diff for: correctness, security issues, performance, and style. Be brutally honest but specific. [CODE]
```

```
Write a minimal reproduction case for this bug, then list the 3 most likely root causes ordered by probability. [ERROR + CODE]
```

---
## 贡献

欢迎提交 Pull Request，我们会审查并合并。由 [aixisstudio](https://github.com/aixisstudio) 维护，他也是开源应用防火墙 [Snitch](https://github.com/aixisstudio/Snitch) 的作者。

## 许可证: MIT
