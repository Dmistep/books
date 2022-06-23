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



<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Flex:opsz,wght@8..144,100;8..144,200;8..144,300;8..144,400;8..144,500;8..144,600;8..144,700;8..144,800;8..144,900;8..144,1000&display=swap'); 

body{
    width: 90%;
    max-width: 800px;
    box-sizing: border-box;
    margin: 0 auto;
    font-size: 18px;
    color: #444;
    font-family: 'Roboto Flex', sans-serif;
}
h1,h2,h3,h4{ 
    color:#354361; 
    
}

a{
    color:#034ad8;
    text-decoration: none;
    font-weight: 500;
            
        }


</style>