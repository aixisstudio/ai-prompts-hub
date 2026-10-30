# Ai Prompts Hub

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | **Русский**

Общая библиотека промптов — добавь свой, автомерж

##  The Быстрая библиотека сообщества

Добавьте свою лучшую подсказку — бот автоматически объединяет действительные PR. Browse [`prompts.md`] (prompts.md) или категории ниже.

###Вклад
1.Вилка → редактировать `prompts.md` → добавить подсказку под правильную категорию
2.Откройте PR → **авто-слияние**
3. Быстрый формат:
```markdown
### [Name](link-to-author)
> The prompt text. Explain briefly what it does.
```

##   Начальные категории
**Кодирование** — отладка, рефактор, объяснение, генерация
**Письмо** — сообщения в блоге, документы, перевод
**Анализ** — обобщить, извлечь, сравнить
**Агенты** — системные подсказки, персонифицированный дизайн
**Изображение** - Срочные рецепты Midjourney/SDXL

`prompts.md` для живого списка.

###Образование подсказывает

```
Act as a Socratic tutor for [TOPIC]. Never give me the answer directly — ask me questions that lead me to it. Grade my reasoning after each exchange.
```

```
Create a spaced-repetition quiz on [TOPIC]. Ask one question at a time, wait for my answer, then show the correct answer with a memory hook.
```

```
Explain [CONCEPT] at three levels: to a 10-year-old, to a college student, and to a domain expert. Highlight what changes at each level.
```

##   Электронная почта и связь

```
Rewrite this email to be 40% shorter while keeping the ask unmistakably clear. Then give me a version that's firmer and one that's warmer. [EMAIL]
```

```
Draft a polite decline for this request that preserves the relationship: [CONTEXT]. Include a soft alternative I could offer.
```

##Системы производительности

```
Be my weekly review coach. Ask me these questions one at a time: What shipped? What slipped? What's the single most important thing next week? Then write my plan.
```

```
Extract every task, deadline, and owner from these meeting notes. Output as a markdown table sorted by deadline. [NOTES]
```

##   Разработчики

```
Act as a strict code reviewer. Review this diff for: correctness, security issues, performance, and style. Be brutally honest but specific. [CODE]
```

```
Write a minimal reproduction case for this bug, then list the 3 most likely root causes ordered by probability. [ERROR + CODE]
```

---
## Участие

Pull request'ы приветствуются — открой PR, он будет проверен и принят. Ведёт [aixisstudio](https://github.com/aixisstudio), автор [Snitch](https://github.com/aixisstudio/Snitch) — open-source application firewall.

## Лицензия: MIT
