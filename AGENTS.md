# AGENTS.md — Outliving

Game Design Repository для **Outliving** — воксельной action-RPG в сеттинге
тёмного славянского фэнтези (по мотивам «Трое из Леса» Юрия Никитина).

Перед началом любой задачи прочитай `.harness/HARNESS.md` — это единый источник
правды для репозитория. Все правила дизайна, посылки, сеттинг-фильтры — там.

## Быстрый старт для AI-воркера

1. **Прочитай `.harness/HARNESS.md`** — инварианты
2. **Прочитай `.harness/designer_system_prompt.md`** — твой System Prompt
3. **Прочитай текущую Issue** — задача и критерии приёмки
4. **Работай в ветке `designer/issue-N`** от `main`
5. **Следуй циклу**: CLAIM → RESEARCH → DESIGN → PREMISES_CHECK → DELIVER

## Структура репозитория

```
outliving/
├── AGENTS.md                              # ← ты здесь
├── TZ.md                                  # Техзадание (без техники)
├── .harness/
│   ├── HARNESS.md                         # Инварианты (читай первым)
│   └── designer_system_prompt.md          # System Prompt воркера
├── docs/                                  # Существующие дизайн-документы
├── design/                                # Артефакты воркера
└── .github/                               # CI + шаблоны Issues
```
