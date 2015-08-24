# Меню административной части

> В DotPlant2 есть возможность редактирования меню административной части. Меню является многоуровневым и не содержит ограничения по вложенности, что позволяет группировать схожий функционал внутри определенного пункта, а не создавать огромную простыню, которая не помещается на экран. Редактирование меню может понадобится при добавлении модулей или расширений в CMS. Обычно это происходит автоматически, но при необходимости Вы можете изменить его сами.

В раздел редактирования меню можно попасть перейдя по ссылке `Настройки/Меню админки` в этом самом меню административной части сайта:) Она состоит из дерева элементов меню и списка элементов внутри выбранного. Выбрать действие с пунктом можно кликнув правой клавишей на элемент дерева, либо по соответствующей кнопке в таблице.

Форма пункта меню имеет следующие поля:

* `название` - название пункта меню (обычно на английском языве);
* `маршрут`- url-адрес страницы;
* `иконка` - название иконки из набора `font-awesome` без приставки `fa-`;
* `категория I18n` - категория интернационализации для перевода названия пункта меню с английского языка;
* `добавлено расширением` - название расширения, которое добавило данный пункт меню;
* `css Class` - дополнительный css класс для пункта меню;
* `роль RBAC` - название роли пользователя, которому будет доступен данный пункт меню;
* `порядок сортировки` - порядковый номер пункта меню.