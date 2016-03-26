# anchormenu
###Документация

Bower
```
bower install fantasy.anchorMenu
```

Классический плагин для перехвата события при клике на ссылку с якорем.

Вызов
```javascript
$(function () {
 $('.anchor-mnu').anchorMenu({
   level: '> li > a',
   padding: 55,
   speed: 100,
   localstr: false
 });
});
```

Функция вызыватся на селектор ul или класс селектора ul. Функция включает в себя три параметра:

level - Уровень вложенности. По умолчанию задается для всех ссылок 'a'

padding - Отступ от начала страницы. По умолчанию 100px

speed - Скорость анимации. По умолчанию 'slow'.

localstr - Если св-во localstr принимает true, то с внутренней страницы при клике на ссылку с якорем будет исполняться редирект на главную с анимацией прокрутки до якоря. Работает только на доменах.
