Проверка на спам
===========

В DotPlant2 реализована проверка отправленных форм на спам. Для настройки выполните следующие шаги:

1. В административном разделе выберете группу свойств (/backend/properties/group?id=) которая отвечает за проверяемую форму.

2. Отредактируйте поле "Интерпритировать как" свойств формы следующим образом:
    * "Не интерпретировать" - значит не проверять поле на спам
    * "Имя" - поле отвечает за имя отправителя
    * "Контент" - в поле содержится контент сообщения

3. В разделе "Проверка на СПАМ" выберите включенный метод проверки и укажите для него ключ API. В DotPlant2 реализованны 2 метода проверки на спам - ["Чистый веб"](https://tech.yandex.ru/cleanweb/) от Яндекса и ["Akismet"](https://akismet.com/) от WordPress