# ⚛️ Химия 8 класс — Учебный портал / Chemistry 8 class - Learning portal

Учебный сайт по химии для 8 класса (учебник Габриелян О.С., 2025).

## Структура

```
index.html                  — главная страница (меню)
chemistry_flashcards.html   — карточки: первые 20 элементов
week2_chemistry_tasks.html  — задания §5–8 + тесты
```


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
