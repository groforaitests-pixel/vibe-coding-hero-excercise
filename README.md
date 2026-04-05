# vibe-coding-hero-excercise

Справочник продуктовых метрик GRO для AI-тренажёров: клиентский опыт, операционка, монетизация.

## Что внутри

- **`index.html`** — самодостаточная просматриваемая страница дашборда. Определяет design-токены (`--color-*`, `--font-sans`, `--border-radius-*`) с поддержкой светлой и тёмной темы через `prefers-color-scheme` и оборачивает разметку в полноценный HTML-документ.
- **`GRO_metrics_тренажеры_v1_31032026 (1).html`** — исходный HTML-фрагмент без `<html>/<head>/<body>`, предназначенный для встраивания во внешнюю страницу, где design-токены уже определены (например, внутри Claude-артефакта или другой оболочки).

## Как посмотреть

Открыть `index.html` в любом браузере — никакой сборки не требуется.

```bash
# macOS
open index.html
# Linux
xdg-open index.html
```

## Группы метрик

| Группа | Метрики |
|---|---|
| Клиентский опыт | Session Start Rate, Drop-off, Session Duration, Artifact Save Rate, Completion Rate, Rating, Energy Score, Return Rate |
| Операционные | Token Usage + Cost per Session, Error Rate, Forced Exit Rate |
| Монетизация | Next Trainer Conversion Rate, Partner Click-through Rate |

Блок «Читать вместе» в конце страницы описывает ключевые связки метрик для интерпретации.
