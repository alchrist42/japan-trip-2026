# Japan Trip 2026

Рабочая репа для планирования поездки и публикации короткого сайта для друзей.

## Структура

- `TRIP_CONTEXT.md` - внутренний краткий контекст для Codex.
- `TOKYO_HOTELS.md` - рабочая таблица по жилью в Tokyo.
- `docs/` - публичный сайт для GitHub Pages.
- `AGENTS.md` - правила проекта для Codex.

## Публикация через GitHub Pages

1. Создать пустой GitHub repository, например `japan-trip-2026`.
2. Добавить remote:

   ```bash
   git remote add origin git@github.com:<user>/japan-trip-2026.git
   ```

3. Убедиться, что локальная ветка называется `main`:

   ```bash
   git branch -M main
   ```

4. Сделать initial commit и push:

   ```bash
   git add .
   git commit -m "Initial trip docs"
   git push -u origin main
   ```

5. На GitHub открыть repository -> Settings -> Pages.
6. В `Build and deployment` выбрать:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/docs`
7. Нажать `Save`.

После этого сайт будет доступен по адресу:

```text
https://<user>.github.io/japan-trip-2026/
```

При каждом новом `push` изменения из папки `docs/` будут обновлять сайт.
