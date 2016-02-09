# anchormenu
Документация

Классический плагин для перехвата события при клике на ссылку с якорем.

Вызов

$(function () {
 $('.anchor-mnu').anchorMenu({
   level: '> li > a',
   padding: 55,
   speed: 100
 });
});

Функция вызыватся на селектор ul или класс селектора ul. Функция включает в себя три параметра:

level - Уровень вложенности. По умолчанию задается для всех ссылок 'a'
padding - Отступ от начала страницы. По умолчанию 100px
speed - Скорость анимации. По умолчанию 'slow'.