# Автофермы для DonutSMP

Одностраничный сайт-каталог схем для Litematica: фото построек, калькулятор материалов на нужное число копий (со счётчиком в стаках) и скачивание `.litematic` файлов.

Всё содержимое (картинки и архивы схем) встроено прямо в `index.html` — сайт полностью работает без внешних файлов.

## Схемы

- **Kelp Starter Farm** — маленькая быстрая ферма ламинарии
- **Middle Kelp Farm** — средняя ферма ламинарии (18×10×10, с крафтерами)
- **Starter Bonemeal Farm** — костная мука
- **Drainer machine** — машина осушения

## Как установить схему

1. Скачай и распакуй архив.
2. Положи `.litematic` в папку `schematics` внутри папки игры.
3. Открой меню Litematica (по умолчанию `M`), загрузи схему и поставь её на место.

## Как открыть сайт

Просто открой `index.html` в браузере — или опубликуй через GitHub Pages (см. ниже).

## Публикация на GitHub Pages

1. Создай репозиторий на github.com (например, `donutsmp-farms`).
2. Загрузи файлы:
   ```bash
   git remote add origin https://github.com/ВАШ_НИК/donutsmp-farms.git
   git push -u origin main
   ```
3. В репозитории: Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `/ (root)` → Save.
4. Сайт будет доступен по адресу `https://ВАШ_НИК.github.io/donutsmp-farms/`.
