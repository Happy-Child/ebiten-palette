## Требования v0.1
* Поддержка RGB модели.

* Возможность ручного ввода кода цвета в 10 (0 - 255) и 16 (0 - F) системах счисления.

В 10-ую разрешён ввод только чисел в диапазоне 0 - 255. Если ввели больше - ставим max значение

В 16-ую разрешён ввод только чисел 0-9 и букв [A-Z][a-z] и только.

* Сверху panelbar с возможность закрытия окна с palette.

* Появляется по середине экрана.

* Всегда фиксированной ширины и высоты.


## Дизайн
![img](https://i.imgur.com/TX8yYEC.png)


## Компоненты системы
- InputField
- ColorBar
- SaturationBar
- ButtonIcon


## Вопрос - ответ
1. Как рисовать RGB полосу выбора цвета?
2. Как забрать цвет на полосе палитры если курсор на (y)?
3. Point внутри SaturationBar стоит на (x, y), как забрать цвет?



