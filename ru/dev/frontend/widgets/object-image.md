# Виджет изображения

> DotPlant2 CMS позволяет привязывать изображения к любой сущности (товар, страница и т.д.) прямо через административную панель, а для вывода изображений на фронтенде используется виджет `app\modules\image\widgets\ObjectImageWidget`.

Виджет может принимать следующие параметры:

* `model` - модель объекта, для которого нужно вывести изображения (обязательно)
* `viewFile` - файл отображения виджета
* `limit` - предел количества выводимых изображений
* `offset` - позиция смещения
* `thumbnailOnDemand` - ложь или истина, выводить миниатюру или нет
* `thumbnailWidth` и `thumbnailHeight` - ширина и высота миниатюры соответственно
* `useWatermark` - ложь или истина, выводить накладывать водяной знак или нет

Минимальный вызов виджета выглядит следующим образом:

```php
<?=
app\modules\image\widgets\ObjectImageWidget::widget(
	[
		'model' => $model,
	]
)
?>
```