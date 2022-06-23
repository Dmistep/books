# linear-gradient()
[![Badge site](https://img.shields.io/badge/gradients-webref.ru-yellowgreen.svg)](https://webref.ru/course/css-advanced/gradients)


Функция `linear-gradient()` добавляет линейный градиент к фону элемента. Она выступает значением свойства `background-image` или `background`.


Синтаксис :

```css
{
background-image: linear-gradient(20deg, green, blue); 
}
```

```css
{
background-image: linear-gradient([<угол> deg | to <top, bottom и left, right>], <цвет> , <цвет>);
}
```

## Типы градиента

Позиция|Угол|Описание
:--------:|:----:|:----------|
to top|0deg|Снизу вверх.
to left|270deg-90deg|Справа налево.
to bottom|180deg|Сверху вниз.
to right|90deg-270deg|Слева направо.
to top left| | От правого нижнего угла к левому верхнему.
to top right| | От левого нижнего угла к правому верхнему.
to bottom left| | От правого верхнего угла к левому нижнему.
to bottom right| | От левого верхнего угла к правому нижнему.



