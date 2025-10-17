# Dynamic Island (Pure CSS)

Интерактивная «Dynamic Island» на чистых HTML и CSS:
- **4 темы**: Deep Purple, Gold, Space Black, Silver
- **Анимации** появления, ховеры и раскрытие «чёлки»
- **Никакого JavaScript** — только селекторы, псевдоэлементы и градиенты

Демо локально:
```bash
# Откройте index.html в браузере
open index.html
```

## Как это устроено
- Структура разметки в `index.html`: контейнер `dynamic-island`, экран устройства, фон из двух секций, «чёлка» с контентом.
- Вся логика тем реализована через `radio`‑инпуты (`name="theme"`) и соседние селекторы `~` в `style.css`.
- Фон берётся из `background-img.png` + наложения градиентов.

## Файлы
- `index.html` — разметка устройства и «острова»
- `style.css` — стили, анимации, темы
- `background-img.png` — фон

## Вдохновение и примеры
- Стилизация и структура README ориентированы на репозитории в духе [`sh1kxrv`](https://github.com/sh1kxrv?tab=repositories) и [`dekciw`](https://github.com/dekciw?tab=repositories).

## Лицензия
MIT