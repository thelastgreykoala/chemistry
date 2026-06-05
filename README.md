# ⚛️ Химия 8 класс — Учебный портал

Учебный сайт по химии для 8 класса (учебник Gabrielyan О.С., 2025).

## Структура

```
index.html                  — главная страница (меню)
chemistry_flashcards.html   — карточки: первые 20 элементов
week2_chemistry_tasks.html  — задания §5–8 + тесты
```

## Размещение на GitHub Pages

1. Создайте репозиторий на GitHub (например, `chemistry-8`)
2. Загрузите все файлы в корень репозитория
3. Откройте **Settings → Pages**
4. В разделе **Source** выберите ветку `main` и папку `/ (root)`
5. Нажмите **Save** — сайт будет доступен по адресу:
   `https://<ваш-логин>.github.io/chemistry-8/`

## Добавление новых разделов

В `index.html` найдите блок `.cards-grid` и добавьте новую карточку по образцу:

```html
<a href="новый_файл.html" class="menu-card card-pink">
  <div class="card-icon icon-pink">🔬</div>
  <div class="card-body">
    <span class="card-tag tag-pink">Категория</span>
    <div class="card-title">Название раздела</div>
    <div class="card-desc">Описание раздела.</div>
  </div>
  <div class="card-meta">
    <div class="card-meta-info"><span>📖</span><span>Инфо</span></div>
    <div class="card-arrow arrow-pink">→</div>
  </div>
</a>
```

Доступные цветовые схемы: `card-teal` / `card-yellow` / `card-pink`  
(иконка: `icon-teal` / `icon-yellow` / `icon-pink`)
