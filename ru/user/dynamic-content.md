# Динамический контент

> Динамический контент — содержит информацию с текстом, заголовком, и seo-даными. Используется для добавления [блоков](http://www.yiiframework.com/doc-2.0/guide-structure-views.html#using-blocks) и seo-данных на страницы с результатами отфильтрованных данных.

### Поля

1. Объект — объект, к которому добавляется дининамический контент
2. Маршрут — [маршрут](http://www.yiiframework.com/doc-2.0/guide-structure-controllers.html#routes) отображения, к которому добавляется дининамический контент
3. Название — идентификатор динамического контента
4. Заголовок — название страницы с динамическим контентом
5. H1 — выделеная надпись, обычно расположенная сверху контента
6. Мета-описание — описание страницы с динамическим контентом, обычно используется в поисковых снипетах
7. Название контентного блока — идентификатор блока
8. Контент — текст блока

### Создание:

1. Необходимо перейти в меню админ-панели на пункт Динамический контент (/backend/dynamic-content/index)
2. Нажать кнопку Добавить
3. Заполнить поля и нажать на кнопку Сохранить

### Редактирование:

1. Необходимо перейти в меню админ-панели на пункт Динамический контент (/backend/dynamic-content/index)
2. Нажать на иконку карандаш
3. Заполнить поля и нажать на кнопку Сохранить

### Удаление:

1. Необходимо перейти в меню админ-панели на пункт Динамический контент (/backend/dynamic-content/index)
2. Нажать на иконку корзины

### Вывод:

Простейший способ вывести динамический контент на страницу:

```php
if (isset($this->blocks['ID'])) {
    echo Html::tag('div', $this->blocks['ID']);
}
```

Где ID - название контентного блока.